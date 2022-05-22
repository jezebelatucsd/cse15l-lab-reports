# Lab Report 3 by Jezebel Yangari

## Option 1) Streamlining ssh Configuration
>Show your `.ssh/config file`, and how you edited it (with VScode, another program, etc)
![image](lr3_ssh_alias_login.png)

>Show the `ssh` command logging you into your account using just the alias you chose.
![image](lr3_scp_r.png)

>Show an `scp` command copying a file to your account using just the alias you chose.
![image](lr3_edited_config.png)

- **description:** This option creates a shortcut for logging into the ieng6 account. It also allows you to choose the shorthand alias to be implemented. This is another way to avoid having to type out the username and password for every log in.


## Option 2) Setup Github Access from ieng6
>Show where the public key you made is stored on Github and in your user account (screenshot).
<img width="647" alt="Screen Shot 2022-05-07 at 9 27 19 AM" src="https://user-images.githubusercontent.com/103277481/167263232-2d36637a-fff9-478b-bf28-96033ace6504.png">

>Show where the private key you made is stored on your user account (but not its contents) as a screenshot.
<img width="408" alt="Screen Shot 2022-05-07 at 9 29 12 AM" src="https://user-images.githubusercontent.com/103277481/167263297-50ee03b7-5349-44c2-bf0b-2482617aecfe.png">

>Show running `git` commands to commit and push a change to Github while logged into your ieng6 account.
<img width="807" alt="Screen Shot 2022-05-07 at 9 30 30 AM" src="https://user-images.githubusercontent.com/103277481/167263341-6dbc0518-44ef-467a-8868-ba846d079e5f.png">

>Show a link for the resulting commit.
>[RESULTING COMMIT LINK](https://github.com/jezebelatucsd/markdown-parser/commit/b640e20afdfa63b524b1b0ce207824b491ec94ab)
<img width="858" alt="Screen Shot 2022-05-07 at 9 34 19 AM" src="https://user-images.githubusercontent.com/103277481/167263477-a53c5a1b-76e7-4f82-b579-0780f2f2d0e8.png">

- **description:** Here we added an SSH Key for the course specific account. This is so less logging in is needed to be done and the process can be much quicker.


## Option 3) Copy whole directories with `scp -r`
>Show copying your whole markdown-parse directory to your ieng6 account.
<img width="690" alt="Screen Shot 2022-05-07 at 1 48 40 PM" src="https://user-images.githubusercontent.com/103277481/167271230-6815dd45-55c0-4513-936f-2d98894ae594.png">

>Show logging into your ieng6 account after doing this and compiling and running the tests for your repository.
<img width="638" alt="Screen Shot 2022-05-07 at 1 51 00 PM" src="https://user-images.githubusercontent.com/103277481/167271314-0d3e1683-6a3e-4845-bd3d-fa5f3075ec3d.png">

>Show (like in the last step of the first lab) combining `scp`, `;`, and `ssh` to copy the whole directory and run the tests in one line.
<img width="691" alt="Screen Shot 2022-05-07 at 1 47 01 PM" src="https://user-images.githubusercontent.com/103277481/167271179-a625dd04-d184-4656-82d2-96bd21ca670a.png">

>git add
<img width="693" alt="Screen Shot 2022-05-06 at 8 25 51 PM" src="https://user-images.githubusercontent.com/103277481/168670303-de771b6f-330f-444f-be56-f4119c0e9114.png">

>git push
<img width="867" alt="Screen Shot 2022-05-07 at 9 24 57 AM" src="https://user-images.githubusercontent.com/103277481/168670133-6fae181d-1c60-44be-b74a-21eac15ca6db.png">




- **description:** After being able to log in to GitHub through the ieng6 account, now we needed the repository. To do this a similar method for running and compiling was done from lab 1. This was  check if the copy had worked. The entire repo was copied not just invidual files.
