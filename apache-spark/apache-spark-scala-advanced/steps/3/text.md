Step 4: Let us now look at pattern matching. Pattern matching is, as said before, a core feature in Scala. Pattern matching is similar to that of switch in other languages.

Enter into the paste mode and execute the following code.

scala> :paste
//Entering paste mode (ctrl-D to finish)

val job = “Transponster”

job match {
case “Masseuse” => println(“That’s Phoebe”)
case “Chef” => println(“That’s Monica”)
case “Executive” => println(“That’s Rachel”)
case “Transponster” => println(“That’s Chandler”)
case “Actor” => println (“That’s Joey”)
case “Paleontologist” => println(“That’s Ross”)
case _ => println(“Unknown job role”)
}



 

In the code above, we have created a new variable called job which has a value of Transponster. We then use the match keyword to match the job variable with a list of cases. As you can see from the screenshot, the value of job is correctly matched and the output is printed. The last case statement which has an underscore (_) is a wild card operator. It is used so that, if none of the cases match, the default case is executed in the loop. Also, notice that there are no break clauses in Scala, similar to that of Java. Scala has in-built fall through mechanisms and so there are no break statements required.

Task 4 is complete!
