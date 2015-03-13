Introduction
============

The GMX/V standard defines a standard way to count words and characters within a document and a standard XML format to share this data between applications.

Open sourced by Gould Tech Solutions, part of thebigword Group.

Library
=======

The code constitutes a reference implementation of the GMX/V standard, complete with unit tests, written in C#. It is useful for programmers who use the .Net platform and wish to integrate GMX/V into their products.

Console Application
===================

A Windows application is available in the downloads section which allows you to retrieve a word count from a given XLIFF document by entering a command line, e.g.:

WordCount.exe my_xliff_file.xlf > C:\gmxv.xml