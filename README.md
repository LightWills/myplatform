# myplatform
README test
### Install

For running the tests with mocha

Go on **[mocha](https://github.com/mochajs/mocha)** and follow the instructions.

To test your installation, try the next command:
```
 docker build -t docker-whale -f ./myplatform/Dockerfile.test .
 ```
and 
```
  docker run --rm docker-whale
 ```
> The *-rm* flag is using to automatically delete the test container after the test finished because
we don't need the test container anymore.
