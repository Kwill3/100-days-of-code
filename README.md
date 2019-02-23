# 100 Days of Code, progress log.

<h2 align="center"> Intro </h2>
Hello World! William Lee here and this is my log for the 100 Days of Code challenge. I've been learning coding on my own (online) for the most of the past year but I haven't been seriously making projects until recently. Since May 2018, I've been going through courses on codecademy and freecodecamp so I've had some knowledge of HTML, CSS and Javascript which should be sufficient for me to start doing some simple projects. In hindsight, the most useful thing I have learnt so far is to know how to search for the answers online and where to look for them. A lot of resources are actually easily found online but otherwise it would be helpful to have a friend or find help from the community. By the end of this challenge I hope to be able to at least be proficient in all the basics of front-end scripts and know how and where to learn the advanced concepts.

<h2 align="center"> Day 0: 18 February 2019 </h2>

**Today's Progress**: Today is all about learning how to use GitHub through the terminal in Visual Studio Code, which is the IDE that I am using currently. I posted my 'test' repository and written down the steps from cloning the repository to adding and committing and putting update descriptions.

**Resources**: [FreeCodeCamp's GitHub tutorial by Tiffany Thompson](https://www.youtube.com/watch?v=x0EYpi38Yp4)

**Thoughts**: GitHub definitely comes off as being intimidatingly intricate and using terminal to commit to repositories, even much so. However I hope to be able to make heads or tails of the whole site and it's functions as I've heard it is really useful to know the capabilities of GitHub.

<h2 align="center">  Day 1: 19 February 2019 </h2>

**Today's Progress**: Did a simple clock project that takes the time from your device. 

**Resources**: [Coder's Digital Clock Project](https://googlecreativelab.github.io/coder-projects/projects/digital_clock/index.html)
[My own clock (Repository in GitHub)](https://github.com/Kwill3/clock)

**Thoughts**: It is a very simple project, very suitable for absolute beginners and in my case very refreshing to go over all the HTML and CSS scripts that I have learned a while back. It did taught me something new thought, which was how to use jQuery. It is my first time using jQuery and I hope to learn more about it.

<h2 align="center">  Day 2: 20 February 2019 </h2>

**Intro**: Started another clock project (I have no obsessions with clocks, I promise) which I have been wanting to do for a long time but never gotten around to doing it. I first saw this clock from Destin of SmarterEveryDay, back then I haven't even started learning coding and I was gonna build the physical clock but never gotten around to it. Now I get to build the virtual one! It is called a TIX clock and it is one geeky little clock. 

**Today's Progress**: I started by searching online to see if anyone has come up with one and found Xavier Decuyper's JS TIX clock, then I read through his blog post and tried to the best of my abilities to write my own code. I admit I had to resort to reading his source code to figure out how to structure my own JS code. I wasn't able to get mine to run.

**Resources**: [Xavier Decuyper's TIX](https://www.savjee.be/2014/02/TixClock-clone-in-Javascript/)

**Thoughts**: I still have a ways to go to be proficient in Javascript, I would like to be able to write my own code for the entirety of a project without having to refer to someone else's code but sometimes I just don't know what functions do I need to use. I might need to do some reading on people's codes and see if I can't learn something.

<h2 align="center">  Day 3: 21 February 2019 </h2>

**Today's Progress**: Continued with my TIX clock, still did not manage to get it running correctly. I discovered a fault in my Visual Studio Code environment, which I must have set up incorrectly. When trying to 'node <js filename here>' in my terminal, my javascript file keeps getting 'document' and 'windows' not defined error prompts. I thought it was that I wasn't using the 'onload' or 'document.ready' or putting 'defer' to my JS script but after scouring the internet for hours and even asking for help from a friend, I still did not find out what was wrong.

**Thoughts**: By the end of the day before retiring to bed, my plans for tomorrow is to find out the root cause, which I figure probably might have something to do with the 'node' not working correctly in my IDE to access the DOM. I have squinted at every line of my code and still could not find what is wrong, it doesn't help that I couldn't use the debug feature on VS either (which might be also because of the same error).

<h2 align="center"> Day 4: 22 February 2019 </h2> 

**Today's Progress**: Finally completed the TIX clock project, figured the reason for 'node' running on my JS file to have undefined properties for 'document' is because it is just running the external JS file which is not linked to the HTML file therefore would not be defined. I also learned a bit more about source control in VS Code.

**Resources**: [TIX Clock Repository in GitHub](https://github.com/Kwill3/tix-clock)
[Visual Code Studio tutorial by Traversy Media](https://www.youtube.com/watch?v=fnPhJHN0jTE)

**Thoughts**: Still struggling with using the full functionality of VS Code but overall improving my working knowledge of it. It is very helpful and saves me a lot of keystrokes though, just need to figure out how to debug my future external JS files or find another way to build the projects.

<h2 align="center"> Day 5: 23 February 2019 </h2>

<img src="https://lh3.googleusercontent.com/B7Cc1b6khlhgNFzzKxhRihDAZm2_oJBZXW9HL5rD7MAOKyR7U7M_K8zpUj6AV5BE2o6zFVDIQI5BHKktis4k9YA1nIXD0uJiLTGmeUzmwPFzkd3ussxU2oo67VE1LZ6PXZT_yesACucXswzRKqTgh9kGpeXhbgDAuebjhagUXf4JJRrLdwo076UMojWJBYocggLIr6sc7APIlekuvIMPz8kEeVjH5M9ikXSYSJkW9LTDNTc6zUwLGxQJA1-JO1sRSa2MeR_0WTbOLMkmsF6U2-d9q4qIIJC9l8742fvG6tnDyZvCFD2-JTmmCgCs56flbVA-w2g3kCj4fZ2vbgQOHokA5Z2vDtxy9nWdZemw6PBqxhV9N8JdB4eDs3LVIMbONU620OPZB2IeqpKS4mtYycoHfIpxNFM44uftzBEJhJkp2jljZowJpihfEJLfQAgDbLnjWPzOv3E_zo5trnv6P9-UqTLpnbuuj4nJH0JFg4hEWsgWUZlO9f6lnUr3Ubkz0CakwR_DC8fcrVrCokEDY2RLVDB8r4nkwrao1WKtl_1KuI8BJB-YPZgpRpADLFjnuFEDFIQTICWhESb9FV5m0hN3mKF6ljpr79Lau-l5--llZEFSektzoBwazBCxs_xEr_a6TnBdhoEngIi-fiKPz5OsMn8zQ3xG0treK7HaSuM2gcBPGtl5x0-gcG3YafKFSpq0aexmPi14WzMJ0nsrohVN=w1006-h416-no" alt="survey-screenshot">

**Today's Progress**: Completed one of FreeCodeCamp's Responsive Web Design Project, which is the Survey Form Project.

**Resources**: [FreeCodeCamp Responsive Web Design - Survey Form](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-survey-form/)
[My Survey Form - CodePen](https://codepen.io/Kwill3/pen/JZXaqb)
[GitHub](https://github.com/Kwill3/FCC-Survey)

**Thoughts**: This was a fairly interesting project which I built with HTML and CSS, didn't find it to be too difficult but still had to look up online to jog my memory especially on the 'forms' part. OVerall, I now feel more confident working with HTML.