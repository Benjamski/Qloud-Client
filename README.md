![Team Pizza Beer logo](http://i.imgur.com/s1n7Uf4.png)

# FileBucket Project: Qloud File Storage

## Install

```
$ npm install
```

## About Qloud

Qloud is a cloud based file storage Single Page web Application designed to
deliver an easy to use file upload and storage servce. The design is minimalistic
and clean, to keep the focus on functionality and the user experience.

The application waas built using the following technologies:

// **List of node packages coming soon** //




## Languages and Technologies Used

  -[HTML] You know what HTML is.

  -[Handlebars](http://handlebarsjs.com/) Handlebars builds semantic HTML templates.

  -[JSHint](http://www.jshint.com/docs/) is used to prevent JavaScript error.

  -[JSCS](https://npmjs.org/package/jscs) is used to check coding conventions.

  -[NPM](https://www.npmjs.com/) is used for node package management.

  -[Node.js](https://nodejs.org/en/) Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.

  -[jQuery](https://jquery.com/) is a fast, small, and feature-rich JavaScript library. It handles things like HTML document traversal and manipulation, event handling, animation, and Ajax.

  -[Express.js](http://expressjs.com/) Minimalist JavaScript framework

  -[CSS3] Raw Cascading Style Sheets for styling our HTML

  -[MongoDB](https://docs.mongodb.com/) MongoDB is an open-source, document database designed for ease of development and scaling.

  -[Mongoose](http://mongoosejs.com/) MongoDB object modeling for Node.js that includes built-in type casting, validation, query building, business logic hooks and more, out of the box.

  -[POSTMAN](https://www.getpostman.com/) is used to test HTTP requests to APIS


## FEATURES

| **Upload File**                                                                                                                                                       | **View File**                                                                                                                                                         |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![https://gyazo.com/f8c9d8798a95ef328e0d2dbe11570b74](https://i.gyazo.com/f8c9d8798a95ef328e0d2dbe11570b74.gif)](https://gyazo.com/f8c9d8798a95ef328e0d2dbe11570b74) | [![https://gyazo.com/f965fcd4c02c3f5ca5bc1d1b8295f5bd](https://i.gyazo.com/f965fcd4c02c3f5ca5bc1d1b8295f5bd.gif)](https://gyazo.com/f965fcd4c02c3f5ca5bc1d1b8295f5bd) |
| CREATE                                                                                                                                                                | READ                                                                                                                                                                  |
| **Edit Tags**                                                                                                                                                         | **Delete**                                                                                                                                                            |
| [![https://gyazo.com/07fa2a1e1b961d3ba2565d038d087dfe](https://i.gyazo.com/07fa2a1e1b961d3ba2565d038d087dfe.gif)](https://gyazo.com/07fa2a1e1b961d3ba2565d038d087dfe) | [![https://gyazo.com/dfa013f3f4ed2424d6482c036c1a0fbc](https://i.gyazo.com/dfa013f3f4ed2424d6482c036c1a0fbc.gif)](https://gyazo.com/dfa013f3f4ed2424d6482c036c1a0fbc) |
| UPDATE                                                                                                                                                                | DESTROY                                                                                                                                                               |
| **Folder Navigation**                                                                                                                                                 | Landing Page                                                                                                                                                          |
| [![https://gyazo.com/b1b66496643af81a4a21072da39d006a](https://i.gyazo.com/b1b66496643af81a4a21072da39d006a.gif)](https://gyazo.com/b1b66496643af81a4a21072da39d006a) | [![https://gyazo.com/e9eece424bbc2d7990e8ac8fc1e2d21d](https://i.gyazo.com/e9eece424bbc2d7990e8ac8fc1e2d21d.gif)](https://gyazo.com/e9eece424bbc2d7990e8ac8fc1e2d21d) |
| AWESOME                                                                                                                                                               | CLEAN                                                                                                                                                                 |

### Standard User CRUD
- Sign up / Create Account
- Sign In / Log In
- Change Password
- Sign Out

### Resource CRUD
- Upload File
- Create Folder
- Add/Edit Tags
- Delete File/Folders

### UX touches
- Auto-Login on Sign Up
- Landing page with Sign Up / Sign In
- Notification of mismatching email and password data on Sign In
- Notification of User Email already taken
- All User files displayed on Login
- Add Folders/Files automatically updated in window




## Approach

 ***Flesh this out***

 -front end skeleton html
 -user stories
 -wireframes
 -data structure
 -back end skeleton
 -pair programming, group code alongs
 -constant communication between

 ## Our Development Process

 #### We used Trello to manage our workflow and stay on schedule

 <img src="http://i.imgur.com/nYlWO3X.gif">

 #### Group Programming

 - We regularly leveraged pair and group programming to keep all team members active in every stage of the development process and approach every problem as a cohesive unit, from multiple perspectives.

 - Any time in the development process that one of us became stuck on a feature build beyond our timebox limit, we would rotate turns with one developer "driving" the development and physically typing. Their code would be displayed on a large monitor and they would make commits while the rest of us would lead their process, troubleshoot related issues, whiteboard problems etc...

 - This may have slowed our overall rate of prograss and skewed the ownership of our commit history, but it gave every developer exposure to every stage of development and kept our momentum steady.


 #### Obstacles

 - Use of Materialized Paths to navigate through files and folders

 - Creating the breadcrumb effect to show that navigation to the user on the front end

 - Heroku deployment

 - persistent issues with integratiing navigation of folders between back and end front end.

- How do we set our application apart from obvious alternatives like dropbox? What can we do better/different?

- Learning to effectively take advantage of git team workflow, pull requests and branch management.

## Future Implementations

- Make use of drag and drop feature by using jquery plugin
- animation
- further security features
- feature to download files without opening tab / option to download
- sleek animations on folder and file crud features
- Sort files and Folders

 ## Are we missing some essential feature?

  - **Nothing is impossible!**

  - Open an [issue](https://github.com/PizzaBeer/filebucket-front-end/issues/new) and let's make the Qloud better together!

  - *Bug reports, feature requests, patches, and well-wishes are always welcome.* :heavy_exclamation_mark:

  ## FAQ

  - ***I already use dropbox, why should I use Qloud?***
  - Stop being like everyone else. Take risks, seek adventure, use Qloud.

  ## Contributing


1. Create an issue and describe your idea
2. [Fork it here](https://github.com/PizzaBeer)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Publish the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
7. Profit! :white_check_mark:

## ERD

![ERD](http://i.imgur.com/wN5N6iH.jpg)

## Wire Frames ![WireFrames](https://i.gyazo.com/0ccac675be470898568f60699475d4d7.png)

## User Stories


1. As a user, I want to store my files on a remote server, so I can access them anywhere.
2. As a user, I want an easy-to-use web interface for adding, viewing, removing my files.
3. As a user, I want my files accessible only to me.
4. As a user, I want to be able to add tags to my files.
5. As a user, I want to be able to tag files to organize them.
6. As a user, I want to be able to update my files.
7. As a user, I want to see my uploaded files upon signin.
8. As a user, I want to see my files sorted by folders.
9. As a user, I want an intuitive UI.
10. As a user, I want my files accessible only to me.
11. As a user, I want to search by tags.
12. As a user, I want to be able to add tags to my files.
13. As a user, I want all my files to show upon login, and be able to navigate
through folders and files in a way that's easy to understand.


## Contributing

1. Create an issue and describe your idea
2. [Fork it here](https://github.com/PizzaBeer)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Publish the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
7. Profit! :white_check_mark:

## The Back End Api Server

The back end repository for the API that this web application consumes can be
found [here](https://github.com/PizzaBeer/filebucket-back-end).

## Deployment

The gh-pages hosted front end for this application is [here](http://pizzabeer.github.io/filebucket-front-end )

## DEVELOPED WITH LOVE by Team Pizza Beer
| [![Ben Adamski](http://i.imgur.com/O7eT5sX.jpg)](https://github.com/benjamski) | [![Natalie Djerf](https://avatars3.githubusercontent.com/u/17814071?v=3&s=460)](https://github.com/natdjerf) | [![Roberto DelValle](https://avatars1.githubusercontent.com/u/17518260?v=3&s=400)](https://github.com/rdelvallej32) | [![Zachary Simpson](https://avatars2.githubusercontent.com/u/9722944?v=3&s=400)](https://github.com/cuprous) |
|--------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| [Ben Adamski](https://benjamski.com)                                           | [Natalie Djerf](https://github.com/natdjerf)                                                                 | [Roberto DelValle](https://github.com/rdelvallej32)                                                                 | [Zachary Simpson](https://github.com/cuprous)                                                                |


© 2016+, [General Assembly, Inc.](http://generalassemb.ly) [MIT License].<br>


Authored and maintained by Ben Adamski | Natalie Djerf | Roberto DelValle | Zachary Simpson and with help from :fa-heart:[contributors](https://github.com/PizzaBeer/filebucket-front-end/graphs/contributors).

[MIT License]: http://mit-license.org/
