# Linux/Hadoop

## QC Agenda
- Linux
  - Open Source
  - CLI
  - Root[/] vs Home[~] directory
  - Commands: mkdir, rm, cp, mv, cd, ls, cat, grep, echo
  - Commands: df, fdisk, sfdisk, cfdisk, lsblk, blkid, mdadm
  - Commands: find, history, ps, kill ,sed, nohup
  - File Editors: vim, nano
  - Search and Replace commands
  - SSH: credentials/private key
- Hadoop
  - Evolution of Big Data
  - Hadoop Ecosystem
  - Intro to HDFS
  - HDFS commands
  - MapReduce
  - Mapper/Intermediate/Reducer phases
  - Partitioners
  - Combiners
  - YARN
  - InputFormats
  
## Resources
### Books
- [Conquering the Command Line](http://conqueringthecommandline.com/book/basics)
- [Linux-Training](http://linux-training.be/index.php?nav=home)
- [TLDP Advanced Bash-Scripting Guide](http://tldp.org/LDP/abs/html/abs-guide.html)

## Documentation
- [The Linux Documentation Project](https://www.tldp.org/)
- [Linux man-pages](https://www.kernel.org/doc/man-pages/)
- [Bash Manual](https://www.gnu.org/software/bash/manual/)
- [GNU Coreutils Manual](https://www.gnu.org/software/coreutils/manual/coreutils.html)
- [The Linux kernel user's and administrator's guide](https://www.kernel.org/doc/html/latest/admin-guide/index.html#)

### Tutorials
- [Linux Journey](https://linuxjourney.com/)
- [Commandline Challenge](https://cmdchallenge.com/)
- [cheat.sh - cli cheatsheets](http://cheat.sh/)
- [explainshell](https://explainshell.com/)
- [ShellCheck](https://www.shellcheck.net/)

## Review
- What is Unix?
- What is Linux?
- What are Linux pipelines?
- What distribution of Linux are you familiar with? Which distributions are in the same family?
- What is a shell? Which shell are you familiar with?
- What is shell scripting?
- What is a package manager? Which one is used on RHEL?
- What is grep? man?
- Explain basic Unix commands for file creation and directory navigation.
- Where is the home directory located? Where is root?
- How is the Linux filesystem structured and organized? What are some important directories?
- What is vim? Nano?
- How do I change file permissions?
- How do I create local and global environment variables?
- What utilities can help you monitor a system's processes? It's filesystem?
- What is ssh? How can you use it to connect to a Linux system?
- What is a private and public key?
- What was the "Hadoop Explosion"?
- What about CDH?
- What are some differences between hard disk space and RAM?
- What is a VM? (short)
- What is AWS? (short)
- What is/was Unix?  Why is Ubuntu a Unix-like operating system?
- Know basic file manipulation and navigation commands in Unix:
  - ls -al
  - cd
  - pwd
  - mkdir
  - touch
  - nano
  - man
  - less
  - cat
  - mv
  - cp
  - rm
  - history
- What's the difference between an absolute and a relative path?
- How do permissions work in Unix?
- What are users, what are groups?
- How does the chmod command change file permissions?
- What is a package manager? what package manager do we have on Ubuntu?
- What is ssh?

- Be able to explain the significance of Mapper[LongWritable, Text, Text, IntWritable] and Reducer[Text, IntWritable, Text, IntWritable]
- What needs to be true about the types contained in the above generics?
- What are the 3 Vs of big data?
- What are some examples of structured data?  Unstructured data?
- What is a daemon?
- What is data locality and why is it important?
- How many blocks will a 200MB file be stored in in HDFS, if we assume default HDFS block size for Hadoop v2+?
- What is the default number of replications for each block?
- How are these replications typically distributed across the cluster?  What is *rack awareness*?
- What is the job of the NameNode? What about the DataNode?
- How many NameNodes exist on a cluster?
- How are DataNodes fault tolerant?
- How does a Standby NameNode make the NameNode fault tolerant?
- What purpose does a Secondary NameNode serve?
- How might we scale a HDFS cluster past a few thousand machines?
- In a typical Hadoop cluster, what's the relationship between HDFS data nodes and YARN node managers?

- When does the combine phase run, and where does each combine task run?
- Know the input and output of the shuffle + sort phase.
- What does the NodeManager do?
- What about the ResourceManager?
  - Which responsibilities does the Scheduler have?
  - What about the ApplicationsManager?
- What is an ApplicationMaster?  How many of them are there per job?
- What is a Container in YARN?
- How do we interact with the distributed filesystem?
- What do the following commands do?
  - hdfs dfs -get /user/adam/myfile ~
  - hdfs dfs -put ~/coolfile /user/adam/
