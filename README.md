# [Java_SE_Course]
Project to review Java and learn new features.

---
# What is Java?

Java is a high level programming language (although not as high as Python or JavaScript) that helps us build applications for different devices and operating systems.

It was created in 1991 by James Gosling while working at Sun Microsystems, a company that was later acquired by Oracle. This means that Java has very good maintenance, but also some changes that we will not all agree with.

Java has two categories: Standard Edition for building desktop or console applications and Enterprise Edition for companies to work with the latest web applications.

In this course we will learn the basics of Java Standard Edition: language syntax, declare variables, work with functions, cycles and conditionals, programming logic, algorithms and many other things.

But do not worry. Java follows the philosophy of Write Once, Run Anywhere (WORA), so everything you read in this document can also be applied with Java EE.

---
# Java and JDK versions
The JDK or Java Development Kit consists of the following elements:

Java Runtime Environment (JRE): The Java virtual machine, which allows us to write the same code to work the same on all devices and operating systems.
Java compiler: Responsible for translating our code in Java into a language that can understand and interpret our virtual machine.
Development APIs: A code base ready to help us develop.
Java development APIs have evolved over time, so there are different versions of java that you can use. The version that most raised the popularity and job offers with Java was Java SE 6.

In Java SE 9 they announced that updates would occur every 6 months, but LTS (Long Time Support) versions will be maintained for 3 years, so updates are necessary, but not urgent.

In this course we are going to work with the Java SE 11 LTS version, the first licensed version of Java. We can only use it for free when working in development and testing environments. Otherwise, we must pay USD 2.5 per month per desktop user and USD 25 per processor for server applications.

Fortunately, OpenJDK is a free and open source version of using Java SE Platform Edition.

---
# The most used Java tools
Java 8 (LTS) is the most used version of Java until the beginning of 2019, but it will only have support until December 2020, after this date we will have to pay a license to continue with its support.

Java 10 introduced some changes in the way of declaring variables, so in this course we will work with Java versions 8 and 11.

The most used tool to build web projects with Java is Maven, but there are also other alternatives such as Gradle. There are also frameworks like Spring to work with Java EE and ORMs like Hibernate to work with databases.

IDEs are integrated development environments, tools (applications, surely desktop) that help us write our code with editors, compilers, debuggers and graphic interface builders, all in one place.

The IDE recommended by Oracle is NetBeans, but there are also Eclipse and IntelliJ IDEA, the latter is the one that has taken the most strength thanks to Kotlin. All three tools are free, but IntelliJ IDEA also has a paid version.

---
# Creating a development environment in Java
* https://adoptopenjdk.net

---
# First Hello World in Java
Java files use the .java extension. Therefore, to create our first “Hello, world” we can do it from a HolaMundo.java file.

The main method is the entry point of an application in different languages such as Java, Kotlin and C ++. Without this method our application will not run and will show an error.

In Java we define this method as follows:
```java
public static void main (String[] args) {
  // acciones
}
```

Therefore, this will be the code of our HolaMundo.java and we can execute it with 
* Right Click> Run 'HelloWorld.main ()':

```java
public class HolaMundo {
  public static void main (String[] args) {
    System.out.println("Hola, mundo!");
  }
}
```

Remember that our IDE provides us with some shortcuts. For example, just by writing the word sout we can autocomplete the statement System.out.println () ;.
