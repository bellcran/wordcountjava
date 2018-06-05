# wordcountjava 

1) mvn clean package
   에러발생 : Deleting full .m2/repository local repository
2) eclipse -> File -> open project from file system
3) run as -> Maven Build -> goals : package 입력 후 실행
4) yarn jar wordcountjava-1.0-SNAPSHOT.jar org.apache.hadoop.examples.WordCount /example/data/gutenberg/davinci.txt /example/data/wordcountout
5) hdfs dfs -cat /example/data/wordcountout/*

** result
  zeal    1
  zelus   1
  zenith  2