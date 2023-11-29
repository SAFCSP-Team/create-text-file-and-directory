## Create a File

#### Objective

Understand the `File` and `Path` classes in Java, and how to use them to create a file.

#### Concepts

These concepts are the main used concepts in the project solution, kindly read the provided resources if any is new to you.
These concepts have covered `File` and `Path` classes in Java, which are used to create a file.

| Concepts                                          | Resources                                                                                |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Accessing a file/directory                        | [Java Documenation of I/O Classes](https://dev.java/learn/java-io/)                      |
| Understand File, FileReader,and  FileWriter class | [CodeAcademy - File Documenation ](https://www.codecademy.com/resources/docs/java/files) |

#### Problem

Create a file in the project directory.

#### Implementation

Do the implementation in the main method of the `CreateFile` class:

1. Initialize a variable with `Path` data type , and assign it `Paths.get(/* file path*/)`.
2. Call the `createFile()` method from the `Files` class, and then pass the path variable that you just created.

```java
 public static void main(String[] args) throws IOException{
        /* You Code Here */
}
```

#### Note
> * You can use either `Path` or `File` class to create a file, but `Path` class is more recommended by dev.java.
> * You can create a directory by using `Files.createDirectory()` method.