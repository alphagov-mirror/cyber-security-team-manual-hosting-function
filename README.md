# firebreak-q1-faas

Just run this to build and deploy:
``` shell
make
```

To make a target zip

``` shell
make zip
```

To Deploy

``` shell
make deploy
```

To run the tests

``` shell
tox
```

To Deploy
Assume your STS Credentials

``` shell
cd terraform/firebreak-q1-event-normalisation/
terraform init
terraform apply
```
