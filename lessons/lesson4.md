---
title: Lesson 4 - do-while
has_children: false
nav_order: 5
description: C# do-while statement
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

# do - while statement

The **do** statement executes a statement repeatedly **while** a specified expression evaluates to false. 

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
            int i = 1;
            do
            {
                sum = sum + i;
                i++;
            }
            while (i < 11);

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

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://csharpfoundation.tutorial.rclapp.com/lessons/lesson4.html';
this.page.identifier = 'f02-04'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://.csharpfundation.tutorial.rclapp.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>