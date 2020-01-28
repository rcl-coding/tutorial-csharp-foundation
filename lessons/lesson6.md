---
title: Lesson 6 - foreach loop
has_children: false
nav_order: 7
description: C# foreach loop statement
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

# foreach loop

The **foreach** statement repeats statement(s) for each element in an array. 

- Write the following code :

```csharp
using System;

namespace LearnCSharp
{
    class Program
    {
        static void Main(string[] args)
        {
            string[] names = { "Jane", "Sue", "Lisa", "Mary" };
            foreach (string item in names)
            {
                if (item == "Mary")
                {
                    Console.WriteLine("Hey, Mary was found !");
                }
                else
                {
                    Console.WriteLine("Looking for Mary ...");
                }
            }
        }
    }
}
```

- Run the application in the Console Window

Output in Console Window
```
Looking for Mary ...
Looking for Mary ...
Looking for Mary ...
Hey, Mary was found !
```

****

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://csharpfoundation.tutorial.rclapp.com/lessons/lesson6.html';
this.page.identifier = 'f02-06'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://.csharpfundation.tutorial.rclapp.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>