---
layout: essay
type: essay
title: My Crash Course on Meteor
date: 2017-09-07
labels:
  - Meteor
  - Application Architecture
---

<img class="ui medium left floated image" src="../images/meteor-meme.jpg">

## They Were Not Joking When They Named It Meteor

Like the name implies and from the meme above, Meteor did rock my world these past two weeks. I took a crash course in Meteor, a client-server application architecture, and while doing so, I did indeed "crash" a couple of times. All puns aside, I definitely learned a lot about creating web applications using Meteor.

## Major Dislike

One aspect about running Meteor from my Windows 10 8GGB RAM computer was the load time. Installing and running meteor for a project took me about 10 minutes if I was lucky. If I was not lucky, let's just say it was faster for me to finish the updates to my application than the sum time it took for Meteor to get up and running.

## A Few "Crashes"



## What is "not smart"?

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
