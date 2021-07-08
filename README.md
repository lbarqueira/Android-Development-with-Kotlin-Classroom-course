# [Android Development with Kotlin: Classroom course](https://developer.android.com/courses/android-development-with-kotlin/course)

This course is designed for students taking instructor-led Android curriculum in a classroom setting as part of the Android Development with Kotlin program.

## [Unit 1: Get started with Kotlin](https://developer.android.com/courses/android-development-with-kotlin/unit-1)

Take your first steps programming in Kotlin.


### [Lesson 1: Kotlin basics](https://developer.android.com/courses/pathways/android-development-with-kotlin-1)

Get started developing in Kotlin, and learn the basics of the Kotlin programming language: data types, operators, variables, control structures, and nullable versus non-nullable variables.

[Summary](https://developer.android.com/codelabs/android-development-kotlin-1.2?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-1%3Fhl%3Den%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-1.2&hl=en#5)

Kotlin is very similar to other languages when it comes to the basics like operators, lists, and loops, but there are some important differences.  

The following features may be different in Kotlin than what you're used to in other languages:
- Kotlin types can't be implicitly converted—use casting.

- Variables declared with ```val``` can only be assigned once.

- Kotlin variables are not nullable by default. Use ```?``` to make variables nullable.

- With Kotlin, you can loop through the index and elements of an array at the same time in a for loop.

The following Kotlin programming constructs are similar to those in other languages:
- Arrays and lists can have a single type or mixed types.

- Arrays and lists can be nested.

- You can create loops with ```for```, ```while```, ```do/while```, and ```repeat```.

- The ```when``` statement is Kotlin's version of the switch statement, but when is more flexible.

[Learn more](https://developer.android.com/codelabs/android-development-kotlin-1.2?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-1%3Fhl%3Den%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-1.2&hl=en#6)
- [Explicit type conversion](https://kotlinlang.org/docs/reference/basic-types.html#explicit-conversions)
- [Defining variables](https://kotlinlang.org/docs/reference/basic-syntax.html#defining-variables)
- [String templates](https://kotlinlang.org/docs/reference/basic-types.html#string-templates)
- [Nullable values](https://kotlinlang.org/docs/reference/basic-syntax.html#using-nullable-values-and-checking-for-null)
- [Lists](https://kotlinlang.org/docs/reference/collections-overview.html#list)
- [Arrays](https://kotlinlang.org/docs/reference/basic-types.html#arrays)
- if, when, for, while
- ?: (Elvis) operator
- !! operator

### [Lesson 2: Functions](https://developer.android.com/courses/pathways/android-development-with-kotlin-2)

Create a Kotlin program and learn about functions in Kotlin, including default values for parameters, filters, lambdas, and compact functions.

[Summary](https://developer.android.com/codelabs/android-development-kotlin-2.1?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-2.1#6)

- To create new Kotlin source files in IntelliJ IDEA, click on "src" in the Project pane and right-click to bring up a menu. Select "New->Kotlin File/Class".  

- To compile and run a program in IntelliJ IDEA, click the green triangle next to the ```main()``` function. Output appears in a window below.

- In IntelliJ IDEA, specify command line arguments to pass to the ```main()``` function in __Run > Edit Configurations__.

- Almost everything in Kotlin has a value. You can use this fact to make your code more concise by using the value of an ```if``` or ```when``` as an expression or return value.

- Default arguments remove the need for multiple versions of a function or method. For example: ```fun swim(speed: String = "fast") { ... }```

- Compact functions, or single-expression functions, can make your code more readable. For example: ```fun isTooHot(temperature: Int) = temperature > 30```

- You've learned some basics about filters, which use lambda expressions. For example: ```val beginsWithP = decorations.filter { it [0] == 'p' }```

- A lambda expression is a function that is not bound to an identifier, i.e. it is an anonymous function. Lambda expressions are defined between curly braces ```{}```.

- In a higher-order function, you pass a function such as a lambda expression to another function as data. For example: ```dirtyLevel = updateDirty(dirtyLevel) { dirtyLevel -> dirtyLevel + 23}```

There's a lot in this lesson, especially if you're new to lambdas. A later lesson revisits lambdas and higher-order functions in more detail.

> Note: You may have noticed that in Kotlin, as in some other languages, there is more than one correct way to do things. Making code more compact sometimes helps readability and performance, but sometimes it doesn't. As you learn more about Kotlin, you may find easier, more concise ways to do things.

[Learn more](https://developer.android.com/codelabs/android-development-kotlin-2.1?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-2.1#7)

- [String templates](https://kotlinlang.org/docs/reference/basic-types.html#string-templates)
- [when](https://kotlinlang.org/docs/reference/control-flow.html#when-expression) expression
- [Single-expression functions](https://kotlinlang.org/docs/reference/idioms.html#single-expression-functions)
- [Higher-order functions and lambdas](https://kotlinlang.org/docs/reference/lambdas.html)
- [Filters](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/filter.html)
- [Sequences](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/index.html)
- [Last parameter call syntax](https://kotlinlang.org/docs/reference/lambdas.html#passing-a-lambda-to-the-last-parameter)

### [Lesson 3: Classes and Objects](https://developer.android.com/courses/pathways/android-development-with-kotlin-3)

Learn about classes, objects, and inheritance in Kotlin. Create small programs as you learn about abstract classes, interfaces, and interface delegation.  
#### [Using Classes and Objects in Kotlin](https://developer.android.com/codelabs/android-development-kotlin-3.1?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-3.1)

[Learn more](https://developer.android.com/codelabs/android-development-kotlin-3.1?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-3.1#10)

- [Classes and inheritance](https://kotlinlang.org/docs/reference/classes.html)
- [Constructors](https://kotlinlang.org/docs/reference/classes.html#constructors)
- [Factory functions](https://kotlinlang.org/docs/reference/coding-conventions.html#factory-functions)
- Properties and fields
- Visibility modifiers
- Abstract classes
- Interfaces
- Delegation
- Data classes
- Equality
- Destructuring
- Object declarations
- Enum classes


#### [Pairs/triples, collections, constants, and writing extension functions](https://developer.android.com/codelabs/android-development-kotlin-3.2?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-development-with-kotlin-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fandroid-development-kotlin-3.2)

## From Kotlin Bootcamp for Programmers

### [Lesson 5.1: Extensions](https://codelabs.developers.google.com/codelabs/kotlin-bootcamp-extensions/)

In Lesson 5.1, you learn about collections, constants, and extension functions in Kotlin. You create small programs as you learn about pairs, triples, lists, and hash maps for storing data, and implement extension functions to add functionality to existing classes.

### [Lesson 5.2: Generics](https://codelabs.developers.google.com/codelabs/kotlin-bootcamp-generics/#0)

In Lesson 5.2, you learn about generic classes, methods, and functions in Kotlin. You create a type hierarchy, make classes more flexible by making them generic, and extend their functionality with generic methods and functions.

### [Lesson 6: Functional manipulation](https://codelabs.developers.google.com/codelabs/kotlin-bootcamp-sams/#0,)

In Lesson 6, you learn about annotations, labeled breaks, and Single Abstract Methods (SAMs). You also review lambdas and higher-order functions. You then create and use lambdas and higher-order functions, and learn about higher-order functions in the Kotlin Standard Library.


# [Android Development Resources for Educators](https://developer.android.com/teach)
### For instructors teaching a course

The Android Development with Kotlin course teaches the fundamentals of Android app development with the Kotlin programming language. These materials are designed for instructors to deliver lectures in a classroom setting. The course is 13 lessons long with each lecture being approximately 1 hour long. Each lecture is accompanied by 2 hours of hands-on codelabs for the students to complete on their own. If you’re ready to start teaching Android, use these materials to get started today.

#### Lecture slides for instructors

[Introduction](http://goo.gle/3sPw3Fz)
Android Development with Kotlin

[Lesson 1](http://goo.gle/3sSg7lK) - Kotlin Basics  

[Lesson 2](http://goo.gle/2Y5Pv2D) - Functions 

[Lesson 3](https://goo.gle/2Y2S8SO) - Classes and Objects 
