Django vs Spring
================

This is a quick comparison of the following web application frameworks. Study is based on internet resources linked within the text and listed in the end.
- Django (version 1.7.1)
- Spring Framework (version 4.1.1)


Features of modern web application framework
--------------------------------------------

Feature                               | Django | Spring | Comments
------------------------------------- | ------ | ------ | --------
Ajax                                  | Yes    | Yes | 
MVC framework                         | Full stack | [Spring MVC][6] |Django's interpretation of MVC is different. See [Django Book: The MTV (or MVC) Development Pattern][9] |
MVC push-pull                         | Push   | Push | 
Internationalization and localization | Yes    | Yes | 
Object-relational mapping (ORM)       | [Django Models][1] | [Hibernate][2], [JDO][2], [JPA][3] | 
Testing framework(s)                  | Yes    | [Yes][5] | 
DB migration framework(s)             | Yes    | 
Security framework(s)                | ACL-based | [Spring Security][10] | 
Template framework(s)                        | [Django Template Language](http://docs.djangoproject.com/en/dev/topics/templates/) | 
Caching framework(s)                         | [Cache Framework](http://docs.djangoproject.com/en/dev/topics/cache/) | 
Form validation framework(s)                 | [Django Forms API][8] | 
URL mapping (clean URLs, RESTful URIs)       | [Yes][7] | Yes |
HTML5                                        | ??? | ???
REST (exposing data as RESTful web services) | ??? | ???
Mobile support                               | ??? | ???
Scaffolding tools                           | No(?) | No(?) | There seems to be some tools for both but not widely used and most are just old scripts with no active development happening.

Other aspects which are often considered
----------------------------------------

These aspects are often considered when selecting web application framework. However I could not find any recent study including Django and Spring considering these aspects. Also evaluating these and giving ratings would require much more time.

Feature                               | Django |  Spring
------------------------------------- | ------ | ------
Developer productivity                | ? | ?
Developer perception                  | ? | ?
Learning curve                        | ? | ?
Project health                        | ? | ?
Developer availability                | ? | ?
Job trends                            | ? | ?
Framework complexity                  | ? | ?
Rapid prototyping                     | ? | ?
Ease of use                           | ? | ?
Documentation & community             | ? | ?
Framework ecosystem                   | ? | ?
Throughput/scalability                | ? | ?
Code maintenance/updates              | ? | ?
UX, look and feel                     | ? | ?


More sources and further reading
--------------------------------

* "Comparing JVM Web Frameworks" by Matt Raible ([video](https://www.youtube.com/watch?v=ygW8fJVlDxQ), [slides](http://www.slideshare.net/mraible/comparing-jvm-web-frameworks-february-2014))
* ["The 2014 Decision Maker’s Guide to Java Web Frameworks" by RebelLabs](http://zeroturnaround.com/rebellabs/the-2014-decision-makers-guide-to-java-web-frameworks/)
* ["The Curious Coder’s Java Web Frameworks Comparison" by RebelLabs](http://zeroturnaround.com/rebellabs/the-curious-coders-java-web-frameworks-comparison-spring-mvc-grails-vaadin-gwt-wicket-play-struts-and-jsf/)
* [Web framework ratings in DevRates](http://devrates.com/project/list?query=[web+framework])
* [Web Framework Benchmarks](http://www.techempower.com/benchmarks/)
* [Wikipedia: Web application framework](http://en.wikipedia.org/wiki/Web_application_framework)
* [Wikipedia: Comparison of web application frameworks](http://en.wikipedia.org/wiki/Comparison_of_web_application_frameworks)

[1]: https://docs.djangoproject.com/en/dev/topics/db/models/ "Django Models"
[2]: http://en.wikipedia.org/wiki/Hibernate_%28Java%29 "Hibernate"
[3]: http://en.wikipedia.org/wiki/Java_Data_Objects "JDO"
[4]: http://en.wikipedia.org/wiki/Java_Persistence_API "JPA"
[5]: http://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/testing.html "Spring Framework Testing"
[6]: http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html "Spring MVC"
[7]: https://docs.djangoproject.com/en/dev/topics/http/urls/ "Django URL dispatcher"
[8]: http://docs.djangoproject.com/en/dev/ref/forms/api/#ref-forms-api "Django Forms API"
[9]: http://www.djangobook.com/en/2.0/chapter05.html#the-mtv-or-mvc-development-pattern "Django Book: The MTV (or MVC) Development Pattern"
[10]: http://projects.spring.io/spring-security/ "Spring Security"


