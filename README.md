Deploy **[Brave Bucks](https://github.com/bravecollective/brave-bucks)** to AWS Beanstalk.

Create:
```
$ eb init
    choose platform Corretto 8
$ eb create --single -i t3a.micro
```
Then add environment variables.

Update:
```
$ eb deploy
```
