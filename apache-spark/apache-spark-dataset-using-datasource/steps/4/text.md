
**Step 2:** Open IDE, right-click the training package which you have created in previous exercise and hover over New and then click on Scala Class. When prompted, enter createDS as the name and click on the dropdown for Kind and select Object. Enter the import as shown below.

```
import org.apache.spark.sql.SparkSession
```

Next, we need to write a case class so that we can specify the schema for our fields. This case class is what it makes a Dataset and differentiates from DataFrame. While loading the file, we simply refer to this case class object to create a dataset.

```
private case class Movies(userId: Int, movieId: Int, rating: Double, timestamp: String)
```

We have created a case class and named it Movies by specifying the fields and its types.


If there is an error saying that the case class Movies is already defined, change the name of class case to anything else and refer to it accordingly throughout the program.

**Step 3:** Now, write the main function and create the SparkSession object as shown below.

```
def main(args: Array[String]): Unit = {

  val spark = SparkSession
    .builder()
    .appName("Creating a Dataset")
    .master("local[*]")
    .getOrCreate()
```

 
