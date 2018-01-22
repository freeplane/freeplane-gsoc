# Ideas for Google Summer of Code

Welcome to Freeplane!
[Freeplane](https://sourceforge.net/projects/freeplane) is an Open Source project for Mind Mapping, Knowledge Management, Project Management, and more.
It helps to organize and communicate your ideas and knowledge in the most effective way.

Freeplane is applying as a mentoring Organization for the Google Summer of Code 2018 edition.

## Project ideas

Freeplane core team has started development of Freeplane server as a greenfield project which allows to collaboratively develop and synchronize Freeplane mind maps from different devices and clients.

The server enables users of the feature-rich Freeplane mind map application to use the power of collaboration and sharing mind maps among different computers and users. It also allows the development of web and mobile clients that support only a subset of Freeplane features while still being able to fully collaborate with the Freeplane rich client because no information is lost in the process.

The server receives map updates as an event stream from the clients and distributes them instantly or when a new client connects. There are different types of map updates and a connected client does not need to understand all of them. This feature makes it possible to create feature-limited clients which - at least initially - only need to process the map structure and the node text updates. All other kinds of information can be ignored, and thus the same map can be processed on different devices safely and even at the same time getting instant updates.

Now is the perfect time for new developers to join us to develop a web or mobile app that will be part of the Freeplane ecosystem. The new APIs and protocols are defined right now and can be adapted to your needs.

### Freeplane web client (prototype)
This project starts the implementation of a JavaScript mind map editor client for web browsers using the Freeplane server as a backend. It makes Freeplane mind maps accessible and editable from every internet browser. Different to existing online only editors the maps are instantly shared with Freeplane clients combining accessibility from everywhere with rich application power.

  * **Technology:** JavaScript, OAuth 2.0, Web Sockets, Frontend Framework like React or Angular 2 or later - you name it.
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev
    * Volker https://sourceforge.net/u/boercher

### Freeplane Android or iOS client (prototype)
This project starts the implementation of an Android and/or iOS mind map editor app using the Freeplane server for collaboration and synchronisation. It should make Freeplane mind maps accessible and editable from Android and/or iOS smartphones and tablets. Differently from existing apps the maps can be instantly shared with Freeplane clients combining accessibility from everywhere with rich application power.

  * **Technology:** OAuth 2.0, Web Sockets, your language of choice for Android or iOS development
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev


### Freeplane desktop client improvement
This project is the original application, which is continuously developed since 2007. You are invited to extend its functionality and make your improvements accessible to many thousands of Freeplane users.

  * **Source code:**  https://github.com/freeplane/freeplane/tree/client
  * **Technology:** Java 8, Swing, OSGi, OAuth 2.0, Web Sockets, Gradle
  * **OSS Licence:** GPL 2 or later
  * **Mentors**:
    * Dimitry https://sourceforge.net/u/dpolivaev

### Freeplane server development
This project is developing and implementing asynchronous collaboration on mind maps. It enables users to edit mind maps and have their changes propagated automatically to all connected and newly launched clients.

  * **Source code:**  https://github.com/freeplane/freeplane-server
  * **Technology:** Java 8, Spring, OAuth 2.0, Web Sockets, Gradle
  * **OSS Licence:**
  * **Mentors**:
    * Felix https://sourceforge.net/u/fnatter


## Contact
Subscribe to the developer mailing list at http://freeplane-developer.996965.n3.nabble.com/, introduce yourself and start a discussion.

You can also contact the project lead directly via e-mail to dimitry (at) freeplane (dot) org

Get in touch with the user community at https://sourceforge.net/p/freeplane/discussion/758437/
