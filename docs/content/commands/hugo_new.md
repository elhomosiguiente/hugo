---
date: 2017-07-16T23:23:14+02:00
title: "hugo new"
slug: hugo_new
url: /commands/hugo_new/
---
## hugo new

Create new content for your site

### Synopsis


Create a new content file and automatically set the date and title.
It will guess which kind of file to create based on the path provided.

You can also specify the kind with `-k KIND`.

If archetypes are provided in your theme or site, they will be used.

```
hugo new [path] [flags]
```

### Options

```
      --editor string   edit new content with this editor, if provided
  -h, --help            help for new
  -k, --kind string     content type to create
  -s, --source string   filesystem path to read files relative from
```

### Options inherited from parent commands

```
      --config string    config file (default is path/config.yaml|json|toml)
      --log              enable Logging
      --logFile string   log File path (if set, logging enabled automatically)
      --quiet            build in quiet mode
  -v, --verbose          verbose output
      --verboseLog       verbose logging
```

### SEE ALSO
* [hugo](/commands/hugo/)	 - hugo builds your site
* [hugo new site](/commands/hugo_new_site/)	 - Create a new site (skeleton)
* [hugo new theme](/commands/hugo_new_theme/)	 - Create a new theme

###### Auto generated by spf13/cobra on 16-Jul-2017
