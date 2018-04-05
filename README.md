# tombot

tombot is a chat bot built on the [Hubot][hubot] framework. It was
initially generated by [generator-hubot][generator-hubot], and configured to be
deployed on [Heroku][heroku] to get you up and running as quick as possible.

This README is intended to help get you started. Definitely update and improve
to talk about your own instance, how to use and deploy, what functionality he
has, etc!

[heroku]: http://www.heroku.com
[hubot]: http://hubot.github.com
[generator-hubot]: https://github.com/github/generator-hubot

### Running tombot Locally

You can test your hubot by running the following, however some plugins will not
behave as expected unless the [environment variables](#configuration) they rely
upon have been set.

You can start tombot locally by running:

    % bin/hubot

You'll see some start up output and a prompt:

    [Sat Feb 28 2015 12:38:27 GMT+0000 (GMT)] INFO Using default redis on localhost:6379
    tombot>

Then you can interact with tombot by typing `tombot help`.

    tombot> tombot help
    tombot animate me <query> - The same thing as `image me`, except adds [snip]
    tombot help - Displays all of the help commands that tombot knows about.
    ...

### Running MongoDB locally

The easiest way to do this is with docker. Run, `docker run -d -p 27017:27017 mongo` to start one.

### Scripting

For many common tasks, there's a good chance someone has already one to do just
the thing.

[scripting-docs]: https://github.com/github/hubot/blob/master/docs/scripting.md

## Restart the bot

You may want to get comfortable with `heroku logs` and `heroku restart` if
you're having issues.
