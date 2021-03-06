!SLIDE centereverything bullets
# Ruby on Rails Workshop

!SLIDE image
# Anatomy of a Web Request
![Internet](/images/slides/internet.png)

!SLIDE bullets
# Anatomy of a HTTP Request
* ![URL](/images/slides/url.png)
* <span style="color:red">the scheme</span>
* <span style="color:blue">the hostname or domain</span>
* <span style="color:green">the path</span>
* <span style="color:orange">the query or parameters</span>
* HTTP request includes an initial line with the path and some other stuff (GET, POST, etc.), headers, and an optional body
* HTTP response includes an initial line with response code and some other stuff, headers, and body (with your HTML or other data in it)
* How did this all come to be?  

!SLIDE image
# Inside the Rails server
![Inside Rails](/images/slides/inside_rails.png)

!SLIDE bullets
# What is Rails?  What is Ruby?
* Rails is a framework, a set of conventions and code that help do all of the stuff that is common to web applications
* Rails is there to help you handle and respond to web requests
* Ruby is a programming language that is the primary language of Rails
* Rails helps you get an application up and running very fast and makes it easy to modify
* Ruby also makes it easy to modify by letting you change code on the fly
* There is more to say than this...
* "Many of the companies you all know and love use Ruby in some capacity: Amazon, BBC, Cisco, CNET, IBM, JP Morgan, NASA, and Yahoo!. Many of the fastest-growing web-based companies have been built using Ruby on Rails: Scribd (over 70 million readers each month), Groupon (over 38.5 million subscribers in North America), Basecamp (millions of users). All in all, more than 200,000 web sites are using Ruby on Rails." -- [Business Insider](http://articles.businessinsider.com/2011-05-11/tech/30035869_1_ruby-rails-custom-software)

!SLIDE bullets
# What We Are Doing Today
* Building a Rails application from scratch so you can experience the full cycle of development
* You will be organized into a small group with a TA and go step-by-step through the process with plenty of chance to ask questions
* We've divided the workshop up into 5 segments.  Each segment will begin with a short lecture from a TA and then each workshop group will go through that section of the curriculum.
* Those who need extra help can get it from "floater" TAs and those who finish early can work on optional extra credit extensions (or take a break)

!SLIDE bullets
# What You Should Do Tomorrow
* Start building your own app (or play outside)
* But wait, will I be ready? Yes, and here's why...

![Do Tomorrow](/images/slides/do_tomorrow.png)

!SLIDE bullets
# Knowing How to Find the Answers
* Let's say you need to add a feature to your site like logging in with Facebook or paginating a big list of products, you can bet it has been done before and you can find information on how to do it. 
  * [Google](http://www.google.com)
  * [Github](http://www.github.com)
* Let's say you're getting an error when you try to load a page or seeing one in your server logs, others have probably gotten the same error before: 
  * [Stackoverflow](http://www.stackoverflow.com) ([Example](http://stackoverflow.com/questions/11996767/joining-2-elements-at-once))
  * [Google](http://www.google.com)
* Let's say you're trying to write ruby code to do something to a list of objects
  * Try [the documentation](http://api.rubyonrails.org/)

!SLIDE bullets
# BUGS!  
* Mistakes and errors are an integral part of development.  They happen *all the time* to *everyone*.
* Rails is designed to minimize their effect on your app:
  * Separate development and production environments
  * Automated testing
  * Easy, highly-specified set up and reproduction of a development environment for an app

![Grace Hopper](/images/slides/grace_hopper_first_bug.png)

!SLIDE bullets
# Open Source: a Practice and an Ethos
* Did you notice that there was nothing you had to buy to get your development environment set up?  Ruby and Rails are open source
* Open Source has a technical meaning based on the license on the source code.  Open source code can be freely shared and used (though there are sometimes restrictions on how it can be used)
* Open Source is also an ethos.  A practice of sharing code within the community which strengthens the whole community.  And it's not just altruism.  
  * Companies hiring will look at your Github repositories to evaluate your work, they'll notice if you have a lot of points for answering questions on Stackoverflow.
  * Your code may benefit from improvements from others who use it
  * The wealth of freely available ruby gems (think libraries of code that perform specific functions) makes it faster and easier for everyone to develop new applications
* The ethos extends farther, to community events and sharing like this event. 

!SLIDE bullets
# Let's Get Started!

