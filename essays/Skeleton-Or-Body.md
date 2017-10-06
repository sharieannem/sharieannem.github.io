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

HTML + CSS:
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

First of all, when asking questions, it is very important to know what you want and lay down what you know. It can be extremely easy to just throw a bunch of questions at someone whom you think has all the answers for your problems but it is most likely inefficient to do so and is seen as very bothersome to most as it shows your incapability to communicate your questions/problems in a professional and concise way. It also shows that you are more focused on getting it done rather than the quality of understanding the concepts and possibly applying it to other similar questions/problems. 
Therefore, as an example, I browsed the various questions stored in StackOverflow and stumbled on a questions that is delivered appropriatly to the forum community. 

The question is given below:

> "How do you create a remote Git branch? I created a local branch which I want to 'push' upstream. There is a similar question here on > Stack Overflow on how to track a newly created remote branch. However, my workflow is slightly different. First I want to create a > > local branch, and I will only push it upstream when I'm satisfied and want to share my branch.
> How would I do that? (my google searches did not seem to come up with anything).
> How would I tell my colleagues to pull it from the upstream repository?
> UPDATE With Git 2.0 there is a simpler answer I have written below: https://stackoverflow.com/a/27185855/109305"

If you are interested, the post can be accessed by clicking [here](https://stackoverflow.com/questions/1519006/how-do-you-create-a-remote-git-branch).
As you can see here, this post is not just one line asking for help. Instead it clearly demonstrates the user's attempts on finding solutions on his/her own and it clearly states what he/she is trying to do. As a result for its quality, this question got thousands of positive feedback and responses. The user was even thoughtful enough to update his/her post to include the answer to the question!

## Section Title

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
