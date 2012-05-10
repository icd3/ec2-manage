To use this script, you'll need to have **boto** AWS Python tools installed: https://github.com/boto/boto `pip install -U boto`

config.json should be in the following format:

    {
      "addresses" : {
        "domain0"  : "xxx.xxx.xxx.xxx"
      },
      "instances" : {
        "name0"  : "i-xxxxxxxx",
        "name1"  : "i-xxxxxxxx"
      },
      "sizes" : {
        "micro" : "t1.micro",
        "small" : "m1.small"
      }
    }

