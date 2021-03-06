# Unit 1 Lesson 6 - Arrays

[Previous Lesson](https://github.com/Kevin-Lago/Java-Course-Guide/tree/master/unit_1_getting_started/lesson_5_methods#unit-1-lesson-5---methods)

[Lesson Slides](https://docs.google.com/presentation/d/12SsbLA1HV4kX1I71zBAGQC0I2icgxCpkWr3B5zB9iB0/edit?usp=sharing)

---
## Arrays

- An array is a data structure that can hold a fixed number of data values of the same data type.
- Data values in the array are called elements.
- We can think of Arrays as a list. For example a list of car brands
	- Toyota
	- Ford
	- Chrysler
	
- Or a list of grades
	- 86
	- 97
	- 64
	- 78

### Helpful Links

to read

- []()

to watch

- []()

---
## Declaring Arrays

- In Java you define the data type of the array when it's declared.
- We tell Java we are creating an Array with [].

```java
// This is an array of String(s)
String[] exampleStringArrayDeclaration;

// This is an array of int(s)
int[] exampleIntArrayDeclaration;
```

### Helpful Links

to read

- []()

to watch

- []()

---
## Initializing Arrays

- The length of an array is specified when instantiated/initialized.
- Once the length of the array is specified the length can not be changed.

```java
String[] stringArray = new String[5];

String[] listOfCarBrands = { "Toyota", "Ford", "Chrysler", "Mazda", "Bentley" };
```

### Helpful Links

to read

- []()

to watch

- []()

---
## Array Elements

- The elements in an array are ordered.
- The location of each element is indicated by a numerical index.

```java
String[] listOfFruits = { "apples", "bananas", "oranges", "peaches" }
```

| Element   | index |
| ----------|:-----:|
| "apples"  | 0     |
| "bananas" | 1     |
| "oranges" | 2     |
| "peaches" | 3     |

```java
int[] listOfNumbers = { 3, 1, 2, 0 }
```

| Element | index |
| --------|:-----:|
| 3       | 0     |
| 1       | 1     |
| 2       | 2     |
| 0       | 3     |

```java
String[] stringArray = new String[4];
```

| Element | index |
| --------|:-----:|
| null    | 0     |
| null    | 1     |
| null    | 2     |
| null    | 3     |

- We can access an Element of an Array with that index.

```java
String[] stringArray = new String[4];
stringArray[0] = "define";
stringArray[1] = "value";
stringArray[2] = "at";
stringArray[3] = "index";
```

| Element  | index |
| ---------|:-----:|
| "define" | 0     |
| "value"  | 1     |
| "at"     | 2     |
| "index"  | 3     |

### Helpful Links

to read

- []()

to watch

- []()

---
## Loops and Arrays

- To access all the elements individually we can use Loops!
- We can use ".length" to get the length of that array.

```java
String[] listOfCarBrands = { "Toyota", "Ford", "Chrysler", "Mazda", "Bentley" }

for (int i = 0; i < listOfCarBrands.length; i++) {
	System.out.println(listOfCarBrands[i]);
}
```

- Another way we can loop through an array is an enhanced for loop.

```java
String[] listOfCarBrands = { "Toyota", "Ford", "Chrysler", "Mazda", "Bentley" }

for (String brand : listOfCarBrands) {
	System.out.println(brand);
}
```

### Helpful Links

to read

- []()

to watch

- []()

---
## Activities

- Create Arrays of different Data Types
- Access and change elements at a specific index
- Loop through those arrays
- Find the min max and average of an array of ints

### Helpful Links

to read

- []()

to watch

- []()

---

[Lesson Quiz]()

[Next Lesson](https://github.com/Kevin-Lago/Java-Course-Guide/tree/master/unit_2_understanding_java/lesson_1_classes_and_objects#unit-2-lesson-1-classes-and-objects)

# Full Java Course

<a href="https://github.com/Kevin-Lago/Java-Course-Guide#java-course-guide">
	<img src="../../java_logo.png" />
</a>


