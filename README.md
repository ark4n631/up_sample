## Setup

You require to have installed up [apex/up](https://github.com/apex/up)

The you can clone the project:

```sh
git clone git@github.com:ark4n631/up_sample.git
cd up_sample
up
```

Then you will be able to get the URL for the result.


** Sidenote: i had some troubles related with env variables using ubuntu 18.04.4 you should check out this issue [up#426](https://github.com/apex/apex/issues/426#issuecomment-344885139) **

So you have to make sure these variables are available to the env (complete with your IAM values):

```sh
export AWS_ACCESS_KEY_ID=;export AWS_SECRET_ACCESS_KEY=;export AWS_REGION=;
```

