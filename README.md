# JAR_Reverse_Shell

javac main.java

Create a text file named Manifest.txt with the following content (make sure to include a newline at the end of the file):
Main-Class: main

jar cfm calc.jar Manifest.txt main.class
