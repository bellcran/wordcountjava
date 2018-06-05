# wordcountjava 

1) mvn clean package
2) eclipse -> File -> import -> General -> Existing Project into workspace
3) yarn jar wordcountjava-1.0-SNAPSHOT.jar org.apache.hadoop.examples.WordCount /example/data/gutenberg/davinci.txt /example/data/wordcountout
4) hdfs dfs -cat /example/data/wordcountout/*

** result
  zeal    1
  zelus   1
  zenith  2