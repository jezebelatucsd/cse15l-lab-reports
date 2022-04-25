# Lab Report 2 by Jezebel Yangari

## failure-inducing inputs
>Image 1 Changes
![Image](full_lab2_4.png)
>Image 2 Changes
![Image](full_lab2_3.png)
>Variations of repeating paretheses and brackets were used to attempt to make the program fail.

## Symptom Brought by All Chnages/Inputs, Infinite Loop
> The infinite loop was the major symptom that we cam eacross. Here I used `control + C` to stop it from running. This was our key identifier that told us we had not yet caught the error in the "MarkdownParse.java" file.
![Image](lab2_infiniteloop.png)

## Change 1/2: 
> Adding a for Loop to break when open brakcet and close bracket are hit.
> If those brackets are at the end of the input, then it would break.
> We came to the conclusion that we should break once this condition was met, so that the infinite loop would not take place. 
![Image](full_lab2_1.png)

## Chnage 3:
> Adding a for Loop to break when open parentheses and close paratheses are hit.
> The reasoning was the same for the previous chnages that were made.
> > We concluded that the reason there was an infinite loop was because the condition of the link ending was never met with repeated brackets and parentheses. 

![Image](full_lab2_2.png)





