---
theme: jekyll-theme-midnight
layout: default
---
<a href="https://raniaspant.github.io/">Home</a> <a href="https://raniaspant.github.io/about/">About me</a>
Google
{% include button.html url="http://www.google.com" %}

<a class="button button-linkedin" style="background: #0074A1;" href="https://www.linkedin.com/in/rania-spantidi-670a4095/" target="_blank"><svg class="icon" viewBox="0 0 24 28">
<path d="M5.453 9.766v15.484h-5.156v-15.484h5.156zM5.781 4.984c0.016 1.484-1.109 2.672-2.906 2.672v0h-0.031c-1.734 0-2.844-1.188-2.844-2.672 0-1.516 1.156-2.672 2.906-2.672 1.766 0 2.859 1.156 2.875 2.672zM24 16.375v8.875h-5.141v-8.281c0-2.078-0.75-3.5-2.609-3.5-1.422 0-2.266 0.953-2.641 1.875-0.125 0.344-0.172 0.797-0.172 1.266v8.641h-5.141c0.063-14.031 0-15.484 0-15.484h5.141v2.25h-0.031c0.672-1.062 1.891-2.609 4.672-2.609 3.391 0 5.922 2.219 5.922 6.969z"></path>
</svg></a>

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

