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
DB migration framework(s)             | Yes    | ? | 
Security framework(s)                | ACL-based | [Spring Security][10] | 
Template framework(s)                        | [Django Template Language](http://docs.djangoproject.com/en/dev/topics/templates/) | [JSP/JSTL,  Thymeleaf, Tiles, Freemarker, Velocity][18] |
Caching framework(s)                         | [Yes][17] | [Yes][16] | 
Form validation framework(s)                 | [Yes][8] | [Yes][15]
URL mapping (clean URLs, RESTful URIs)       | [Yes][7] | [Yes][14] |
HTML5                                        | ? | ? | 
REST (exposing data as RESTful web services) | [Yes][12] | [Yes][13] | 
Mobile support                               | ? | ? | 
Scaffolding tools                           | No(?) | [Spring Roo][11] | There seems to be some scaffolding tools also for Django but not widely used and most are just old scripts with no active development happening.

Other aspects which are often considered
----------------------------------------

These aspects are often considered when selecting web application framework. However I could not find any recent study including both (Django and Spring) and considering these aspects. Also evaluating these and giving ratings would require much more time.

Feature                               | Django | Spring | Comments
------------------------------------- | ------ | ------ | --------
Developer productivity                | ? | ? | 
Developer perception                  | ? | ? | 
Learning curve                        | ? | ? | 
Project health                        | ? | ? | 
Developer availability                | ? | ? | 
Job trends                            | ? | ? | 
Framework complexity                  | ? | ? | 
Rapid prototyping                     | ? | ? | 
Ease of use                           | ? | ? | 
Documentation & community             | ? | ? | 
Framework ecosystem                   | ? | ? | 
Throughput/scalability                | ? | ? | Data from [Web Framework Benchmarks][19] could be used?
Code maintenance/updates              | ? | ? | 
UX, look and feel                     | ? | ? | 


More sources and further reading
--------------------------------

* [Web frameworks comparison by David Díaz Clavijo](http://blog.websitesframeworks.com/)
* "Comparing JVM Web Frameworks" by Matt Raible ([video](https://www.youtube.com/watch?v=ygW8fJVlDxQ), [slides](http://www.slideshare.net/mraible/comparing-jvm-web-frameworks-february-2014))
* ["The 2014 Decision Maker’s Guide to Java Web Frameworks" by RebelLabs](http://zeroturnaround.com/rebellabs/the-2014-decision-makers-guide-to-java-web-frameworks/)
* ["The Curious Coder’s Java Web Frameworks Comparison" by RebelLabs](http://zeroturnaround.com/rebellabs/the-curious-coders-java-web-frameworks-comparison-spring-mvc-grails-vaadin-gwt-wicket-play-struts-and-jsf/)
* [Web framework ratings in DevRates](http://devrates.com/project/list?query=[web+framework])
* [Web Framework Benchmarks](http://www.techempower.com/benchmarks/)
* ["Top 20 Web Frameworks for the JVM" by InfoQ](http://www.infoq.com/research/jvm-web-frameworks)
* [Django Book](www.djangobook.com/)
* [Wikipedia: Web application framework](http://en.wikipedia.org/wiki/Web_application_framework)
* [Wikipedia: Comparison of web application frameworks](http://en.wikipedia.org/wiki/Comparison_of_web_application_frameworks)
* [If programming languages were vehicles](http://crashworks.org/if_programming_languages_were_vehicles/)

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
[11]: http://docs.spring.io/spring-roo/reference/html/base-web.html "Spring Roo: Web MVC"
[12]: http://spring.io/guides/gs/rest-service/ "Spring REST Service"
[13]: http://www.django-rest-framework.org/ "Django REST Framework"
[14]: http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html "Spring Web MVC framework"
[15]: https://spring.io/guides/gs/validating-form-input/ "Spring Form Validation"
[16]: http://docs.spring.io/spring/docs/current/spring-framework-reference/html/cache.html "Spring Cache Abstraction"
[17]: http://docs.djangoproject.com/en/dev/topics/cache/ "Django Cache Framework"
[18]: http://spring.io/understanding/view-templates "Spring Template Engines"
[19]: http://www.techempower.com/benchmarks/ "Web Framework Benchmarks"
