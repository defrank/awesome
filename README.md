# Awesome Resources

<!-- vim-markdown-toc GFM -->

- [Collaboration](#collaboration)
  - [Code Review](#code-review)
- [Computer Science](#computer-science)
  - [Algorithms](#algorithms)
  - [Data Structures](#data-structures)
  - [CS Practice](#cs-practice)
- [Courses](#courses)
- [Databases](#databases)
  - [SQL](#sql)
- [Editors](#editors)
  - [VI(m)](#vim)
- [Interviewing](#interviewing)
- [Computer Networking](#computer-networking)
- [Cloud Computing & Infrastructure](#cloud-computing--infrastructure)
  - [Amazon Web Resources (AWS)](#amazon-web-resources-aws)
  - [Infrastructure-as-Code](#infrastructure-as-code)
    - [Terraform & OpenTofu](#terraform--opentofu)
- [Containers](#containers)
  - [Docker](#docker)
- [DevOps](#devops)
  - [Continuous Integration and Deployment (CI/CD)](#continuous-integration-and-deployment-cicd)
  - [Monitoring](#monitoring)
    - [Prometheus](#prometheus)
  - [Reliability (SRE)](#reliability-sre)
- [Operating Systems](#operating-systems)
  - [Commandline Interface (CLI)](#commandline-interface-cli)
  - [Linux](#linux)
    - [Linux Distrobutions](#linux-distrobutions)
- [Privacy](#privacy)
- [Programming](#programming)
  - [Learn Programming](#learn-programming)
    - [Beginner Programming](#beginner-programming)
    - [Intermediate Programming](#intermediate-programming)
  - [Learn a New Language](#learn-a-new-language)
  - [Go Lang](#go-lang)
    - [Beginner Go](#beginner-go)
    - [Idiomatic Go](#idiomatic-go)
    - [Intermediate Go](#intermediate-go)
  - [Python](#python)
    - [Beginner Python](#beginner-python)
    - [Idiomatic Python (Being Pythonic)](#idiomatic-python-being-pythonic)
    - [Intermediate Python](#intermediate-python)
    - [Advanced Python](#advanced-python)
    - [Python Web Frameworks](#python-web-frameworks)
- [Software Engineering](#software-engineering)
  - [Tech Lead & Staff+](#tech-lead--staff)
  - [Systems Design](#systems-design)
- [Version/Revision Control Systems (VCS/RCS)](#versionrevision-control-systems-vcsrcs)
  - [Git](#git)
- [More Awesome](#more-awesome)

<!-- vim-markdown-toc -->

## Collaboration

### Code Review

- [thoughtbot/guides/code-review](https://github.com/thoughtbot/guides/tree/main/code-review)
  -- excellent for async communication in general
- [google/eng-practices/review](https://google.github.io/eng-practices/review/)


## Computer Science

- https://roadmap.sh/computer-science
- [apeman/awesome_computer_science](https://github.com/apeman/awesome_computer_science#readme)
- [prakhar1989/awesome-courses](https://github.com/prakhar1989/awesome-courses#readme)

### Algorithms

- [Visualizing Algorithms](https://bost.ocks.org/mike/algorithms/)
- [tayllan/awesome-algorithms](https://github.com/tayllan/awesome-algorithms#readme)

### Data Structures

- [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

### CS Practice

- [LeetCode](https://leetcode.com/problemset/)

## Courses

- [MIT OpenCourseWare (OCW)](https://ocw.mit.edu/search/)

## Databases

- [numetriclabz/awesome-db](https://github.com/numetriclabz/awesome-db#readme)

### SQL

- [r/SQL/wiki](https://www.reddit.com/r/SQL/wiki/index/)

## Editors

### VI(m)

- [mzlogin/vim-markdown-toc](https://github.com/mzlogin/vim-markdown-toc#readme)

## Interviewing

- [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/)

## Computer Networking

- [An Introduction to Computer Networking](https://intronetworks.cs.luc.edu/current2/html/)
- [The TCP/IP Guide](http://www.tcpipguide.com/free/index.htm)
- [What is DNS? | How DNS Works | Cloudflare](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
- [What is SSL? | SSL Definition | Cloudflare](https://www.cloudflare.com/learning/ssl/what-is-ssl/)
- [What is the Network Layer? | Network vs. Internet Layer | Cloudflare](https://www.cloudflare.com/learning/network-layer/what-is-the-network-layer/)
- [facyber/awesome-networking](https://github.com/facyber/awesome-networking#readme)
- [nyquist/awesome-networking](https://github.com/nyquist/awesome-networking#readme)
- [r/networking/wiki](https://www.reddit.com/r/networking/wiki/index/)

## Cloud Computing & Infrastructure

### Amazon Web Resources (AWS)

- [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws#readme)
- [open-guides/og-aws](https://github.com/open-guides/og-aws#readme)

### Infrastructure-as-Code

#### Terraform & OpenTofu

- [shuaibiyy/awesome-tf](https://github.com/shuaibiyy/awesome-tf#readme)

## Containers

### Docker

- [Friz-zy/awesome-linux-containers](https://github.com/Friz-zy/awesome-linux-containers#readme)
- [The Docker Handbook](https://docker-handbook.farhan.dev/)
- [docker for beginners](https://docker-curriculum.com/)
- [veggiemonk/awesome-docker](https://github.com/veggiemonk/awesome-docker#readme)

## DevOps

- https://roadmap.sh/devops

### Continuous Integration and Deployment (CI/CD)

- [cicdops/awesome-ciandcd](https://github.com/cicdops/awesome-ciandcd#readme)

### Monitoring

- [Enapiuz/awesome-monitoring](https://github.com/Enapiuz/awesome-monitoring#readme)
- [awcodify/awesome-monitoring](https://github.com/awcodify/awesome-monitoring#readme)
- [crazy-canux/awesome-monitoring](https://github.com/crazy-canux/awesome-monitoring#readme)
- [Monitoring Distributed Systems](https://landing.google.com/sre/sre-book/chapters/monitoring-distributed-systems/)
- [Practical Alerting](https://landing.google.com/sre/sre-book/chapters/practical-alerting/)
- [USE Method](http://www.brendangregg.com/usemethod.html)
- [RED Method](https://grafana.com/blog/2018/08/02/the-red-method-how-to-instrument-your-services/)

#### Prometheus

- [awesome-prometheus-alerts](https://github.com/samber/awesome-prometheus-alerts?tab=readme-ov-file)

### Reliability (SRE)

- [DORA Metrics](https://en.wikipedia.org/wiki/DevOps_Research_and_Assessment#DORA_Four_Key_Metrics)
  - **Deployment Frequency:** How often an organization successfully
    releases to production
  - **Lead Time for Changes:** The amount of time it takes a commit to
    get into production
  - **Change Failure Rate:** The percentage of deployments causing a
    failure in production
  - **Mean Time to Recovery/Restore (MTTR):** How long it takes an
    organization to recover from a failure/outage in production;
    [not to be confused with MTTRepair, MTTResolve, and MTTRespond](https://www.atlassian.com/incident-management/kpis/common-metrics)
- [Google SRE Books](https://sre.google/books/)
- [awesome-sre](https://github.com/dastergon/awesome-sre#readme)

## Operating Systems

- https://www.tutorialspoint.com/operating_system/index.htm

### Commandline Interface (CLI)

- [The Missing Semester of Your CS Education | MIT](https://missing.csail.mit.edu/)

### Linux

- [Linux Journey](https://linuxjourney.com/)
- [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [inputsh/awesome-linux](https://github.com/inputsh/awesome-linux#readme)

#### Linux Distrobutions

- [ArchLinux](https://archlinux.org/) as my personal favorite distro
- [Fedora](https://docs.fedoraproject.org/en-US/docs/) for
  enterprise/work use, which is also the base distro for CentOS and
  Red Hat Enterprise Linux (RHEL)
- [Gentoo](https://www.gentoo.org/)
- [Linux from Scratch](https://www.linuxfromscratch.org/) for hardcore
  learning
- [Slackware](http://www.slackware.com/index.html)

## Privacy

- [Lissy93/awesome-privacy](https://github.com/Lissy93/awesome-privacy#readme)
- [What is Data Privacy? | Cloudflare](https://www.cloudflare.com/en-gb/learning/privacy/what-is-data-privacy/)
- [pluja/awesome-privacy](https://github.com/pluja/awesome-privacy#readme)

## Programming

### Learn Programming

#### Beginner Programming

- [Bento Technology Education](https://bento.io/topics)
- [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books)
- [Runestone Academy Library of Books](https://runestone.academy/ns/books/index)
- [r/learnprogramming/wiki/books](https://www.reddit.com/r/learnprogramming/wiki/books/)
- [r/learnprogramming/wiki/faq](https://www.reddit.com/r/learnprogramming/wiki/faq/)
- [r/learnprogramming/wiki/online](https://www.reddit.com/r/learnprogramming/wiki/online/)
- [r/learnprogramming/wiki](https://www.reddit.com/r/learnprogramming/wiki/index/)

#### Intermediate Programming

- [Refactoring Guru](https://refactoring.guru/refactoring)

### Learn a New Language

- [Learn X in Y Minutes](https://learnxinyminutes.com/)

### Go Lang

- [avelino/awesome-go](https://github.com/avelino/awesome-go#readme)

#### Beginner Go

- [Learn Go in Y Minutes](https://learnxinyminutes.com/docs/go/)
- [A Tour of Go](https://go.dev/tour/list)
- [How to Write Go Code](https://go.dev/doc/code)

#### Idiomatic Go

- [Managing Module Source](https://go.dev/doc/modules/managing-source)
- [Organizing a Go Module](https://go.dev/doc/modules/layout)
- [Effective Go](https://go.dev/doc/effective_go)

#### Intermediate Go

- [The Go Programming Language Specification](https://go.dev/ref/spec)

### Python

- [vinta/awesome-python](https://github.com/vinta/awesome-python#readme)

#### Beginner Python

- [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- [Practical Python Programming](https://dabeaz-course.github.io/practical-python/Notes/Contents.html)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/2e/)
- [r/learnpython/wiki](https://www.reddit.com/r/learnpython/wiki/index/)

#### Idiomatic Python (Being Pythonic)

- [PEP 8 - Style Guide for Python Code](https://peps.python.org/pep-0008/)
- [PEP 20 - The Zen of Python](https://peps.python.org/pep-0020/)
- [The Hitchhiker's Guide to Python](https://docs.python-guide.org/)
  -- except I recommend [Poetry](https://python-poetry.org/docs/) over Pipenv
- [The Little Book of Python Anti-Patterns](https://docs.quantifiedcode.com/python-anti-patterns/)

#### Intermediate Python

- [Python Cookbook](http://www.dabeaz.com/cookbook.html)
- [Obey the Testing Goat!](http://www.obeythetestinggoat.com/pages/book.html)
- [Full Stack Python](http://www.obeythetestinggoat.com/pages/book.html)
- [Design Patterns in Python](https://refactoring.guru/design-patterns/python)
- [Python Design Patterns](https://python-patterns.guide/)
- [Ultimate Python](https://github.com/huangsam/ultimate-python)

#### Advanced Python

- [Python Wiki - Advanced Books](https://wiki.python.org/moin/AdvancedBooks)

#### Python Web Frameworks

- [Django](https://docs.djangoproject.com/) is the first web framework
  you should learn as it will teach you the Model-View-Controller (MVC)
  pattern and it comes batteries included so you can focus on getting
  things done and/or learning if you're a beginner
- [Bottle.py](https://bottlepy.org/) is the second web framework to
  learn more about the internals of how they work -- it's contained in a
  single file
- [FastAPI](https://fastapi.tiangolo.com/) for those that want a more
  modern framework that they can customize to their needs

## Software Engineering

- [Software Engineering at Google](https://abseil.io/resources/swe-book)

### Tech Lead & Staff+

- [StaffEng](https://staffeng.com/)
- [The Manager's Path](https://www.oreilly.com/library/view/the-managers-path/9781491973882/)

### Systems Design

- [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer#readme)

## Version/Revision Control Systems (VCS/RCS)

### Git

- [Pro Git book](https://git-scm.com/book/en/v2)
- [dictcp/awesome-git](https://github.com/dictcp/awesome-git#readme)
- [phillipadsmith/awesome-github](https://github.com/phillipadsmith/awesome-github#readme)

## More Awesome

- [All Awesome Lists](https://github.com/topics/awesome)
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome#readme)
