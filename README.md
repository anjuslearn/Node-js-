

# What is Nodejs 

Node.js is a server side scripting based on Google’s V8 JavaScript engine. It is used to build scalable programs especially web applications that are computationally simple but are frequently accessed. 

# Where can you use it?

In developing I/O intensive web applications like video streaming sites. You can also use it for developing: Real-time web applications, Network applications, General-purpose applications and Distributed systems.

# Why use Node.js?

Node.js makes building scalable network programs easy. Some of its advantages include:
- It is generally fast
- It almost never blocks
- It offers a unified programming language and data type
- Everything is asynchronous 
- It yields great concurrency

# Why is Node.js Single-threaded?

Node.js is single-threaded for async processing. By doing async processing on a single-thread under typical web loads, more performance and scalability can be achieved as opposed to the typical thread-based implementation. 

# Callback in Node.js

A callback function is called at the completion of a given task. This allows other code to be run in the meantime and prevents any blocking.  Being an asynchronous platform, Node.js heavily relies on callback. All APIs of Node are written to support callbacks. 

# What are the functionalities of NPM in Node.js?

NPM (Node package Manager) provides two functionalities:

- Online repository for Node.js packages
- Command line utility for installing packages, version management and dependency management of Node.js packages

# How to install node.js?
1. Go to the site https://nodejs.org/en/download/
2. Double click on the downloaded .msi (32/64 bit)file to start the installation. Click the Run button in the first screen to begin the installation

# Verify that Node.js was Properly installed
1. command in your Command Prompt (regardless of if you're using cmd.exe, Powershell, or any other command prompt)
$ node -v
2. If Node.js was installed fully, the command prompt will print something
$ node -v // The command we ran - prints out the version of Node.js that's currently installed 
v6.9.5 // The printed version of Node.js that's currently installed .


