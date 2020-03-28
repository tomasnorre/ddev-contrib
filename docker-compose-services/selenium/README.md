# Selenium in DDEV  

Running selenium for e.g Codeception tests can be quite handy.

To include this to your own project you can do following:

```
$ cp docker-compose.selenium.yaml /path/to/your/project/.ddev/docker-composer.selenium.yaml
$ cd /path/to/your/project/
$ ddev start # or ddev restart (depending on the state of the project)
```

Now you have a selenium with a chrome headless browser node running in your ddev project.

To see how to use it with Codeception, you can take a loot at (https://dev.to/tomasnorre/codeception-ddev-selenium-docker-36kk)[https://dev.to/tomasnorre/codeception-ddev-selenium-docker-36kk]