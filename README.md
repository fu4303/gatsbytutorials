# Gatsby Tutorials

Gatsby Tutorials is a website where you can find all of the GatsbyJS tutorials that are available online.

Hope it helps!

Website: https://www.gatsbytutorials.com

## How do I add a tutorial?

1. Add it to `src/data/tutorials.yml
2. Submit a pull request.

Please follow this example's format and indentation:

```yaml
- title: 'GatsbyJS: How to Create the Fastest Sites in the World'
  link: https://www.youtube.com/watch?v=Gtd-Ht-D0sg
  format: video
  date: 2017-10-01
  length: '24:52'
  author: Kyle Mathews
  source: ReactNext 2017
  topics:
    - performance
```

- `title` - Title of tutorial (string, required)
- `link` - Working URL for tutorial (string, required)
- `format` - Media format of tutorial (string: 'video', 'audio' or 'text', required)
- `date` - Publishing date (e.g. 2017-10-01)
- `length` - Length of tutorial, if applicable (string)
- `author` - Name of author or speaker (string)
- `source` - Name of YouTube channel, podcast, conference, blog, etc. (string)
- `topics` - Array of topics covered by the tutorial (array of strings, optional)