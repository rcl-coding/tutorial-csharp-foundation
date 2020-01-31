---
title: Lesson 2 - C# Types
has_children: false
nav_order: 3
description: C# Types
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

# Types

C# is a strongly typed language. 

Every **variable** must be defined by a **type**. 

The following is a list of common types used in C#:

- string
- int
- long
- decimal
- bool
- DateTime

## Strings

The **string** type is used for text. 

- Write the following code in the **Main** method :

```java
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            string name = "Anil";
            Console.WriteLine($"Hello {name}");
        }
    }
}
```
- Run the application in the Console Window

Output in Console Window
```
Hello Anil
```

The variable, **name** is of type **string**.

The **value** of the name variable is set to 'Anil'.

## Integers

Integers (**int**) are used to represent whole numbers (e.g. 3, 5, etc.). The range for the int type is :  -2,147,483,648 to 2,147,483,647.

The **long** type has a greater range : -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807

- Write the following code :

```java
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x = 1;
            int y = 3;
            int sum = x + y;
            Console.WriteLine($"Sum : {sum}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
Sum : 4
```

## Decimal

The type **Decimal** is used to represent decimal numbers (eg: 3.14).

- Write the following code :

```java
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Decimal pi = 3.14M;
            Console.WriteLine($"The value of pi is {pi}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
The value of pi is 3.14
```

'M' is used to specify that the number is a decimal.

## Bool

The type **bool** is used to represent **true** or **false** (Boolean) values.

- Write the following code :

```java
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            bool b = true;
            Console.WriteLine($"{b}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
True
```

## DateTime

The type **DateTime** is used to represent Date and Time.

- Write the following code :

```java
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            DateTime now = DateTime.Now;
            Console.WriteLine($"The current date and time is {now}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
The current date and time is 1/27/2020 4:27:54 PM
```

## Arrays

You can store multiple variables of the same type in an array data structure. 

You declare an array by specifying the type of its elements. 

Note the index starts from 0.

```java
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] numbers = { 3, 0, 4, 8, 2 };
            int a = numbers[3];
            Console.WriteLine($"The fourth number in the array is : {a}");
        }
    }
}

```

- Run the application in the Console Window

Output in Console Window
```
The fourth number in the array is : 8
```

****

# Bob Tabor Videos

[Courtesy Microsoft and Bob Tabor](https://channel9.msdn.com/Series/CSharp-Fundamentals-for-Absolute-Beginners)

****

> NOTE - These videos are a little dated, Visual Studio 2013/2015 is being used here. But the principles are basically the same.

*****

## Understanding Data Types and Variables

<div style="overflow:hidden; padding-bottom:56.25%; position:relative; height:0;">
<iframe style="left:0; top:0; height:100%; width:100%; position:absolute;" src="https://www.youtube.com/embed/5Tquxkpj9DM?autoplay=0&rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

****

## Working with Strings

<div style="overflow:hidden; padding-bottom:56.25%; position:relative; height:0;">
<iframe style="left:0; top:0; height:100%; width:100%; position:absolute;"  src="https://www.youtube.com/embed/ZJs027Q1ReI?autoplay=0&rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

****

## Working with Dates and Times

<div style="overflow:hidden; padding-bottom:56.25%; position:relative; height:0;">
<iframe style="left:0; top:0; height:100%; width:100%; position:absolute;" src="https://www.youtube.com/embed/mCMNP9yACWw?autoplay=0&rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

****

## Understanding Arrays

<div style="overflow:hidden; padding-bottom:56.25%; position:relative; height:0;">
<iframe style="left:0; top:0; height:100%; width:100%; position:absolute;" src="https://www.youtube.com/embed/a31-Qt9zjIM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

****

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://csharpfoundation.tutorial.rclapp.com/lessons/lesson2.html';
this.page.identifier = 'a03-02'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://coding-skills-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>


