# awesome-bookmarks
bookmarks about different subjects : infrastructure, machine-learning, etc.

## Benchmarks

[Elastic](https://benchmarks.elastic.co/index.html)

---

[PHP benchmarks](http://www.phpbenchmarks.com/fr/)

* Use Apache Bench & Siege
* Compares PHP version
* Compares popular HTTP frameworks
* Compare popular templating frameworks


## Cheatsheets

[List of cheatsheets](https://lzone.de/cheat-sheet/)

---

[Docker](https://devhints.io/docker)

[ECMAScript 6](https://devhints.io/es6)

[Elasticsearch](http://elasticsearch-cheatsheet.jolicode.com/)

[Kubernetes CLI - kubectl](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) Official

[Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[MongoDB](https://www.opentechguides.com/how-to/article/mongodb/118/mongodb-cheatsheat.html)

[MySQL](https://devhints.io/mysql)

[Neo4j - Cypher](https://neo4j.com/docs/cypher-refcard/current/) Official

[PHP - Twig](https://github.com/okeeffed/cheat-sheets/blob/master/twig-cheat-sheet.md)


## Algorithm

### Conjunctions

#### Zig-zag algorithm

[Algorithm](http://www.mathcs.emory.edu/~cheung/Courses/554/Syllabus/4-query-exec/index=zig-zag-join.html)

* Fast conjunction on sorted elements
* Used by Lucene under the name "Leap-frog algorithm" : [Lucene FilteredQuery](https://lucene.apache.org/core/4_2_0/core/org/apache/lucene/search/FilteredQuery.html#LEAP_FROG_FILTER_FIRST_STRATEGY)
* [bbuzz 2015 - Talk from Adrien Grand](https://youtu.be/eQ-rXP-D80U?t=357)

### Sort

#### Theory
* [Selection sort VS Insertion sort - Computerphile ](https://www.youtube.com/watch?v=pcJHkWwjNl4)

#### Implementations
* [Merge sort - PHP source code](https://github.com/php/php-src/blob/master/main/mergesort.c)
* [Insert sort & Quick sort - PHP source code](https://github.com/php/php-src/blob/master/Zend/zend_sort.c)

## Architecture

### CAP theorem

### Chaos Engineering

* [Netflix architecture resiliency - Experimentations on production environment clusters - Medium](https://medium.com/netflix-techblog/chaos-engineering-upgraded-878d341f15fa) 

### CQRS

### CRUD

### Event-loop

### Event-sourcing

### Optimistic models


## Infrastructure

### Deployment process

[Presentation of different deployment : Blue-green, A/B testing, Canary - Christian Posta](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/)

### Kubernetes

#### Storage

[Kubernetes Volumes Guide - Matthew Palmer](https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-volumes-example-nfs-persistent-volume.html)

* Explain differences between the filesystem, k8s volumes, k8s persistent volumes
* Example of an external NFS service 

---

### Memcached

#### Mcrouter

[GitHub](https://github.com/facebook/mcrouter)

[Presentation](https://code.fb.com/core-data/introducing-mcrouter-a-memcached-protocol-router-for-scaling-memcached-deployments/)

### Nginx

#### Configuration

[nginxconfig.io](https://nginxconfig.io/)

* Generate nginx configuration
* Generate HTTPS certificate using Let's encrypt

## Search engines

### Front-end

[Lunr](https://github.com/olivernn/lunr.js)
* ECMAScript 5 implementation
* Fulltext search engine
* In-memory storage
* Can be used by mobile apps

---

[Metis](https://github.com/MKCG/metis)

* ECMAScript 6 implementation
* Fulltext search engine
* Facet engine (filters)
* In-memory storage
* Can be used by mobile apps

## Natural Language Processing

[LASER - Facebook](https://code.fb.com/ai-research/laser-multilingual-sentence-embeddings/)

## Testing

### CI Pipeline

### Functional tests

[PHP - Behat - BDD - Gherkin based framework](http://behat.org/en/latest/)

[PHP - Codeception BDD - User centric based framework](https://codeception.com/)

