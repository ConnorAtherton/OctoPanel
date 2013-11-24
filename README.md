OctoPanel
=========

This theme is heavily influenced by the beautiful [Medium](https://medium.com) layout.

Please create an issue on Github if you have any problems or requests for the theme.

If you are using this theme on your site then please post the link [on the wiki](https://github.com/ConnorAtherton/OctoPanel/wiki/All-sites-using-this-theme).

## Installation instructions

Open your terminal and type

1. `$ cd octopress-blog`
2. `$ git clone git://github.com/ConnorAtherton/OctoPanel.git .themes/OctoPanel`
3. Copy `gravatar.rb` to your `plugins` directory.
4. Update your `_config.yml` file to include a `gravatar_email` variable.

	```
	# Gravatar
	gravatar_email: youraddress@example.com
	```

5. `$ rake install['OctoPanel']`
6. `$ rake generate`
