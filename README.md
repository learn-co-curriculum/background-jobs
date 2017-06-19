# Background Jobs 

### Introduction

Background jobs are used when we need to perform tasks that are not part of the standard request response cycle.  Why would we ever want to do this?  Two reasons: 

The first is when we have a scheduled task that we need to regularly occur.  For example, every day check various news sources to gather any articles on your favorite topic.

The second case relates more directly to performance.  There are times that when the user makes a request, part of the task that needs to be performed takes a long time.  We don't want the entire response to have to wait on this one piece, so we send this task to a background job, and then send the user an updated response when the task has resolved.  

### Resources on Background Jobs

Take a look at the following resouces regarding background jobs: 

* [Background Jobs](http://blog.scoutapp.com/articles/2016/02/16/which-ruby-background-job-framework-is-right-for-you)
* [Railscast on Background Jobs](https://www.youtube.com/watch?v=IkqW9ww3z8Q)
* [ActiveJob RailsGuide](http://guides.rubyonrails.org/v4.2/active_job_basics.html)
<p class='util--hide'>View <a href='https://learn.co/lessons/background-jobs'>Background Jobs</a> on Learn.co and start learning to code for free.</p>
