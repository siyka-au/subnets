# subnets
Visual subnet calculator as seen at https://ashy-pond-04b29a610.1.azurestaticapps.net/subnets.html

Original example online by David C. is at http://www.davidc.net/sites/default/subnets/subnets.html

# Run with docker

```
cd <project folder>
docker build . -t subnets
docker run -d -p 5001:80 --name subnets subnets
```

# Additional work

This repository is also tracking the great work of Yehuda Katz who has provided IPv6 support which is of great interest to me. You can find his fork at https://github.com/yakatz/subnets.
