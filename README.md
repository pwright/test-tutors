# Teachy-McTeachface

**Change this heading to match your course name**

This repos describes how to use logseq to author tutors.dev courses.

To convert from tutors to logseq, see [pwright/workshop-2024 at logseq]( https://github.com/pwright/workshop-2024/tree/logseq?tab=readme-ov-file#tutors-to-logseq ).

Create tutors.dev content using Logseq

**Prerequisites**

* [Logseq: A privacy-first, open-source knowledge base]( https://logseq.com/ ) 
You can use [Logseq]( https://demo.logseq.com/ ) if you give that website file access.

* [Node.js — How to install Node.js]( https://nodejs.org/en/learn/getting-started/how-to-install-nodejs ) - [nvm]( https://github.com/nvm-sh/nvm ) is an excellent option.

**Procedure**

1. Start Logseq and open the `logseq` folder of this repo as a graph.

2. Make some edits.

3. In the root folder of this repo, create the course using:
   ```bash
   $ python template/logseq.py logseq/ build/ template/
   ```
4. Install tutors html publish using:
   ```bash
   $ npm i -g tutors-html
   ```
5. Create the tutors html using:
   ```bash
   $ cd build
   $ tutors-html
   ```
   The output html files are located in `build/public-site`.



**Reference**

```
$ python template/logseq.py 

usage: logseq.py [-h] source destination template
logseq.py: error: the following arguments are required: source, destination, template
```

