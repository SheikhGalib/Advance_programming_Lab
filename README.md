**Executive Summary**

This document provides a detailed overview of the initial phase of our Java and Android Programming lab, where we focused on setting up the Java development environment and understanding the basic concepts of the language. The goal of this lab was to establish the foundation required for future software development projects, especially in Android, by ensuring that all tools and dependencies are properly configured and the team is aligned with Java’s core principles. Furthermore, this lab clarified the transition from C/C++ to Java, highlighting important differences and key advantages of Java in modern application development.

**Tools and Setup**

To begin working with Java, we first had to set up the development environment. The tools and steps involved were as follows:

**Java Development Kit (JDK**): We learned how to download and install the JDK, which provides the essential tools for compiling and running Java programs.

First going to this website we downloaded the **JAVA JDK.** Then installed in our machines. **[https://www.oracle.com/java/technologies/downloads/#jdk23-windows**](https://www.oracle.com/java/technologies/downloads/%23jdk23-windows)**
![Aspose Words f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa 001](https://github.com/user-attachments/assets/d88795e7-2507-490b-b0ff-77a2843d01f2)


**![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.001.png)**

` `**VS Code Installation:** Though several IDEs like Eclipse or IntelliJ IDEA are popular, we were taught how to set up Visual Studio Code (VS Code) as a lightweight yet powerful editor for Java development.
First going to this website we downloaded the respective version of VS Code for our machine.
<https://code.visualstudio.com/Download>

![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.002.png)

We made sure to mark all the check box, this shall come in handy later.
![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.003.png) 

After downloading and installation. We did some changes to it.
**Optional:** I did some preference changes for ease of work. Goto **settings >** in the search option, search for auto save. Then change it to **afterDealy** and set **Auto Save Delay** to 700. 
(Can’t find setting, use this shortcut. **Ctrl + ,** )

**Java Development Extension in VS Code:** To enable Java programming in VS Code, we installed the Java extension pack, which includes tools for syntax highlighting, debugging, and project management.

First going to extensions. (just use **ctrl+shift+x**), then installed.
**Code runner**, **Extension Pack for Java, Java, Debugger for Java, Test Runner for Java, Gradle for Java, Maven for Java, Project Manager for Java.**

![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.004.png)

After Installation of Vs code and Java JDK we run some code to test If the system is running the code or not.
**Optional:** For some users there might be some error in running the java code. If there is this problem. After running this command “**java  --version**” in the terminal. Then we need to update our environment variable. ![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.005.png)









Updating the environment variable. (optional)

|Step-1![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.006.png)|<p>Step-2</p><p>![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.007.png)</p>|
| :- | :- |
|<p>Step-3</p><p>![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.008.png)</p>|<p>Step-4</p><p>![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.009.png)</p>|

Step-5

![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.010.png)

Open cmd and run “**java --version”**  This shall give this output 
![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.011.png)

Then we are good to go.


**Running the code:**
We open a folder in Vs code and named our program **Main.java**. It is important to note that Java is case sensitive. We went to this website to learn and practice some coding of Java.
<https://www.w3schools.com/java/default.asp>

![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.012.png)

Output:
![](Aspose.Words.f4a56bbb-2d1d-4103-bf2e-5d6ca311aefa.013.png)

**Transitioning from C and C++ to Java**

Given that we already had prior experience with C and C++ and Object-Oriented Programming (OOP) concepts in C++, the focus was on understanding how Java differs from these languages. Some of the key differences discussed were:

- **Memory Management:** Unlike C and C++, where developers are responsible for manually managing memory (using malloc, free, etc.), Java features automatic garbage collection, which simplifies memory handling.
- **Syntax Differences:** Though similar in some ways, Java eliminates certain complexities of C and C++. For instance:
  - Java does not use pointers, which are a core part of C/C++.
  - All Java code must reside within a class.
  - Java has a unified exception-handling mechanism, which helps avoid crashes caused by unchecked errors.
- **Portability:** One of Java's primary strengths is its portability, enabled by the Java Virtual Machine (JVM). Unlike C/C++, which compiles directly into machine code, Java compiles into bytecode, making it platform-independent.
- **Object-Oriented Features:** Java is fully object-oriented, whereas C++ is only partially so. In Java, every piece of code belongs to a class, and even primitive types have wrapper classes that enable them to behave like objects.

**Benefits of Java for Android Development**

This lab reinforced the reasons for choosing Java as the primary language for Android development:

- **Strong Ecosystem:** Java has a well-established ecosystem with extensive libraries and frameworks, including the Android SDK.
- **Cross-Platform Compatibility:** Java’s "write once, run anywhere" philosophy aligns perfectly with Android’s requirement for applications to work on various devices.
- **Community Support:** Java benefits from a large and active developer community, ensuring ample resources for problem-solving and learning.


**Conclusion**

This lab was an essential starting point for our journey into Java and Android programming. By setting up the development environment and understanding the key differences between Java, C, and C++, we are now better equipped to start developing Java-based applications. These foundational skills will be invaluable as we progress toward building more complex Android projects.

In the upcoming labs, we will continue to delve deeper into Java, explore advanced concepts, and eventually focus on Android-specific development.


