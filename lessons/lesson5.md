---
title: Lesson 5 - for loop
has_children: false
nav_order: 6
description: C# for loop statement
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

## for loop

By using a **for loop**, you can run a statement repeatedly until a specified expression evaluates to false. 

- Write the following code :

```csharp
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        { 
            int sum = 0;
            for(int i = 1; i < 11; i++)
            {
                sum = sum + i;
            }

            Console.WriteLine($"The sum of the numbers 1 to 10 is : {sum}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
The sum of the numbers 1 to 10 is : 55
```

****

# Bob Tabor Videos

[Courtesy Microsoft and Bob Tabor](https://channel9.msdn.com/Series/CSharp-Fundamentals-for-Absolute-Beginners)

****

> NOTE - These videos are a little dated, Visual Studio 2013/2015 is being used here. But the principles are basically the same.

*****

## For Iteration Statement

<div style="overflow:hidden; padding-bottom:56.25%; position:relative; height:0;">
<iframe style="left:0; top:0; height:100%; width:100%; position:absolute;" src="https://www.youtube.com/embed/JrS0e_-8Nlo?autoplay=0&rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

****

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://csharpfoundation.tutorial.rclapp.com/lessons/lesson5.html';
this.page.identifier = 'a03-05'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://coding-skills-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>