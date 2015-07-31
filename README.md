Webcom is a [BAAS](https://en.wikipedia.org/wiki/Mobile_Backend_as_a_service) with a complete client framework. 
Developers can build real-time applications and communication services and deploy them easily. Here are some examples :

* chat
* audio and video conference apps
* collaborative apps
* data exchange for [IoT](https://en.wikipedia.org/wiki/Internet_of_Things)
* multiplayer games ...
* data repositories like address book or user preferences

### Get started ###


* [Quickstart][Quickstart]
   Get started in minutes. Read and send data in realtime with Webcom. Discover how Webcom is really easy to use.

* [Data Sync framework][DataSyncDoc]
   this is the core of Webcom. These API enable to store and to synchonise data between multiple devices instantaneously. The backend is offered "as a service". Thus most of the time you don't need to install any server.

* [Webcom communication SDK][ComSDKDoc]
   Client framework (javascript library) can be retrieved to add communication features on your website (chat, audio/video call, conferences, presence). You can customize/enrich it if necessary.

* [Use cases][Examples]
   A demonstration of a communication service based on Webcom Framework. Create your own account and use tchat, audio & video calls and conferences, presence. You can also use the code of this demo as a sample of Webcom usage


### Concept ####


Chosen concept is "Backend-as-a-service".

Basically, webcom-base is:

* a high level datastore
* with a tree data structure (tree nodes store strings, numbers, booleans, or nested children)
* with flexible pubsub available on any node of the tree
* with a document describing "security rules"


### Key features ###


* Data synchronisation between multiple devices, data storage

* One unified real-time backend for every kind of services:
	* communication services: presence, chat, audio & vidéo call & conference, message publication…
	* collaboratives apps: photo or document sharing, live sketching, location sharing...
	* Internet of Things: data exchange between multiple devices, sensors and apps, at home or everywhere

* Usable for Web apps. Native apps coming soon

* Backend as a Service: each service project has its own data space and use API on Internet

* Service logic is mainly on the client side: low impact on network when a service is deployed or upgraded

* Natively adapted for
	* data persistency: activity log, chat history, call log, address book…
	* group communication: multi-device data exchange, group chat, audio/video conferencing between multiple accounts/users or between multiple devices of a same account/user

* Based on Web technologies
	* NAT/proxy/firewall traversal: where HTTPS can pass, Webcom access will be available

* Based on scalable middleware (NoSQL database)


[Quickstart]: https://webcom.orange.com/doc/tutorial-quickstart.html
[DataSyncDoc]: https://webcom.orange.com/doc/Webcom.html
[ComSDKDoc]: https://webcom.orange.com/doc/tutorial-comsdk_WebRTC.html
[Examples]: https://webcom.orange.com/doc/tutorial-examples.html