.. _Docker: https://www.docker.com/

Tag an EC2 Instance
-------------------

Used to tag an EC2 Instance run as a once-off `Docker`_ service.

Usage:

.. code-block:: yaml
    
    ec2taginstance:
        image: apnarm/ec2-tag-instance
        environment:
            - AWS_ACCESS_KEY=<ACCESS>
            - AWS_SECRET_KEY=<SECRET>
        command: Foo=bar;Bar=foo
