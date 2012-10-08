Hadoop-WordCountDemo
====================

Sample project which I use as a template for making Hadoop jars.  Derived from http://exported.wordpress.com/2010/01/30/building-hadoop-job-jar-with-maven/

Building
--------

```bash
mvn assembly:assembly
```

Running
-------

```bash
hadoop jar target/WordCountDemo-1.0-SNAPSHOT-job.jar ./test/input.txt ./test/output-`date +%s`/
```