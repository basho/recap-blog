---
title: Riak Recap for February 11 - 26
layout: newpost
summary:
---

Greetings and salutations.

We're now making the Riak recap a team effort for the Basho technical
evangelists, so expect to see a little more content. This latest is
particularly long due to the release of 1.3 and a two week gap since
our last note.

John

http://twitter.com/macintux

## Riak 1.3 was released!

* Basho's announcement ---> http://basho.com/introducing-riak-1-3/
* GigaOM's coverage ---> http://gigaom.com/2013/02/21/basho-technologies-takes-aim-at-more-enterprises-with-upgrades/
* The Register's coverage ---> http://www.theregister.co.uk/2013/02/23/basho_gives_riak_greater_data_reliability/

Chris Tilt describes the new multi-datacenter replication in 1.3 with Riak Enterprise

* ---> http://basho.com/advanced-mode-now-available-for-riak-enterprises-multi-datacenter-replication/

Joseph Blomstedt expands on The Register's description of the new Active Anti-Entropy (AAE) functionality

* ---> http://forums.theregister.co.uk/forum/1/2013/02/23/basho_gives_riak_greater_data_reliability/#c_1741034


## Other news

1) Matt Anderson has several blog posts on Riak and has created a Riak protobuf client in C++

* Blog here ---> http://z-dev.org/thoughts/
* Client here ---> https://github.com/andersonmat/riakcpp

2) Basho head tech evangelist Mark Phillips will be speaking at Data Day Texas on Saturday March 30th, in Austin

* List of speakers ---> http://datadaytexas.com/speakers

3) Steve Willcock has created NodeJS tools for JSON documents in Riak

* Packages here ---> https://npmjs.org/~stevewillcock

4) Basho engineer Richard Shaw added to the Riak docs a list of metrics useful for monitoring purposes

http://docs.basho.com/riak/latest/cookbooks/Statistics-and-Monitoring/#Riak-Metrics-To-Graph

5) Dr. Margo Seltzer, Oracle architect and developer of Berkeley DB/founder of SleepyCat will keynote RICON East

* RICON blog entry here ---> http://ricon.io/blog/2013-02-13-margo-seltzer-keynote.html

6) Github has made available their Puppet module for Riak for new Mac workstations

* Project here ---> https://github.com/boxen/puppet-riak

7) Hilary Mason, Chief Scientist at Bitly, will be speaking at RICON East

* RICON blog entry here ---> http://ricon.io/blog/2013-02-19-hilary-mason.html

8) Basho technical evangelist Pavan Venkatesh gave a talk on Riak at Apollo Group

* Slides here ---> https://speakerdeck.com/pavankv/riak-usage-at-apollo-group

9) Dan Revel created notes on installing Riak under MacOS X

* Blog here ---> http://nopolabs.com/2013/02/installing-riak-1-2-1-on-mac-osx-10-7/

10) Andrew Nelson has created a simple Perl interface to Riak

* Project here ---> https://github.com/holophrastic/data-riak
* MetaCPAN entry by Florian Ragwitz here ---> https://metacpan.org/release/FLORA/Data-Riak-1.9/

11) Alexey Gordeyev has created a multi-database ORM for NodeJS that supports several NoSQL databases, including Riak

* Site here ---> http://www.camintejs.com/

12) The ClojureWerkz team has release v1.4.0 of Welle, their Clojure client for Riak

* Blog entry here ---> http://blog.clojurewerkz.org/blog/2013/02/21/welle-1-dot-4-0-is-released/

13) Basho overachiever Tyler Hannan has created a Vagrant setup for a Riak cluster under Ubuntu

* Github project here ---> https://github.com/tylerhannan/vagrant-riak-cluster

14) Basho engineer Simon Vans-Colina has created a simple way to fire up a 5-node Riak cluster on a MacOS X machine

* Github project here ---> https://github.com/simonvc/riak-dev-cluster

15) Versu.com thanked the Erlang community for the great tools (including Riak) and support that enabled them to roll out a new iPad game

* Post to erlang-questions ---> http://erlang.org/pipermail/erlang-questions/2013-February/072500.html

16) Engine Yard technologist and RICON veteran Ines Sombra will talk about Riak at POSSCON

* Talk description ---> http://posscon.org/presentation/getting-started-riak-cloud/

17) Unison Technologies opened some of the custom tools they use with Riak

* Github project ---> https://github.com/unisontech/uriak_pool

18) Basho engineer Eric Redmond talked at SCALE about data management with Riak

* Overview and slides ---> http://www.socallinuxexpo.org/scale11x/presentations/distributed-data-management-riak

19) Hibernum uses Riak for social gaming

* Basho blog post ---> http://basho.com/hibernum-selects-riak-for-user-data-storage/

20) The inaugural Twin Cities Riak meetup was announced for March 5th

* Meetup.com announcement ---> http://www.meetup.com/Twin-Cities-Riak-Meetup/events/106353292/

21) Basho engineer Ryan Zezeski's new blog began with a discussion of the performance and behavior implications of disabling Solr's "stale check" for its connection pools

* Blog post ---> http://www.zinascii.com/2013/solr-distributed-search-and-the-stale-check.html

22) Various Q and A

* ---> http://stackoverflow.com/questions/14991708/jackson-annotation-or-method-to-url-encode-decode-during-serialization
* ---> http://stackoverflow.com/questions/14845506/riak-couchdb-and-mongodb-comparison-for-concurrent-inserts-not-update
* ---> http://stackoverflow.com/questions/14854208/activity-feed-with-riak
* ---> http://stackoverflow.com/questions/14910294/do-i-need-riak-to-run-hallway-singly
* ---> http://stackoverflow.com/questions/14886046/riak-java-cannot-deserialize-domain-objects-from-mapreduce-query-in-scala
