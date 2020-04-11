---
layout: default
title: Comparison of GroupVine v1 and v20
---

## New Features:

 *  New Email Feed "Gallery" view in addition to familiar "Listing" view.

 *  Pages that members and the public can reach (your subscribe page,
    your email feed, and member profile pages) are themed to use
    colors based on your account's custom primary color.

 *  Add multiple, Email Widgets into a single email and download
    consolidated spreadsheet with results.

 *  Trivial to add standard Email Widgets for Feedback, RSVPs, and Counts

 *  Easily embed a member sign-up form in your own website

 *  Emails can be archived to keep your Email Feed tidy

 *  Email Widgets and personalization variables can be inserted into
    emails composed in and sent from sender's familiar inbox

 *  Define exactly the information you'd like to track for each member
    by adding custom attributes which can even be used like lists to 
    address a set of members.

 *  Customize the account description in your main email feed, your
    member sign-up page, and your member's profile page

 *  Friendlier, more natural and flexible membership import and export 
    file format, including the customizeable member attributes.

 *  Easily define customized, reusable email "templates"

 *  Easier management of email file attachments

 *  Upgraded, mobile-friendly and more responsive state-of-the-art UI


## Other advanced features:

*  Simpler site name for your accounts of the form 
   ```centralvalley.groupvine.com``` rather than 
   ```www.groupvine.com/centralvalley```.

*  Cleaner rewritten from addresses of the form 
   ```sue.smith{gmail.com}@groupvine.com``` rather than
   ```sue.smith-at-gmail.com.user@groupvine.com``` rather than

*  Cleaner targetted email addresses for list-, attribute-, 
   and EW-response based email addresses, of the form
   ```volunteer=yes.maybe+staff~~cve@groupvine.com```.

*  From address always rewritten, DKIM keys always added, so all
   emails should now pass all SPF, DKIM, and DMARC security checks.

*  All membership management and a number of other 
   operations can be performed via email with attached spreadsheets.

*  Secure API to permit multiple accounts to be managed by a 
   3rd party

## Backup Notes:

### Migration:

* use ```<community>.groupvine.com``` rather than
  ```www.groupvine.com/<community>``` for web pages.  Main account and
  sub-group email addresses remain unchanged.  List addresses are
  simpler (like ```<listname>~~<community>@groupvine.com```)

*  Say goodbye to the "notes" field and fixed address fields in import
  files and member profile pages.  Now custom attributes can be
  defined to hold whatever makes sense for your community, and are
  imported, exported, and otherwise managed just like any of the old
  fixed attributes.


### Scalable & State-of-the-art:

 * More scalable EW and email engine architecture

*  Consolidated, state-of-the-art development and production platforms

*  Comprehensive suite of automated end-to-end tests of all major
   functions of email engine.

*  Key web UI and EW servers client code in Angular / Typescript, 
   mobile-responsive, single-page web apps

*  All server running in node.js v10 / Express / Typescript

*  All code stored as npm packages on github

*  All email files shared using Amazon elastic network file system

*  Database consolidated in PostgreSQL 10.6


