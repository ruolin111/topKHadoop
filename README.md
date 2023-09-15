# Please add your team members' names here. 

## Team members' names 

1. Student Name: Ruolin Dong

   Student UT EID: rd32966

##  Course Name: CS378 - Cloud Computing 

##  Unique Number: 53030
    


## Task 1 - Top-10 Words in Book-Tiny.txt

````
the	13851
of	6638
and	6000
a	4549
to	4529
in	3904
that	2692
his	2428
I	1723
with	1695
````

## Task 2 - Generate a sorted list of all the word counts in Book-Tiny.txt

Output file: output.txt


# Project Template

# Running on Laptop     ####

Prerequisite:

- Maven 3

- JDK 1.6 or higher

- (If working with eclipse) Eclipse with m2eclipse plugin installed


The java main class is:

edu.cs.utexas.HadoopEx.WordCountTopKDriver 

Input file:  Book-Tiny.txt  

Specify your own Output directory like 

# Running:




## Create a JAR Using Maven 

To compile the project and create a single jar file with all dependencies: 
	
```	mvn clean package ```



## Run your application
Inside your shell with Hadoop

Running as Java Application:

```java -jar target/MapReduce-WordCount-example-0.1-SNAPSHOT-jar-with-dependencies.jar SOME-Text-Fiel.txt  intermediatefolder  output  ``` 

For example 
```java -jar target/MapReduce-WordCount-example-0.1-SNAPSHOT-jar-with-dependencies.jar 20-news-same-line.txt  intermediatefolder  output  ``` 

Or has hadoop application

```hadoop jar your-hadoop-application.jar edu.cs.utexas.HadoopEx.WordCountTopKDriver arg0 arg1 arg2 ```



## Create a single JAR File from eclipse



Create a single gar file with eclipse 

*  File export -> export  -> export as binary ->  "Extract generated libraries into generated JAR"
