Hadoop-WordCountDemo
====================

Sample project which I use as a template for making Hadoop jars

Building
--------

mvn assembly:assembly

Running
-------

hadoop jar target/WordCountDemo-1.0-SNAPSHOT-job.jar ./test/input.txt ./test/output-`date +%s`/