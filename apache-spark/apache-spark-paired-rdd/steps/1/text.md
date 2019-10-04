Let's first setup VScode editor and clone respository. Clone the following repository by executing following command in the terminal.
`git clone https://github.com/athertahir/apache-spark.git`{{execute}}

Now, move in the directory which contains the source code.

`cd apache-spark/`{{execute}}


**Note:**
- The supplied commands in the next steps MUST be run from your `apache-spark` directory. 
- Final code was already cloned from github for this scenario. You can just understand the application code in the next steps and run it using the instructions.
- Click **IDE Editor** tab to open Visual Studio and open solution explorer and open `apache-spark/src/main/scala/training/avgRatings.scala` to view scala file.

![](https://github.com/fenago/katacoda-scenarios/raw/master/apache-spark/1.JPG)


The aim of the following lab exercises is to start writing Spark code in Intellij to learn about Paired RDDs.
We will cover following topics in this scenario.
- Creating a Tuple
- Creating a Paired RDD
- Performing Operations on Paired RDD

We need the following packages to perform the lab exercise: 
- Java Development Kit
- Scala
- Spark
