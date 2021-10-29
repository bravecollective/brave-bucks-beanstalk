Deploy **[Brave Bucks](https://github.com/bravecollective/brave-bucks)** to AWS Beanstalk.

Create:
```
$ eb init
    choose platform Corretto 8
$ eb create --single -i t3a.micro
```

Then add environment variables, use port 5000.

Update:
```
$ eb deploy
```
