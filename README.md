# mut8

This is an yi jing app. For me, it's mainly a way to learn some things. 

## Requirements

### Stage 0
- Show all 64 hexagrams in a mobile app with commentary.
- Show the progression of the hexagrams.
- Descriptions and commentary should be available in English and the original
  Chinese.

### Stage 1
- Add a feature for throwing. 
- Add community translations to other languages.
- Make it accessible in webpage form.

### Stage 2
- Give users the opportunity to submit their own interpretations of the
  original Chinese.

## Strategy

I want to build this with [lapis](https://github.com/leafo/lapis/) and
[hyperview](https://hyperview.org/) in order to learn both. I'm open to trying
other stuff, though, including dotnet if you think it's prudent.

Most of the structural requirements are simple here. The only things that could
be a big footgun in the future, if not approached correctly, are the
translations and the suggestions. Let's think through those before we get to
the point where recreating the entire app from scratch would take more than 500
hours of work.
