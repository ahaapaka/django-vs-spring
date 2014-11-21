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

Python vs Java
--------------

Aspect                | Python | Java | Comments
-------------| ------ | ------ | --------
Productivity | + |  | See: [22], [23], [24]. In lines of code (LOC) per hour speed is practically same but because Python programs are shorter and simpler the developers are significantly more productive. |
Expressiveness | + | | Python programs are more concise and compact (typically 3-4 times shorter) because of dynamic typing and built-in high-level data types. |
Performance (runtime speed) |  | + | See: [20], [21]. Performance depends on implementation but Python is generally expected to be run slower because of runtime typing. |
Popularity | + | + | See: [25]

### Type systems (Python vs Java)

Characteristic  | Python type system | Java type system | Comments
--------------- | ------------------ | ---------------- | --------
Type expression | implicit | explicit | 
Type compatibility and equivalence | [structural type system][27], [duck typing][31] | [nominal type system][26] |
Type checking | [dynamic type-checking][28] | [static type-checking][29] | 
Strong vs weakly typed | [strongly typed][30] | [strongly typed][30] |

More sources and further reading
--------------------------------

### Django vs Spring

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

### Python vs Java

* ["Python & Java: A Side-by-Side Comparison" by Steve Ferg](http://pythonconquerstheuniverse.wordpress.com/2009/10/03/python-java-a-side-by-side-comparison/)
* ["Popularity vs Productivity vs Performance" by Kyle Hailey](http://datavirtualizer.com/popularity-vs-productivity-vs-performance/)
* "An empirical comparison of C, C++, Java, Perl, Python, Rexx, and Tcl" by by Lutz Prechelt ([PDF](http://page.mi.fu-berlin.de/prechelt/Biblio//jccpprt_computer2000.pdf))
* "Programming Language Productivity" by Connelly Barnes ([PDF](http://www.connellybarnes.com/documents/language_productivity.pdf))
* ["Programming languages ranked by expressiveness"](http://redmonk.com/dberkholz/2013/03/25/programming-languages-ranked-by-expressiveness/)
* ["The Computer Language Benchmarks Game"](http://benchmarksgame.alioth.debian.org/) ([Python3 vs Java on x64 quad-core](http://benchmarksgame.alioth.debian.org/u64q/benchmark.php?test=all&lang=python3&lang2=java&data=u64q))
* ["Python vs. Java: An update to a subjective speed comparison"](http://www.snaplogic.com/blog/python-vs-java-an-update-to-a-subjective-speed-comparison/)

### Libraries for reporting and graphs

* ["ReportLab Open-source PDF Toolkit"](http://www.reportlab.com/opensource/)
* ["Outputting PDFs with Django"](https://docs.djangoproject.com/en/dev/howto/outputting-pdf/)
* ["ReportLab Documentation"](http://www.reportlab.com/software/documentation/)

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
[20]: http://benchmarksgame.alioth.debian.org/u64q/benchmark.php?test=all&lang=python3&lang2=java&data=u64q "The Computer Language Benchmarks Game: Python3 vs Java on x64 quad-core"
[21]: http://www.snaplogic.com/blog/python-vs-java-an-update-to-a-subjective-speed-comparison/ "Python vs. Java: An update to a subjective speed comparison"
[22]: http://page.mi.fu-berlin.de/prechelt/Biblio//jccpprt_computer2000.pdf "An empirical comparison of C, C++, Java, Perl, Python, Rexx, and Tcl by by Lutz Prechelt"
[23]: http://www.connellybarnes.com/documents/language_productivity.pdf "Programming Language Productivity by Connelly Barnes"
[24]: http://pythonconquerstheuniverse.wordpress.com/2009/10/03/python-java-a-side-by-side-comparison/ "Python & Java: A Side-by-Side Comparison by Steve Ferg"
[25]: http://datavirtualizer.com/popularity-vs-productivity-vs-performance/ "Popularity vs Productivity vs Performance by Kyle Hailey"
[26]: http://en.wikipedia.org/wiki/Nominal_type_system "Wikipedia: Nominal type system"
[27]: http://en.wikipedia.org/wiki/Structural_type_system "Wikipedia: Structural type system"
[28]: http://en.wikipedia.org/wiki/Type_system#Dynamic_type-checking_and_runtime_type_information "Wikipedia: Dynamic type-checking"
[29]: http://en.wikipedia.org/wiki/Type_system#Static_type-checking "Wikipedia: Static type-checking"
[30]: http://pythonconquerstheuniverse.wordpress.com/2009/10/03/static-vs-dynamic-typing-of-programming-languages/ "Static vs. dynamic typing of programming languages by Steve Ferg"
[31]: http://en.wikipedia.org/wiki/Duck_typing "Wikipedia: Duck typing"
