# section-summarization-tool
Script to summarise a section in a wiki page. 

# How to use it: 
1. Copy `script.js` to your `username/common.js`. or alternatively, load it using: 
```
mw.loader.load('https://cdn.jsdelivr.net/gh/tonythomas01/section-summarization-tool@main/script.js', 'text/javascript');
```
or load it with Greasemonkey or a similar tool from https://greasyfork.org/en/scripts/466717-wikipedia-chatgpt-section-summaries
1. Create an OpenAI Key using: [OpenAI API key](https://platform.openai.com/account/api-keys)
1. Click on the `summarize` button next to `[edit]` near the section header. When doing it for the first time, provide the API key.
1. As of now, the output is only available as a `console.log`
