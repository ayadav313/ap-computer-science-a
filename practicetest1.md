# Name: 

# Unit 1: What is the output of the following Java code snippet?

```java
int a = 10;
double b = 4.5;
double result = a % b;
System.out.println(result);
```

# Unit 2: Consider the following code snippet:

```java
String str1 = "Hello";
String str2 = "World";
str1.concat(str2);
System.out.println(str1);
```

**What is the output of this code?**

# Unit 3: What is the output of the following Java code snippet?

```java
int x = 5;
int y = 10;
if (x < y) {
  System.out.println("x is less than y");
} else {
  System.out.println("y is less than or equal to x");
}
```

# Unit 4: Write a Java program that prints the first 20 Fibonacci numbers.

# Unit 5: Consider the following Java code snippet:

```java
public class Dog {
  private String name;
  private int age;

  public Dog(String name, int age) {
    this.name = name;
    this.age = age;
  }

  public String getName() {
    return name;
  }

  public int getAge() {
    return age;
  }

  public void bark() {
    System.out.println("Woof!");
  }
}
```

**Create a new class called Poodle that extends the Dog class and adds a new instance variable called haircutStyle.**

# Unit 6: Write a Java program that finds the maximum and minimum values in an array of integers.

# Unit 7: Write a Java program that removes all occurrences of a specified element from an ArrayList.

# Unit 8: Write a Java program that prints the sum of the elements in a 2D array.

# Unit 9: Consider the following code snippet:

```java
public class Animal {
  protected String species;

  public Animal(String species) {
    this.species = species;
  }

  public void makeSound() {
    System.out.println("Generic animal sound");
  }
}

public class Dog extends Animal {
  private String breed;

  public Dog(String species, String breed) {
    super(species);
    this.breed = breed;
  }

  public void makeSound() {
    System.out.println("Woof!");
  }
}
```

**Create a new class called Poodle that extends the Dog class and overrides the makeSound method to print "Yip!".**

# Unit 10: Write a Java program that calculates the factorial of a given integer using recursive methods.