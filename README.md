# jcole-lyrics-bot
Creates J. Cole type lyrics


I was bored so I decided to make something...
Here is a program that creates lyrics in the style of of J. [the vill is back, cole world, king is back] Cole- J. Cole...

This has two main parts...

Python - scrapes web., songlyrics dot com, gets j.cole lyrics, changes swear words to another word (Durag).

Then the winforms app trains the program to come up with J. Cole lyrics... it uses a markov chain.

What is a markov chain you may or may not have asked? 

Well it is a stochastic model. 

What is a stochastic model?

A stochastic model is a pattern that cannot be predicted precisely and it may be analysed statistically.

What is analysed statistically?

Statistical analysis is basically the collection, organisation and analysis of data. This can lead to figuring out the patterns, 
and nuances of said data, since nothing is truly random, everything can be statistcally analysed and you will always find some type of pattern.

So this winforms app takes in data, organises it, analyses it then predicts the next step in a sequence, in layman's terms.

So how does it come up with it's own j.cole lyrics using the markov chain.
Fortunately we live in an "information world" where anything is possible. All I did was google c# markov chain and bam... results. 
I used this github repos - https://github.com/chriscore/MarkovSharp it looked the easiest to use and it definately. Just look at the code. Thank you Chris Core for your
intellegnce.

So I inputted data into this statistical analysis machine, known as a stochasit model, known as a markov chain.

Here it is pulling through what I want. It predicts what type of sentance would be next based on some of j.coles old lyrics.

![Image](/Image1.PNG)

It is not perfect. but that doesn't matter.

Ok I have a challenge for you. If you have noticed there are is a lot of commented out code. this isn't me being lazy. 
I want to challenge you to implement this rhyming API that I am calling and try to make it use a word the user enters in the rhyme in j.coles style.

Feel free to download it and create your own repos with improvements and link them to me.
Next project will be implementing a voice analyzer that will train it to sound like J. Cole as well.

Uses https://github.com/chriscore/MarkovSharp library to train.
