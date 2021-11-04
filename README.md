# Hugocast

### Introduct

A podcasting tool based on hugo, you can use this hugo theme to build your own Podcast server.

### How to use

1. Download this theme to your hugo themes folder.

2. Move `config.toml` to your hugo root directory, and configure it.

	```
	baseURL = "http://domain.com" # Your domain
	title = "Podcast title" # Your podcast title
	copyright = "Domain.com" # Your copyright information
	theme = "hugocast" # Do nothing
	disableKinds = ["sitemap"] # Do nothing

	[params]
	  defaultContentLanguage = "en-US" # Your podcast default language
	  startyear = "2020" # Start year
	  author = "Bin Hua" # Your name
	  email = "forhua@gmail.com" # Your email address
	  description = "This is my podcast" # Your podcast description
	  explicit = true # True or false
	  podcastlogo = "podcastlogo.png" # Your podcast logo
	  itunecategory = ["Comedy","Technology","Arts"] # Your podcast category, check the category, https://podcasts.apple.com/us/genre/podcasts/id26

	[taxonomies]
	  tag = "" # Do nothing
	  group = "" # Do nothing
	  category = "" # Do nothing
	```

3. Put your static files (Audio files / images) in the `static` of the hugo root directory.

4. Create a podcast like blogging with hugo, and upload the public folder to your server, done.

### Tips

Different podcast platforms have different requirements, such as the size of the logo, etc. You need to carefully check the requirements of each platform. This is in line with the requirements of several platforms such as Apple podcasts.

### How to Collaborate

Please feel free to submit your PR or issue.

### License

[MIT](LICENSE)

Copyright (C) 2020-present, Bin Hua 
