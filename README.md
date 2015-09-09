Tag an EC2 Instance
===================

Used to tag an EC2 Instance run as a once-off [Docker](https://www.docker.com/) service.

Usage:

``` sourceCode
ec2taginstance:
    image: apnarm/ec2-tag-instance
    environment:
        - AWS_ACCESS_KEY=<ACCESS>
        - AWS_SECRET_KEY=<SECRET>
    command: Foo=bar;Bar=foo
```
