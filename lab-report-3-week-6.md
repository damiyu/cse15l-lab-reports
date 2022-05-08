# Lab Report #3 Weeks 5-6

## Streamlining `ssh` Configuration

![Image](config.png)
After creating my config file, I used Window's Notepad to edit this file so I can add my host information.

![Image](configlog.png)
This is me logging into my remote account.

![Image](configscp.png)
This is me using the `scp` command to copy a png to remote server.

## Setup Github Access from ieng6

![Image](gitpublickey.png)
In my Github settings, I added the public key to Github.

![Image](gitpubpriv.png)
In my user account, my Github public and private keys are stored in the .ssh directory.

![Image](gitpush.png)
This is an image of me using the `add`, `commit`, and `push` commands to my Github account.

[Commit Link](https://github.com/damiyu/cse15l-lab-reports/commit/8d17d9c1f4818b866ae9c906e4eb6f02fc1bf426)



## Copy whole directories with `scp -r`

![Image](scpr.png)
This is the output of the command `scp -r . ieng6:~/markdown-parse`.

![Image](sshtest.png)
This is me logging into my remote account and running the JUnit tests.

![Image](scptop.png)
I combined the `scp` and `ssh` commands to copy my repository to my remote account and then run the tests.
![Image](scpbottom.png)
This is a screenshot of the JUnit tests running after the files are copied.
