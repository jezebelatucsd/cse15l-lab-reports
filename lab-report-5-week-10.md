# Lab Report 5 by Jezebel Yangari
# Note: I completeed this to the best of my ability, but I have noticed that fellow students with similar submissions to me have more points. I just hope that my grade in the class does not drop by virtue of which tutor/ TA I get that day.

* I searched through the results manually in order to find the different outputs.

> vimdiff
<img width="1380" alt="Screen Shot 2022-06-05 at 9 59 18 PM" src="https://user-images.githubusercontent.com/103277481/172097650-d8ca7c73-f769-4465-8417-e7f4d2ad5f78.png">

## Test File 1: 201.md

> other repo to this test ----> [Link](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md)

### Describes which implementation is correct
> Both implementations are incorrect (in the above screenshot, on 201 md). 
* My ouput according to preview 1:
<img width="1144" alt="Screen Shot 2022-06-10 at 6 16 50 PM" src="https://user-images.githubusercontent.com/103277481/173167081-2bd54fae-403a-47d8-bd27-68dcbce2025b.png">
* My ouput according to running the file 1:
<img width="1046" alt="Screen Shot 2022-06-10 at 6 38 48 PM" src="https://user-images.githubusercontent.com/103277481/173167791-4c530c58-cb93-4f18-9c6a-491fccd6373a.png">
* THEIR ouput according to running 1:
<img width="800" alt="Screen Shot 2022-06-10 at 6 49 55 PM" src="https://user-images.githubusercontent.com/103277481/173168080-f0a20663-d1ef-41fe-a50c-78e0fc63584f.png">

### Provides correct description of the bug

* The program is trying to access elements that do no exist and/or have not been account for. This is demonstrated by the string index out of range exception.

### Provides code snippet that needs to be changed

> Line 18 is where the error is being pointed to but it is likely before that. (THEIR REPO)
<img width="812" alt="Screen Shot 2022-06-10 at 7 22 25 PM" src="https://user-images.githubusercontent.com/103277481/173169035-e1c3cdff-28a1-4295-a80f-dadc6d2a4da6.png">


## Test File 2: 194.md
> other repo to this test ----> [Link](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md)


### Describes which implementation is correct

> Both implementations are incorrect (in the above screenshot, on 201 md). 
### Provides correct description of the bug
* The program is trying to access elements that do no exist and/or have not been account for. This is demonstrated by the string index out of range exception.


### Provides code snippet that needs to be changed

>Line 18 is where the error is being pointed to but it is likely before that. (THEIR REPO)
<img width="812" alt="Screen Shot 2022-06-10 at 7 22 25 PM" src="https://user-images.githubusercontent.com/103277481/173169035-e1c3cdff-28a1-4295-a80f-dadc6d2a4da6.png">

* My ouput according to preview 2:

<img width="1177" alt="Screen Shot 2022-06-10 at 6 20 47 PM" src="https://user-images.githubusercontent.com/103277481/173167189-f1833bf2-456c-4573-afe6-2bd504d2f13e.png">

* My ouput according to running the file 2:
<img width="1057" alt="Screen Shot 2022-06-10 at 6 39 52 PM" src="https://user-images.githubusercontent.com/103277481/173167825-dd1298f2-b1e5-4e9b-a658-59b66393014e.png">

* THEIR ouput according to running 2:

<img width="797" alt="Screen Shot 2022-06-10 at 6 50 32 PM" src="https://user-images.githubusercontent.com/103277481/173168098-11478ab8-364e-4081-b892-3a69de9fc500.png">

##  ---------- OLD LAB REPORT ----------

## How you found the tests with different results (Did you use vimdiff on the results of running a bash for loop? Did you search through manually? Did you use some other programmatic idea?)
> vimdiff
<img width="1380" alt="Screen Shot 2022-06-05 at 9 59 18 PM" src="https://user-images.githubusercontent.com/103277481/172097650-d8ca7c73-f769-4465-8417-e7f4d2ad5f78.png">

## Provide a link to the test-file with different-results (in the provided repository or your repository , either is fine)
> answer: other repo [Link](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/200.md)

### For each test:
## Describe which implementation is correct, or neither if both give the wrong output
> answer: My implementation is correct because it does not print "url".

## Decide on what it should produce (i.e., expected output) by using either VScode preview or the CommonMark demo site. 
> answer: 
> their repo
<img width="1212" alt="Screen Shot 2022-06-05 at 10 20 28 PM" src="https://user-images.githubusercontent.com/103277481/172099648-68180049-6ca6-416b-b4cb-633bb053261c.png">
> my repo:
<img width="1207" alt="Screen Shot 2022-06-05 at 10 24 31 PM" src="https://user-images.githubusercontent.com/103277481/172100029-e529b932-a65e-451a-9b8b-7de9cb5fbf2d.png">

## For the implementation that’s not correct (or choose one if both are incorrect), describe the bug (the problem in the code) in about 2-3 sentences. You don’t have to provide a fix, but you should be specific about what is wrong with the program, and show the code that should be fixed (Provide a screenshot of code and highlight where the change needs to be made).
> answer: More conditions likely need to be added for the proper output to occur. The output in the preview seems to be the same for both.
<img width="864" alt="Screen Shot 2022-06-05 at 10 25 28 PM" src="https://user-images.githubusercontent.com/103277481/172100123-370324e7-240c-40b7-9f69-7c90a353c338.png">
