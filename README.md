Simple Spray.io on Heroky POC
-----------------------------------
 * Project based on: Spray-Workshop https://github.com/spray/spray-workshop
 * Added sbt-start-script https://github.com/sbt/sbt-start-script to create a start script.

Running the project
-----------------------------------
 * Install sbt 0.13.0
 * Install heroku toolbelt

 * Locally using sbt `sbt re-start`
 * Locally using foreman `sbt clean compile stage` and then `foreman start`
 * On [Heroku](https://devcenter.heroku.com/articles/getting-started-with-scala)
```sh
 heroku login
 heroku create
 git push heroku master
 heroku ps:scale web=1
 heroku open
```


