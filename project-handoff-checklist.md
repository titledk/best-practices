# Project Handoff Checklist

Things to take care off before handing off a project.

## Site

- [ ] Clear whether or not to use the `www` prefix
- [ ] Favicon (including [vector favicon for Safari](http://blog.iconfactory.com/2015/11/the-new-favicon/) and mobile icons)   
_Has a favicon been set up?_ - use a [web based generator](http://www.favicon-generator.org)
- [ ] Do we have a cookie policy plugin?
- [ ] Has (Google) Analytics been set up?
- [ ] Print stylesheet?


## Device Compatibility

- [ ] Does the project work in browsers promised?    
Go through the site on IE + make some screenshots on Browserstack


## Languages

- [ ] Is the project localized in the actual language? (check html source)
- [ ] Are dates being displayed properly?

## Infrastructure

- [ ] Backups    
_Have backups been setup?_
  - [ ] Onsite
  - [ ] Offsite
- [ ] What's the caching strategy? Is there a need for load testing?
- [ ] Are outgoing / transactional mails working? For mission critical mails, consider using services like [Mandrill](http://mandrill.com) or [Mailgun](http://www.mailgun.com)
