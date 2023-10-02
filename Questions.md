1. Name some of the differences between an Author and a Publisher.

Author instance is used for content creating, editing and managing content(Sites, Assets etc). These instances are not exposed publically and only authorized users access this instance and create/modify web pages using available components. Content ready to be published for the end user are replicated from the Author instances.

Publish instance delivers the published content on Auhtor to the end users. In general, Authoring of webpages is not done on these instances.

2. What is the Dispatcher and what are some of its purposes?
   Dispatcher module helps in caching and load balacing content which improves website performance. The main purposed of it are to Cache content(Static/dynamic) to improve page loads, in load balacing to handle high traffic and is also used for URL rewriting.

3. Name some of the open source technologies that AEM uses and name provide some of the functionality it provides.

Jackrabbit(Oak in newer versions), Apache Sling, and OSGI

All these 3 are part of AEM architecure.
Jackrabbit/oak specification for how the content is stored, Sling framework helps us access the content stored by resourace mapping(REST) and OSGI provides a modular archieture to control individual java components
