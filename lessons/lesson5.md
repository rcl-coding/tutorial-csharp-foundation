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

****

> NOTE - These videos are a little dated, Visual Studio 2013/2015 is being used here. But the principles are basically the same.

*****

## For Iteration Statement

<div style="position: relative;overflow: hidden;padding-top: 56.25%;">
<iframe src="https://channel9.msdn.com/Series/CSharp-Fundamentals-for-Absolute-Beginners/for-Iteration-Statement/player?format=html5" style="position: absolute; top: 0;left: 0; width: 100%; height: 100%;border: 0" allowFullScreen frameBorder="0" title="for Iteration Statement - Microsoft Channel 9 Video"></iframe>
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