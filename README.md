# AppInsightPub
Creating a management tool for your network VM's using NodeJS and Microsoft SQL Server

Overview: This repository is to demonstrate the processes I went through to solve an epidemic level crisis of envrionment fragmentation hell I solved at my current company.  To give a high level outlook of our environment it was as follows.  Our public facing server, was attached to 2 independant archive servers.  Those archive servers were handling over 60 customers, those customers were then serviced using desktop applications spread out over 20+ virtual machine Windows environments.  Each customer had at least 2 desktop applications, several had upwards of 30 applications running on various virtual machines. What this led to was a drain on resources when trying to find the issue with 1 customer's data on say "virtualPC-13" because it may have been put into our raw data by an application on one of 6 pc's.  one of 100 desktop applications, then consumed that data from 1 of 100 different applications on different service pc's.  The project goal was 2 parts.  One, to change the operational procedure from logging into each database to run 1 off queries and procedures. Two, to create a centralized web-accessible management view for the applications and an admin-dashboard like interface for better transparency into the scattered apps.

This Readme assumes you already have an understanding of Javascript, HTML5, and terminal or command line.
*I highly recommend you install cyg-win into your command line if you're using windows.

To get started, install Node.  If you don't yet have node, you can download it here: <a href="https://nodejs.org/download/">NodeJS</a>
Once the installation has completed, you can type: 
<code> Node -v </code> into terminal/command line, a corresponding version when type in lets you know that you have node installed.  You can also type: <code> npm -v </code> a version response here lets you know that you also have "Node Package Manager" We'll be using this to install all of the relevant packages for this project.
