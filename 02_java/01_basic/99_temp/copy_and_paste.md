<a name="topage"></a>

# copy_and_paste

----

* [java]
* 
## `package`
* A package is a "namespace" that organizes a set of related classes and interfaces. (like folder/directory to files)
* `package structure` - is a file structure that organize different files in your program.
* a package make the program code classified into different unit of code (subjects).
   * example: utilities, hr(human resource), sales, java_core, etc
 
#### example

```
package a_java_core.a_BasicEexample;
```

## `class`
* A "class" is the blueprint from which individual objects are created.
* A class: every line of code in java need to be inside a "Class".
* A class contains all the lines of code in the file.
* example
```
public class A_javaBasicVariable {
}
```

## `main()` - java `main` Method
* In Java, each application has an entry point (a starting point), which is a method called "main".
    *  Every program in Java must have a class.
    *  Every Java program starts from the main method.

* example:
```java
class MyClass {
  public static void main(String[ ] args) {
    System.out.println("Hello world");
  }
}
```

### java main() method template:

* main() template
```
  public static void main(String[] args) {
		// TODO Auto-generated method stub
	}
```

* method template:
    * `public`: anyone can access it
    * `static`: method can be run without creating an instance of the class containing the main method
    * `void`: method doesn't return any value
    * `main`: the name of the method
    * `String[] args`: This is an `array of String objects`.
        * each `String` in the array is one of the command-line arguments when executing the Program code - `MyProgram`.
        ```
        $ java MyProgram arg1 arg2 arg3
        ```
    * `{  }`: code block

## attributes 
* attributes (global variable) 
    * attributes / variable declaration
    * attributes is a variable inside a class.
* exmaple
```
enter example
```

## access Modifiers attributes: 
* access Modifiers attributes: private/ public/ default/ protected.
   * `private` - accessible only within the declared class itself.
   * `public` - accessible from any other class.
   * `default` -  no access control modifier available to any other class in the same package.
   * `protected` - like "default" + "subclasses" can access protected variable/method of the superclass

* example:
```
TODO: add example
```

```
TODO: add example
```

----

<p align="right">(<a href="#topage">back to top</a>)</p>
<br/>
<br/>
