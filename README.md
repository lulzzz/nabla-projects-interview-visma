# nabla-projects-interview-visma
![nabla-projects-interview-visma](http://home.nabla.mobi/sample/images/mroizo.1f00120c.png)

[![License](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](https://github.com/AlbanAndrieu/nabla-projects-interview-visma/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/nabla-projects-interview-visma/Lobby.svg)](https://gitter.im/nabla-projects-interview-visma/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Java project for an interview request by visma

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.pitest/pitest/badge.svg?style=flat)](https://maven-badges.herokuapp.com/maven-central/org.pitest/pitest)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/AlbanAndrieu/nabla-projects-interview-visma)
[![Travis Build Status](https://travis-ci.org/AlbanAndrieu/nabla-projects-interview-visma.svg?branch=master)](https://travis-ci.org/AlbanAndrieu/nabla-projects-interview-visma)
[![Jenkins Build Status](http://home.nabla.mobi:7072/jenkins/job/nabla-projects-interview-visma-nightly/badge/icon)](http://home.nabla.mobi:7072/jenkins/job/nabla-projects-interview-visma-nightly)
[![Quality Gate](http://home.nabla.mobi:9000/api/badges/gate?key=com.nabla.project.sample.interview.visma:visma:master)](http://home.nabla.mobi:9000/dashboard/index/com.nabla.project.sample.interview.visma:visma:master)

Dependency Status using [versioneye](https://www.versioneye.com/users/AlbanAndrieu)

[![Versioneye Status](https://www.versioneye.com/user/projects/55e70677a65c8c000e00a65a/badge.svg?style=flat)](https://www.versioneye.com/user/projects/55e70677a65c8c000e00a65a)
[![Dependency Status](https://img.shields.io/david/AlbanAndrieu/nabla-projects-interview-visma.svg?style=flat-square)](https://david-dm.org/AlbanAndrieu/nabla-projects-interview-visma)
[![devDependency Status](https://img.shields.io/david/dev/AlbanAndrieu/nabla-projects-interview-visma.svg?style=flat-square)](https://david-dm.org/AlbanAndrieu/nabla-projects-interview-visma#info=devDependencies)

[![Code Climate](https://codeclimate.com/github/AlbanAndrieu/nabla-projects-interview-visma/badges/gpa.svg)](https://codeclimate.com/github/AlbanAndrieu/nabla-projects-interview-visma)
[![Test Coverage](https://codeclimate.com/github/AlbanAndrieu/nabla-projects-interview-visma/badges/coverage.svg)](https://codeclimate.com/github/AlbanAndrieu/nabla-projects-interview-visma/coverage)

[![OpenCollective](https://opencollective.com/nabla-projects-interview-visma/backers/badge.svg)](#backers)
[![OpenCollective](https://opencollective.com/nabla-projects-interview-visma/sponsors/badge.svg)](#sponsors)

[![Xing](http://www.xing.com/img/buttons/45_fr_btn.gif)](http://www.xing.com/profile/Alban_Andrieu)

The challenge
================

Here is the programming challenge:

### Payment schedule

Problem Description

    Below, please find a simple development task which we use for new employments in the development department.

    The task should be solved using Java.
    The solution should be returned with full source and if possible also as an executable under Windows or on a web server accessible using MS Internet Explorer.

    Programming test
    Create a simple application which can be used for calculation of the cost from a housing loan.

    The application should have a simple user interface where the user can specify the desired amount and the payback time in years.
    For simplicity we assume a fixed interest of 5.5% per year during the complete payback time.
    The interest should be connected to the loan type in such a manner that different loan types can have different interests.
    When selecting amount and payback time, the application should generate a monthly payback plan based on the series loan principle, i.e. you pay back an equal amount each month and add the generated interest.
    The interest is calculated every month.

    The application should be made in such a manner that it can easily be extended to calculate a payment plan for other types of loans, for instance car loan, spending loan etc. with different interests. Also bear in mind that it should be easy to extend the application to cover other payback schemes as well. We do not expect this to be implemented.

    Feel free to choose this being a desktop application or a web application, but we expect that you demonstrate reasonable use of the available language functionality for abstraction, interfaces, inheritance, a good class structure and show a good programming practice. We are focused on code quality and good design, so it is nice if you add a design sketch.
    You will not be judged for correctness in the interest calculation or a fancy GUI:

------------------

### Result

Please find below output of this sample:

- Source code repository : [github](https://github.com/AlbanAndrieu/nabla-projects-interview-visma)

- Jenkins : [jenkins](http://home.nabla.mobi:7072/jenkins/job/nabla-projects-interview-visma/)

- Sonar metrics : [sonar](http://home.nabla.mobi:9000/dashboard/index/2831)

TODO : The compiled, source, and Javadoc JAR files will be uploaded as downloads [here](https://github.com/AlbanAndrieu/nabla-projects-interview-visma/downloads).

The generated site will be committed to the [gh-pages branch](https://github.com/AlbanAndrieu/nabla-projects-interview-visma/tree/gh-pages) and visible [here](http://albanandrieu.github.io/nabla-projects-interview-visma/).

Remarks : visma installer is produced during the jenkins build , especially [here](http://home.nabla.mobi:7072/jenkins/job/nabla-installer-visma/).
In order to install, double click on the [VISMAInstaller.jar](http://home.nabla.mobi:7072/jenkins/job/nabla-installer-visma/lastSuccessfulBuild/artifact/visma-installer/target/VISMAInstaller.jar)

On unix, please make sure you can execute the installer :

```
$ chmod 755 VISMAInstaller.jar
$ sudo ./VISMAInstaller.jar
```

Once installed :

```
$ cd /usr/local/visma-installer-1.0.1-SNAPSHOT
$ sudo chmod 755 ./run.sh
$ sudo ./run.sh start
```

You can find a basic GUI at http://localhost:9090/loan.xhtml
Enjoy!!!

------------------

### WhiteSource security tests

[WhiteSource](www.whitesourcesoftware.com) is providing free open source analysis solution to this project, as part of its on-going support to the open source community

------------------

### Swagger REST

git clone https://github.com/swagger-api/swagger-ui.git
cd swagger-ui
sudo docker build -t swagger-ui-builder .
sudo docker run -p 127.0.0.1:8080:8080 swagger-ui-builder

http://localhost:8080

http://online.swagger.io/

http://editor.swagger.io/#/

### My resources

Other resources can be found on my [googlecode](https://code.google.com/p/alban/w/list) wiki:

Below resources are available from outside my network :

- Set up your workstation : [workstation](https://github.com/AlbanAndrieu/ansible-workstation)

- Set up your build environment : [servers](https://github.com/AlbanAndrieu/ansible-nabla)

- Nexus : [nexus](http://home.nabla.mobi:8081/nexus/index.html#welcome)

- Phpmyadmin : [phpmyadmin](http://home.nabla.mobi:7070/phpmyadmin)

Only for local users to the network :

- Elasticsearch / Logstash / Kibana: [logstash](http://192.168.0.29:80/)

- Monit monitoring: [monit](http://192.168.0.29:3737)

- Mon monitoring: [mon](http://192.168.0.29:7070/cgi-bin/mon.cgi)

- Supervisor: [supervisor](http://192.168.0.29:9042/)

- Statistic : [awstats](http://192.168.0.29:7070/cgi-bin/awstats.pl?config=home.nabla.mobi)

- Disk usage : [philesight](http://192.168.0.29:7070/cgi-bin/philesight.cgi)

------------------

### My opensource projects

On [GitHub](https://github.com/AlbanAndrieu) I have mostly [Ansible](http://www.ansible.com/home) roles.

I am trying to contribute as much as possible (instead of creating new projects). The projects I have created are shared on the Ansible repository [ansible-galaxy](https://galaxy.ansible.com/list#/users/1487)

All the roles I am using are gathered inside a main role [ansible-nabla](https://github.com/AlbanAndrieu/ansible-nabla).

The main project provides a continuous delivery build farm and everything needed for a dev, systems admin, QA, UI, or a release manager.

You will also have stuff like :

 - [jenkins](http://jenkins-ci.org/) (scheduler)
 - [sonar](http://www.sonarqube.org/) (metrics)
 - [nexus](http://www.sonatype.org/nexus/) (repository)
 - [docker](https://www.docker.com/) (provisioning)
 - [vagrant](https://www.vagrantup.com/) (provisioning)
 - [virtualbox](https://www.virtualbox.org/) (provisioning)
 - [logstash](http://logstash.net/) (monitoring)
 - [eclipse](https://eclipse.org/home/index.php) (with basic plugins),
 - [za-proxy](https://code.google.com/p/zaproxy/) (security)
 - [jmeter](http://jmeter.apache.org/) (performance)
 - [visualVM](http://visualvm.java.net/) (performance)
 - [selenium](http://www.seleniumhq.org/) and Xvfb (End2End test)

There is also a FrontEnd [apache](http://httpd.apache.org/) with mod [pagespeed](https://developers.google.com/speed/pagespeed/), [fail2ban](http://www.fail2ban.org/wiki/index.php/Main_Page), DeniedOfService, [AWStats](http://www.awstats.org/), a [Varnish](https://www.varnish-cache.org/) load balancer, [Zabbix](http://www.zabbix.com/), Mon, [Monit](http://mmonit.com/monit/), [Supervisor](http://supervisord.org/), [Jboss](http://www.jboss.org/), [Tomcat](http://tomcat.apache.org/) ready and more.

Essentially, there is a bit more than the basic tools for a production, staging, dev environment all configured to work together with as much security as possible.

My "old" project [nabla](https://code.google.com/p/alban/) which is using [andromda](http://www.andromda.org/index.html) as an UML code generator.
I am now using this project more because it generates a lot of code and it is resource-demanding for my devops environment.
This project is using JBoss, Seam, Hibernate, Spring,GWT, JSF, Arquillian, ... So it was quite hard to get Jacoco with mutation testing to work with it.
In this repo there's also some sample projects used as ProofOfConcept

 - Database best pratices [nabla-databases-integration](http://home.nabla.mobi:7072/jenkins/job/nabla-databases-integration/)

 - Server integration best pratices [nabla-uml-integration](http://home.nabla.mobi:7072/jenkins/job/nabla-servers-integration/)

 - UML best pratices [nabla-uml-integration](http://home.nabla.mobi:7072/jenkins/job/nabla-uml-integration/)

The goal is mostly to ensure that any of my code will be able to work with any [database](http://home.nabla.mobi:7072/jenkins/job/nabla-databases-matrix/) on any [servers/browsers](http://home.nabla.mobi:7072/jenkins/job/nabla-browsers-matrix/) using [selenium](http://home.nabla.mobi:7072/jenkins/job/nabla-servers-jsf-simple-selenium/).

------------------

### VISMA : An opensource project to showcase best pratices

You're invited to have a quick look at the project below (it has some of the quality metrics that I am using at work, like unit tests, integration tests, mutation tests, performance tests, load tests, end2end tests, functional tests)
 - [Jenkins](http://home.nabla.mobi:7072/jenkins/job/nabla-projects-interview-visma/)
 - [Sonar](http://home.nabla.mobi:9000/dashboard/index/418)

Visma is a very basic code done for an interview that you can easily install using [IZPack](http://izpack.org/) at [installer](http://home.nabla.mobi:7072/jenkins/job/nabla-installer-visma/lastSuccessfulBuild/artifact/visma-installer/target/)
The goal is to provide an easy Maven starter with basic integration and metrics for any code interview working.
The goal is also to have as many testing tools ready to work altogether (like junit, mock, selenium, cucumber).
because there is always some form of incompatiblity between them...
The GUI is working on jetty! It is basic, but it has coverage, debug mode, monitoring (JMX and NewRelic) and even some perf testing.
The code is not yet using the best tool like REST, and AngularJS and has no database.
So like this, a dev can mesure the quality of his work.
It takes 1 hour to build for 1000 lines of code on an old laptop...

Writing code is just one step among many others: building, testing, documenting, releasing, packaging, deploying, monitoring

Thanks for reading!

License
-------

[Apache v2](http://www.apache.org/licenses/LICENSE-2.0.html)

***

Alban Andrieu

[linkedin](fr.linkedin.com/in/nabla/)
