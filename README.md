# transcripts.io.src

[transcripts.io](http://transcripts.io) hosts beautiful, searchable, conversational transcripts. [transcripts.io](http://transcripts.io) is **auto-generated** by the `.transcript` text files in this repo.

For example, [tim_ferriss_show/2015-12-14-derek-sivers.transcript](https://github.com/jonmbake/transcripts.io.src/blob/master/tim_ferriss_show/2015-12-14-derek-sivers.transcript) was auto-generated into  https://www.transcripts.io/transcripts/tim_ferriss_show/2015/12/14/derek-sivers.html on commit.

Feel free to contribute!

## Why transcripts.io

Transcribing audio is hard work.  Like most things in life, when done as a group it becomes much easier.  The idea behind [transcripts.io](http://transcripts.io) is that, by working together, we can create **quality** transcriptions that can be enjoyed by many.

The value of transcribed audio is immense. For example, you can do things like search for something you previously heard and jump right to that position within the audio.

## How to Contribute

Right now this idea is being tested out on a single Podcast, [The Tim Ferriss Show](http://fourhourworkweek.com/podcast/) (one of my personal favorites).  If you would like to contribute, there are a couple of ways:

1. Transcribing new content.
2. Making corrections to an existing transcript.  (Next to each blurb is a link to make corrections, which when clicked will jump to position within the transcript source)

## Contribution Details

Transcription are formatted using a slightly "enhanced" version of [Markdown](https://daringfireball.net/projects/markdown/).  The only enhancement is the `!#` element is added to indicate change of speaker.

*transcripts.io* uses [Jekyll](https://jekyllrb.com/) to generate the transcript HTML so a bit of [YAML Front Matter](http://jekyllrb.com/docs/frontmatter/) is also necessary.  There is also some metadata data needed by the transcript generator, such as speaker information. Check out [2014-04-22-josh-waitzkin.transcript](https://github.com/jonmbake/transcripts.io.src/blob/master/tim_ferriss_show/2014-04-22-josh-waitzkin.transcript) for an example transcript.
