---
title: "ManTech Summer Internship"
categories:
  - Industry Experience
tags:
  - Software
  - Design
  - Resume
---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Spending a summer in San Antonio with ManTech International was a great experience, helping me refocus how I think about software design
and the cybersecurity sector as a whole. Although the project I worked did not directly involve Computer Network Operations (CNO), my discussions with coworkers and some
small lectures on interesting aspects of software and operating system security pushed me to realized the vast amount of engineering debt related to security, especially with the proliferation of network connected embedded systems.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Although my project group was focused on offensive cyber operations, their responsibilities still required reverse engineering of complicated binaries with no source code. Analyzing binaries without any knowledge of the functionality or objective can be incredibly difficult, even with the advanced state of disassemblers and de-compilers available. Our goal of automating some attribution of unknown binaries is not to give the final say on the author or goal of a program, but to give context for further analysis.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the rapidly evolving state of binary obfuscation, there is no definitive answer on how to quantify *similar* binaries. Our team of two focused on creating an extensible framework to accommodate a variety of tools. The six week effort resulted in a number of analysis tools recording results to a PostgreSQL database through a Python helper module. This module handled schema creation with user created JSON files and handled client-server communications. This module standardizes the method of communication between new analyzers and the central database allowing for simple expansion.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Concluding the six week period, we were generating meaningful results from comparisons of programs cyclomatic complexity, call graph similarity, import tables, and [yara](http://virustotal.github.io/yara/) rules.
