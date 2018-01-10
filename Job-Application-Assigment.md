## Job application assignment for Android

### What you need to do?

* Take a [git class in codeschool](https://www.codeschool.com/courses/try-git) if you haven’t already.
* Create a private repo called “evolve-android-assignment” in [bitbucket](https://bitbucket.org)
* Do as instructed below
* Push your code to the repo (make sure that you have multiple number of commits with proper messages) 
* Invite careers@evolveasia.co to your particular private repo
* Invite careers@evolveasia.co to your MBaaS platform

### Assignment

Create a contact management application using [Firestore](https://firebase.google.com/docs/firestore/) with a simple login using [Firbase Authentication](https://firebase.google.com/docs/auth/) that must include an email signup, along with atleast one Social Media platform of your choice. 

Your app should let users:
* Add/Edit new contact, 
* List existing contacts,
* Show contact detail page,
* Schedule a periodic check for any updates in the user's contact database via background service or a job scheduler.

Once contact information is loaded (both listing and detail) data should persist. Any persistance mechnism can be used, i.e., cache or database.

Design as you wish, keeping material design principles in mind.

### Criteria for judgement

* Object Oriented approach used in project.
* Strict use of **MVP** or **MVVM** architecture in your project.
* It is **MANDATORY that you use these 2 Android libraries; [RxJava](https://github.com/ReactiveX/RxJava), and [Dependency Injection](https://google.github.io/dagger/)**; use [Retrofit](http://square.github.io/retrofit/) if there are network calls that not provided by the Firebase SDK.
* **Basic Unit and Functional testing included.**
* Proper naming conventions for XML and Java files.
* Proper use of ViewGroup(s) and View(s).
* Proper use of Android API(s).
* Project structure.


### Bonus points

* Using Kotlin for development.
* Integration with a CI platform.
* Use of relevant design patterns.
* If you can use relevant 'Material Design' components in your application.
* If you write readme file with screenshots and short description of your application.
