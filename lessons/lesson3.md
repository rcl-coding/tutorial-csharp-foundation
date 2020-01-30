---
title: Lesson 3 - if-else
has_children: false
nav_order: 4
description: C# if-else statement
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

# if - else statement

An **if** statement identifies which statement to run based on the value of a Boolean (true or false) condition. 

The following are some common comparators that can be used when you set up conditions:

- if(a == b) : if a is equal to b;
- if(a < b) : if a is less than b;
- if(a > b) : if a is greater than b;
- if(a != b) : if a is not equal to b;

Type the following code :

```csharp
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            string result = string.Empty;
            int number = 5;

            if (number == 12)
            {
                result = "dozen";
            }
            else
            {
                result = "not a dozen";
            }

            Console.WriteLine($"The amount {number} is {result}");
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
The amount 5 is not a dozen
```

****

# Bob Tabor Videos

****

> NOTE - These videos are a little dated, Visual Studio 2013/2015 is being used here. But the principles are basically the same.

*****

## The If Decision Statement

<iframe src="https://channel9.msdn.com/Series/CSharp-Fundamentals-for-Absolute-Beginners/The-if-Decision-Statement/player?format=html5" width="640" height="360" allowFullScreen frameBorder="0" title="The if Decision Statement - Microsoft Channel 9 Video"></iframe>

****

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://csharpfoundation.tutorial.rclapp.com/lessons/lesson3.html';
this.page.identifier = 'a03-04'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://coding-skills-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
