---
theme: jekyll-theme-midnight
layout: default
---
<a href="https://raniaspant.github.io/">Home</a> <a href="https://raniaspant.github.io/about/">About me</a>
Google
{% include button.html url="http://www.google.com" %}

I've been programming for several years now, hence I have lots of projects and small ideas to showcase. My interests tend to shift from 
one programming language to another every now and then. 

## [](#header-2)C

* ### [](#header-3)[Board simulation using pipes](https://github.com/raniaspant/BoardSimulation)
_This was a project that I developed for my Unix Systems Programming class (undergraduate studies). Usage of fork/exec for processes, communication between them with pipes/named-pipes, low level I/O, signal management, bash script creation. All of these in combination of custom data structures and dynamic memory management._

Two entities: board client and board server. The server remains active throughout the procedure. The client(s) post on the board on different channels (provided by the server). Server and clients communicate through named pipes. There was also a bash script created to gather statistics about this whole project running (how many boards are running, how many are inactive etc).

Developed in Linux, Ubuntu, using gedit and terminal.

* ### [](#header-3)[Bank server-client using threads](https://github.com/raniaspant/ServerClient)
_Again, project developed for the same class. Usage of sockets and multithreading techniques, thread pool._

Two entities: bank server and bank client. Bank server keeps a hash table that contains a list in every bucket and keeps 1 mutex per 5 positions to maintain synchronization and avoid deadlocks. Size of the table is defined as 50, all of the mutex values are kept in an integer matrix which later gets sorted.

The server waits for an incoming connection using a select to avoid busy waiting. There are also 2 more scripts, one for the worker thread, and one for placing/obtaining/initializing functions of the request thread pool, as well as functions about the hash table structure.

Developed in Linux, Ubuntu, using gedit and terminal.

