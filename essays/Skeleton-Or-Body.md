---
layout: essay
type: essay
title: Do You Want A Skeleton or Do You Want A Body?
date: 2017-09-07
labels:
  - Semantic UI
  - UI Frameworks
  - HTML
  - CSS
---

<img class="ui medium center image" src="../images/frameworks-humour.jpg">

## Skeletons

You can think of programming in HTML as building a skeleton or maybe a doll that has absolutely no facial features, clothes, accessories, and hair. When you build that image in your mind, it can be a bit terrifying! Looking at it might even give you an urge to wanna add those special features to make the doll "pretty" and more easy to look at. In terms of programming, this is where CSS is put into play. You add a sprinkle of CSS to your HTML code and voila! Out comes a program that is more aesthetically appealing.

HTML Only:

<h1>This is just a plain header</h1>

```
<!DOCTYPE HTML>
<html>
<head>
</head>

<body>
<h1>This is just a plain header</h1>
</body>
</html>
```
<hr>

HTML + CSS:

<h1 style="text-shadow: 0 0 3px #99FFFF">This is just a plain header</h1>

```
<!DOCTYPE HTML>
<html>
<head>
</head>

<body>
<h1 style="text-shadow: 0 0 3px #99FFFF">This is just a plain header</h1>
</body>
</html>
```

## The Proccess and Time Commitment

The combination of HTML with CSS can produce beautifully designed websites but coding from scrath can result to some cons that you are likely to experience. First of all, to be able to create sylish user interfaces, you would need an extensive knowledge of the HTML and CSS programming languages plus A LOT of practice to enhance your application of your knowledge. Even with that, you would still be bugged by the responsibility of making and maintaining your program's compatibility with multiple browsers and platforms (which could take more time than it took you to code). All the while, debugging would be a nightmare with the hundreds of lines of code that you had written.

## UI Frameworks to the rescue!

Questions opposite to the example above are more likely to yield the opposite results or no results at all. Questions that are told in a "not smart" fashion tend to sound like the user is desperate for the answer only and/or demonstrate the user's lack of research on his/her own question. These questions can be very ambiguous as it might not clearly state what the goal is in a concise and professional manner.

Below shows an example of a question that exactly portrays this image:

> "I need help in java: so in the code I'm working itread from the input file and writes that info to the output file. in the input  
> file I have this info 1245: my address: miami, fl. then when the information is being written down in the output I need it to change 
> the : for |. can anyone explain how can I do This."

```
import java.io.*;

public class fileConverted {

public static void main(String args[]) {        
    try {
        File input = new File("input");
        File output = new File("output");
        Scanner sc = new Scanner(input);   
        PrintWriter printer = new PrintWriter(output);
        while (sc.hasNextLine()) {
            String s = sc.nextLine();
            printer.write(s);
        }
        printer.flush();
    }
    catch (FileNotFoundException e) {
        System.err.println("File not found. Please scan in new file.");
    }
}
```

If you are interested, the post can be accessed by clicking [here](https://stackoverflow.com/questions/32686789/i-need-help-in-java).
First of all, the headline is not helpful and does not give others browsing through the forums to clearly know what it is the user is asking for. Secondly, this post is very confusing because of its wording. It clearly shows the lack of the user's attempt to find solutions on his/her own before directing the question to the forum community. Because of the quality, this question did not attract a lot of answers—compared to the number of views it got (53), it is a very low proportion—and has 4 negative ratings.

## Conclusion

Admittingly, I sometimes do ask "not-so-smart" questions and looking back, the answers I got either left me in the same confused state or made me even more confused. After reading about the effective ways on how to ask [questions](http://www.catb.org/esr/faqs/smart-questions.html) and applying what I learned by pinpointing the bad questions from the good on StackOverflow, I have a good understanding on how to communicate questions effectively in a way that actually encourages people to answer and help me out.
