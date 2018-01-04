# Ideas for Google Summer of Code

Welcome to Freeplane!
[Freeplane](https://sourceforge.net/projects/freeplane) is an Open Source project for Mind Mapping, Knowledge Management, Project Management.
It helps to organize and communicate your ideas and knowledge in the most effective way.

Freeplane is applying to be a mentoring Organization for the Google Summer of Code 2018 edition.

## Project ideas

Freeplane core team has started development of Freeplane server as a green field project which allows to collaboratively develop and synchronize Freeplane mind maps from different devices and clients.

The server receives map updates as an event stream from the clients and can disctribute them instantly or when a new client connects. Map updates have different types. And connected clients do not need to understand each of them. It makes possible to write clients which at the beginning only need to process the map structure and the node text updates. All other kinds of information can be ignored, and thus the same map can be processed on different devices safely and even at the same time getting instant updates.

It makes possible to continue use a feature rich mind map application and have power of collaboration and sharing mind maps among different computers and users.

It also allows to develop web and mobile clients supporting only small subset of freeplane functionality. The map can still be processed on the full freeplane client because no information is lost in this process.

Now it is a perfect time for new developers who want to develop nice web or mobile app to be added to freeplane ecosystem to get in touch with us because new APIs and protocols are defined right now and could be adapted to your needs too.

### Freeplane web client (prototype)
This project can start implementation of java script mind map editor client for web browsers using Freeplane server as a backend. It should make Freeplane mind maps accessible and editable from every internet browser. Different to existing online only editors the maps are instantly shared with Freeplane clients combining accessibility from everywhere with rich application power.

  * **Technology:** JavaScript, OAuth 2.0, Web Sockets, Frontend Framework like React or Angular 2 or later - you name it.
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev
    * Volker https://sourceforge.net/u/boercher

### Freeplane android or iOS client (prototype)
This project can start implementation of android or iOS mind map editor app using Freeplane server for collaboration and synchronisation. It should make Freeplane mind maps accessible and editable from android or iOS smart phones and tablets. Differently from existing apps the maps can be instantly shared with Freeplane clients combining accessibility from everywhere with rich application power.

  * **Technology:** OAuth 2.0, Web Sockets, your language of choice for android or iOS development
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev


### Freeplane desktop client improvement
This project is the original application which is continiously developed since 2007. You are welcome to extend its functionality and make the improvements accessible to many thousands of freeplane users.

  * **Source code:**  https://github.com/freeplane/freeplane/tree/client
  * **Technology:** Java 8, Swing, OSGi, OAuth 2.0, Web Sockets, Gradle
  * **OSS Licence:** GPL 2 or later
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev

### Freeplane server development
This project is developing and implementing asynchronous collaboration on mind maps. It should users to make changes independently to mind maps and have the changes propagate automatically to all already connected or brought up clients.

  * **Source code:**  https://github.com/freeplane/freeplane-server
  * **Technology:** Java 8, Spring, OAuth 2.0, Web Sockets, Gradle
  * **OSS Licence:**
  * **Mentors**:
    * Felix https://sourceforge.net/u/fnatter


## Contact

Subscribe to the developer mailing list at http://freeplane-developer.996965.n3.nabble.com/ and introduce yourself and start the discussion

You can contact also the project lead directly by e-mail to dimitry (at) freeplane (dot) org

Get in touch with the user community at https://sourceforge.net/p/freeplane/discussion/758437/


## About your project application

Your proposal can contain the following information, plus anything you think is relevant:

* Your name
* Title of your proposal
* Abstract of your proposal
* Detailed description of what you are going to contribute
* Mention the details of your academic studies, any previous work, internships
* Relevant skills that will help you to achieve the goal (programming languages, frameworks)?
* Any previous open-source projects (or even previous GSoC) you have contributed to and links.
* Do you plan to have any other commitments during GSoC that may affect your work? Any vacations/holidays? Will you be available full time to work on your project? (Hint: do not bother applying if this is not a serious full time commitment)
