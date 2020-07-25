# Test

- Linux 
  -
  - Refers to the large collection of open-source operating systems based on the famous Linux kernel.
  - The intresting thing about linux is its open source feature and that anyone with appropraite skills can easily edit it and contribute to it.
  - Due to this there are many flavours or distros of linux available out there some of the famous ones being Ubuntu, Mint, Kali and even Android is linux based.
  - The code for linux is licensed under GPLv2 or GNU Public License and it an amalgamation of contributions by many authors so its sometimes its even referred to as GNU/Linux.
  - Like any other operating system linux consistes of its own set of user applications, bootloader, kernel, desktop env. and deamons.
  - The most intresting thing about linux is its high customizability and ability for a user to tweak it self according to a users needs with required skills.
  - Linux is mostly associated with a command line interface which gives almost unrestricted access to users which considerd the most important feature of Linux not offered by other OS.

- Bash
  -
  - GNU Bash or commonly known as Bash (Bourne-Again SHell) is a command line language used as default login shell for most Linux distros.
  - Bash shell is intergral part of almost every famous Linux and when started greets us with a prompt of dollar sign (**$**)
  
  ```$```
  
  - Common bash commands let you interact with bash your system in general 
  ```
  /mnt/e$ cd Programs
  /mnt/e/Programs$ ls
  2020_eSwap_1.exe    GrammarlyAddInSetup.exe    PowerISO7-x64.exe  Rainmeter-4.4-r3349-beta.exe  TakeOwnership.zip   nexus.zip
  /mnt/e/Programs$ cd ..
  /mnt/e$
  ```
  - Bash also lets your execute multiple commands using formatting like
  ```
  /mnt/e/Programs$ cd .. && ls
  ```
  - It also features roboust feature like text editors *vim*, *emacs* and *nano*.
  - Bash scripting is a important feature which helps us make use of scripts and text files ending in **.sh** to automate tasks and execute multiple commands via a single file.

- VSCode
  -
  - VSCode or Visual Studio Code is a light, robust source code editing environment which provides us tools and features which helps us work fluently.
  - Some common features which it uses is Syntax Highlighting, syntactical error detection, code completion and refactoring.
  - It also containts fetaures like Git version management and directly downloading and connecting to git repos online allowing full git management acess inside the environment itself.
  - It has plugins which helps us ease our tasks and supports almost all languages from C++ to Kotlin.
  
- MySQL & SQL
  -
  - MySQL is a famous Reltional Database Management System which is based on SQL or Structured Query Language and it open-source.
  - MySQL stored data in different realted tables rather than one large collection so as to maintain consistency ins searches.
  - MySQL is open-source so anyone can edit it according ot their needs.
  - Being in SQL the databases of MySQL can be easily accessed using a commnd line interface including updates, addition or removal of entries or even tables.
  - It works on server based system which can be run on any simple system too which we feed commands to get results in return.

- MongoDB
  -
  - MongoDB is a NoSQL database system which stored databases in a flexible, JSON like documents.
  - It offeres wide variety of datastructres and it not strict in choices of it like MySQL and thus offers a flexible document to document independent database system.
  - The document to document independent system allows us to store data in key-value pair system where each document can have its own choice of fiels though documents collected together surely need to be realted serving the basic purpose of a database.
  - It is highly scalable as it is schema and relation free unlike RDBMS.
  - JavaScript querying is available and various javascript functions can be used to access MongoDB.
  - MongoDB used replica i.e. it maintains various copies of same data so that if the primary collection fails then some secondary collection can be used to access and restore the data.
  - MongoDB also has sharding which helps distributing data over servers.

- Elasticsearch
  -
  - Elasticsearch is a distributed, open source search and analytics engine built on Lucene for all types of data, structured or unstructured.
  - Unlike conventional DBMS which don't support full text searches, Elasitcsearch support full text seaeches very efficiently using indexing.
  - Indexing is technique where documents with similar features are collected or indexed together for better seraching. before feeding to the database every document is log and indexed in a complex manner which helps ElasticSearch work the way it does.
  - It uses JSON based REST API to refer to Lucene features.
  - ElasticSearch does a denormalized document storage near every possible repository where it resides which helps it perform faster searches and make data readily available. 
  - It comes apcked with two other systems Logstash and Kibana and together build the ELK or Elastic Stack.

- Redis
  -
  - Redis is an open-source, in-memory data storage system used as database and caching system.
  - It also stores data in form of key-value pairs and is fast due because of its ability to build a cache for recently called data.
  - Redis supports almost all programming langauges which is in use like *C++, Python, Java, C, 
  - Its caching feature helps in fast data requests and it also used simple server commands to built and access the data like *SET* and *GET*
  ```
  127.0.0.1:6379> SET x "Hello"
  OK
  127.0.0.1:6379> GET x 
  "Hello"
  ```
  - General datatypes like Strings and List and more complex datasets like sorted lists and hashed tables are supported by Redis.

- Pandas
  -
  - Pandas is famous python library which stands for Python Data Analysis Library which gives a lot of intrestin capability to read and write data stored in files inside python environments.
  - Everything inside pandas is pandas dataframe which refers to a collection of related data in form of tables, generally retrieved from files like **.csv**, **SQL**, **MS Excel** 
  - Each dataframe is lighter as compared to normally loading the whole data into the system and this is what makes pandas so reliable and fast.
  - Pandas also offers greate variety of tools to access the data seperate them from coloumns or directly retrieve it for inside numpy or python lists.
  - It supports features of data handling like insertion and deletion or even splitting and merging different databases.
  - It has integral options for handling missing datapoints using different kinds of featurs pertaining to the rest of the data.
  - 
- Flask
  - 
  - Flask is a microweb framework written in Python.
  - Microframeworks like Flask don't come with any dependencies or extensions and it totally user customizable acoording to your needs.
  - The basic dependencies of Flask is Werkzeug which is WSGI and jinja2 which is a template library.
  - Flask being a webframework helps you host websites using its extensions and features.
  - Its is easy to build dynamic webistes with flask and ad dfeatures like form validation and upload handing using extensions.

- Tornado
  - 
  - Tornado is python web framework built for asynchronous request handling as it works on nonboking network io.
  - It a webframework not based on the conventional python WSGI. 
  - Tornado is generally used for handling lot of user request and when long lenght user connections needs to be maintained while handling other requests.
  - Any computationally expensive task handled to Tornado is passed on to another thread so that no blocking occurs.
- GCP
  - 
  - GCP or Google Cloud Platform is a cloud computing service which ranges from storage to analytics and computational power.
  - The major GCP services are Google CLoud Storage, Google Cloud Compute and Google Cloud SQL.
  - Cloud works on server farms managed by comapies which in this case is Google and provide this facilities at a cost.
- Git & Github
  -
  - Git is the most famous and widely used version control system for software and source code developers.
  - Github is a webiste which offers free of cost online Git service for storage and verion control for developers.
  - Version control is generally used to track changes in files across time and check, revert or refer to any pervious stages of a program.
  - Git supports non-linear development like code merging and forking thus allowing developers full freedom to experiment with features while maintining thw working version at bay.

### Refrences
> https://opensource.com/resources/what-bash
> https://www.educative.io/courses/master-the-bash-shell/3j8399P3M6M
> https://en.wikipedia.org/wiki/Bash_(Unix_shell)

> https://www.redhat.com/en/topics/linux/what-is-linux
> https://www.linux.com/what-is-linux/
> https://opensource.com/resources/linux

> https://www.quora.com/What-is-Visual-Studio-Code-Why-is-it-used

> https://dev.mysql.com/doc/refman/8.0/en/what-is-mysql.html
> https://www.siteground.com/tutorials/php-mysql/mysql/
> https://searchoracle.techtarget.com/definition/MySQL

> https://en.wikipedia.org/wiki/MongoDB
> https://intellipaat.com/blog/what-is-mongodb/
> https://www.tutorialspoint.com/mongodb/index.htm

> https://en.wikipedia.org/wiki/Elasticsearch
> https://www.elastic.co/what-is/elasticsearch
> https://towardsdatascience.com/an-overview-on-elasticsearch-and-its-usage-e26df1d1d24a
> https://qbox.io/blog/what-is-elasticsearch

> https://www.educative.io/edpresso/what-is-pandas-in-python

> https://redis.io/topics/introduction
> https://codeburst.io/redis-what-and-why-d52b6829813
> https://en.wikipedia.org/wiki/Redis
> https://www.educative.io/edpresso/what-is-redis
> https://redislabs.com/ebook/part-1-getting-started/chapter-1-getting-to-know-redis/1-2-what-redis-data-structures-look-like/1-2-1-strings-in-redis/

>https://en.wikipedia.org/wiki/Flask_(web_framework)
>https://pythonbasics.org/what-is-flask-python/
>https://www.fullstackpython.com/flask.html
>https://pymbook.readthedocs.io/en/latest/flask.html

>https://www.tornadoweb.org/en/stable/
>https://www.tornadoweb.org/en/stable/guide/intro.html
>https://opensource.com/article/18/6/tornado-framework
>https://www.velotio.com/engineering-blog/python-tornado-guide

>https://kinsta.com/blog/google-cloud-hosting/
>https://en.wikipedia.org/wiki/Google_Cloud_Platform

>https://en.wikipedia.org/wiki/Git
