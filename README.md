# Hadoop-WordCount
This is a simple word count app. 
Run under Hadoop 2.7.1
Read the source database which we use 50 wiki page here. Then count the follow four words : "education", "politics", "sports", "agriculture" appear times.

While using in hadoop ec2 , the command code seems like:

hadoop fs -mkdir /data

hadoop fs -put states/ /data

hadoop jar WordCount.jar WordCount /data/states /test/wordcountout3

hadoop fs -ls /test/wordcountout3
