# Starting an Open Source Project

## What does “open source” mean?
When a project is open source, that means anybody can view, use, modify, and distribute your project for any purpose. These permissions are enforced through an open source license.

To understand how it works, imagine your friend is having a potluck, and you bring a cherry pie.
* Everybody tries the pie (use)
* The pie is a hit! They ask you for the recipe, which you provide (view)
* One friend, Alex, who’s a pastry chef, suggests reducing the sugar (modify)
* Another friend, Lisa, asks to use it for a dinner next week (distribute)

## Why do people open source their work?
* Collaboration: Open source projects can accept changes from anybody in the world. Exercism, for example, is a programming exercise platform with over 350 contributors.
* Adoption and remixing: Open source projects can be used by anyone for nearly any purpose. People can even use it to build other things. WordPress, for example, started as a fork of an existing project called b2.
* Transparency: Anyone can inspect an open source project for errors or inconsistencies. Transparency matters to governments like Bulgaria or the United States, regulated industries like banking or healthcare, and security software like Let’s Encrypt.

## Does open source mean “free of charge”?
One of open source’s biggest draws is that it does not cost money. “Free of charge”, however, is a byproduct of open source’s overall value.

## Launching your own open source project
Generally speaking, you should open source your project when you feel comfortable having others view, and give feedback on, your work.

No matter which stage you decide to open source your project, every project should include the following documentation:

* [Open source license](https://help.github.com/articles/licensing-a-repository/)

An open source license guarantees that others can use, copy, modify, and contribute back to your project without repercussions. It also protects you from sticky legal situations. You must include a license when you launch an open source project.
  
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
  * What does this project do?
  * Why is this project useful?
  * How do I get started?
  * Where can I get more help, if I need it?
  
For more inspiration, try using [@PurpleBooth’s](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) README template to write a complete README.

* [Contributing guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)

A CONTRIBUTING file tells your audience how to participate in your project. For example, you might include information on:
    * How to file a bug report (try using issue and pull request templates)
    * How to suggest a new feature
    * How to set up your environment and run tests
    
In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions, such as:
    * The types of contributions you’re looking for
    * Your roadmap or vision for the project
    * How contributors should (or should not) get in touch with you
    
* [Code of conduct](https://github.com/FOSS-UCSC/FossCody-1.0/edit/master/Sample_Project_Guide.md)

Finally, a code of conduct helps set ground rules for behavior for your project’s participants. This is especially valuable if you’re launching an open source project for a community or company

## Naming and branding your project
Pick a name that is easy to remember and, ideally, gives some idea of what the project does.

## You did it!
Congratulations on open sourcing your first project. No matter the outcome, working in public is a gift to the community. With every commit, comment, and pull request, you’re creating opportunities for yourself and for others to learn and grow.


Sample Twitter bot Guide 
===================================

![Tweetin'](https://cdn.gomix.com/4032b241-bff8-473e-aa6b-eb0c92a4bd06%2Ftweeting.gif)

This is a template for making fun Twitter bots with [Glitch](https://glitch.com/) and the [Twit](https://github.com/ttezel/twit) node.js library. For a bit more advanced version of this starter project see [twitterbot-advanced](https://glitch.com/edit/#!/twitterbot-advanced).

## A quick tutorial

1. Create a new Twitter account and a new Twitter app. ([See how.](https://botwiki.org/tutorials/how-to-create-a-twitter-app/))
2. Update the `.env` file with your Twitter API key/secrets and change the `BOT_ENDPOINT` (it could just be random letters).
3. Update `server.js` with some cool Twitter bot code. (Make sure your bot follows [Twitter's rules](https://support.twitter.com/articles/18311-the-twitter-rules) and is overall [not a jerk](https://botwiki.org/articles/essays/).)
4. Set up a free service ([cron-job.org](https://cron-job.org/en/), [Uptime Robot](https://uptimerobot.com/), or [a similar one](https://www.google.com/search?q=free+web+cron)) to wake up your bot [every 25+ minutes](https://support.glitch.com/t/a-simple-twitter-bot-template/747/16) and tweet. Use `https://YOUR_PROJECT_NAME.glitch.me/BOT_ENDPOINT` as a URL to which to send the HTTP request.

The included example tweets out "hello world 👋". Check out [the Twit module documentation](https://github.com/ttezel/twit) for more examples of what your bot can do.

You can find more tutorials and open source Twitter bots on [Botwiki](https://botwiki.org). Be sure to [join Botmakers](https://botmakers.org/) and [submit your bot to Botwiki](https://botwiki.org/submit-your-bot) :-)

## More starter projects

For more bot starter projects on Glitch, check out the official [Botwiki page on Glitch](https://glitch.com/botwiki).

## Support Botwiki/Botmakers

- [patreon.com/botwiki](https://patreon.com/botwiki)
- [botwiki.org/about/support-us](https://botwiki.org/about/support-us)

🙇

