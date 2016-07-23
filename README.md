Articles
=========
This is a place for me to collect and collate interesting articles related to distributed systems, algorithms, tooling, etc.

1. [Docker and Jenkins : Data that persists](http://engineering.riotgames.com/news/docker-jenkins-data-persists)
2. [BigArray Tutorial](http://bulldog2011.github.io/blog/2013/01/24/big-array-tutorial/)
3. [Why are projects always behind schedule?](http://priceonomics.com/why-are-projects-always-behind-schedule/)
4. [Don't call yourself a programmer](http://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/)
5. [Big Company vs Startup Comp](http://danluu.com/startup-tradeoffs/)
6. [Ken Thompson - Reflections on trusting trust](https://www.ece.cmu.edu/~ganger/712.fall02/papers/p761-thompson.pdf)
7. [10 Things Bitly forgot to Monitor](http://word.bitly.com/post/74839060954/ten-things-to-monitor)
8. [High Scalability - All time favourites](http://highscalability.com/all-time-favorites/)
9. [10 Practical Docker Tips](http://www.smartjava.org/content/10-practical-docker-tips-day-day-docker-usage)
10. [Haskell Game Server - Part 1](http://mojobojo.com/posts/2015-12-26-haskell-game-server-part-1.html)
11. [Haskell Game Server - Part 2](http://mojobojo.com/posts/2016-01-01-haskell-game-server-part-2.html)
11. [Let's build a web server](http://ruslanspivak.com/lsbaws-part1/)
12. [Starting a tech startup with c++](https://medium.com/@jamesperry/starting-a-tech-startup-with-c-6b5d5856e6de#.tk2wgvi7b)
13. [Who builds a house without drawing blueprints](http://cacm.acm.org/magazines/2015/4/184705-who-builds-a-house-without-drawing-blueprints/fulltext)
14. [Testing SQL Lite](https://www.sqlite.org/testing.html)
15. [Project Oberon - the making oi a computer from grounds up](http://www.projectoberon.com/home)
16. [Files are hard](http://danluu.com/file-consistency/)
17. [Tinystat](https://github.com/codahale/tinystat)
18. [How To Remove Duplicates In A Large Dataset Reducing Memory Requirements By 99%](http://highscalability.com/blog/2016/4/4/how-to-remove-duplicates-in-a-large-dataset-reducing-memory.html)
19. [Big Data Counting: How To Count A Billion Distinct Objects Using Only 1.5KB Of Memory](http://highscalability.com/blog/2012/4/5/big-data-counting-how-to-count-a-billion-distinct-objects-us.html)
20. [When Should Approximate Query Processing Be Used?](http://highscalability.com/blog/2016/2/25/when-should-approximate-query-processing-be-used.html)
21. [Understanding Distributed Analytics Databases, Part 1: Query Strategies](https://www.periscopedata.com/blog/understanding-distributed-analytics-databases-part-1-query-strategies.html)
22. [Microservice Implementation withh Docker](https://dzone.com/articles/microservice-architecture-with-spring-cloud-and-do?edition=179567&utm_source=Spotlight&utm_medium=email&utm_content=queue&utm_campaign=java%202016-06-07)
23. [Golang Web Development](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
24. [BGP spoofing](http://www.zdnet.com/article/bgp-spoofing-why-nothing-on-the-internet-is-actually-secure/)

#### Blogs

1. [Chris Stucchio](https://www.chrisstucchio.com/publications.html)
2. [Thomas Watson - github](https://github.com/watson)
3. [Make Printers Great Again - Thomas Watson](https://www.youtube.com/watch?v=58Ti8w1yX2w)
4. [Dr. Gleb Bahmutov, PhD](https://glebbahmutov.com/)
5. [RabbitMq- with Java](http://stackoverflow.com/questions/22901822/when-using-rabbitmq-as-a-java-work-queue-how-should-you-handle-concurrency-and)
6. [Stavros Stuff](https://www.stavros.io/posts/emergency-food-button/)
7. [Programming blogs every programmer must read](http://danluu.com/programming-blogs/)
8. [marc-andreessen](http://fourhourworkweek.com/2016/05/29/marc-andreessen/)
9. [Being privacy aware](https://vox.space/blog/89/being-privacy-aware-in-2016)

###Build Stacks

1. [Medium Architecture Stack](https://medium.com/medium-eng/the-stack-that-helped-medium-drive-2-6-millennia-of-reading-time-e56801f7c492#.iskk3ub9o)
2. [Service Architectures at Scale: Lessons from Google and eBay](http://www.infoq.com/presentations/service-arch-scale-google-ebay)
3. [Kubernetes](http://kubernetes.io/)
4. [Debug Linux Software](http://www.linuxuser.co.uk/tutorials/debug-your-own-linux-software-like-a-pro)



## Distributed Systems ##
* [Apache Kafka, Samza, and the Unix Philosophy of Distributed Data](http://www.confluent.io/blog/apache-kafka-samza-and-the-unix-philosophy-of-distributed-data) by [Martin Kleppmann](https://twitter.com/martinkl) - a very good introduction to the [Samza](https://samza.apache.org/)/[Kafka](https://kafka.apache.org/) approach to stream processing with particular attention to how this approach relates to the Unix philosophy of small, stand-alone, interchangable tools.  
* [Personalized Recommendations at Etsy](https://codeascraft.com/2014/11/17/personalized-recommendations-at-etsy/) by [Robert Hall](https://codeascraft.com/author/rhall/) of [Esty](https://www.etsy.com/).  Excellent post that summarizes in reasonable detail the approach that Etsy takes in generating recommendations from products to its customers.  This post complements [Conjecture](https://github.com/etsy/Conjecture), Etsy's framework for these recommendations. Strongly suggested for those interested in learning about recommender systems or applied linear algebra.
* [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) by [Tyler Akidau](http://twitter.com/takidau). A medium length introduction the fundamental concepts of stream processing by one of the authors of Google's in-house solution, [MillWheel](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/41378.pdf).  This is an excellent introduction for those completely new to stream processing. The two biggest take-aways are that stream processing systems that do not provide a consistent view of the data should not be trusted and that for time-based computation, event-time windows, while the most difficult to achieve, are the only approach worth pursuing.

##Performance##
* [You're probably wrong about caching](http://msol.io/blog/tech/youre-probably-wrong-about-caching/) by [Mike Solomon](https://twitter.com/msol).  Good summary of potential downsides of using caching to increase system performance.

###Resources

-  [Riot Games Engineering Blog](http://engineering.riotgames.com/)
-  [Building simple and elegant programming abstractions](http://bulldog2011.github.io/)
-  [Free Programming resources](https://medium.com/free-stuff/2000-programming-resources-c2c835001216#.cbbi68vuw)
-  [Spring-webapp sample](https://github.com/making?tab=repositories)
