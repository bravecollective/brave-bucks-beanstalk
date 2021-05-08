Deploy **Brave Bucks** Docker container to AWS Beanstalk.

https://hub.docker.com/r/bravecollective/brave-bucks

Create:
```
$ eb init
    choose platform Docker
$ eb create --single -i t3a.micro
```
Then add environment variables.


Update:
```
$ eb deploy
```
