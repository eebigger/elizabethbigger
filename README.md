# Elizabeth Bigger Dot Com

This repository holds the hugo project for your website. 

## Development

### Install tools

Install Hugo via homebrew on macos. You only need to do this once on your system. Note: You should update your hugo to `hugo v0.107.0+extended`

1. Open the terminal
2. install Hugo:
`brew install hugo`

### Clone this repository

### Build the static site

1. Open terminal
2. Navigate in ternminal to where you have this site
3. Run `Hugo`
4. You should see something like:
```
Start building sites … 
hugo v0.107.0+extended darwin/amd64 BuildDate=unknown

                   | EN  
-------------------+-----
  Pages            | 22  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     | 47  
  Processed images |  0  
  Aliases          |  4  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 149 ms
```

### Build and preview

1. Open terminal
2. Navigate in ternminal to where you have this site
3. Run `Hugo Server`
4. You should see something like:
```
Start building sites … 
hugo v0.107.0+extended darwin/amd64 BuildDate=unknown

                   | EN  
-------------------+-----
  Pages            | 22  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     | 47  
  Processed images |  0  
  Aliases          |  4  
  Sitemaps         |  1  
  Cleaned          |  0  

Built in 178 ms
Watching for changes in /Users/luisfraguada/Documents/dev/elizabethbiggerdotcom/{archetypes,content,layouts,static,themes}
Watching for config changes in /Users/luisfraguada/Documents/dev/elizabethbiggerdotcom/config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
5. Open ` http://localhost:1313/` in your browser to see the page update. Note: if you change config.toml, you'll need to press Ctrl+C and run `Hugo Server` again.
6. Your content is in the directory `content`. Update this by chnging the md files in there, or by adding new files. If you want to add images, add them in the `static/images` directory.

### Updating the live site
You can use a terminal for this, or the source control tools in VS Code.

- in VS Code fo to the source control tab
- review changed files and press '+' to stage the changes.
- add a commit message
- press the down button to find 'commit & push'. press that

### [OLD] Updating the live site

For now, this is a manual process of uploading the generated `public` directory to the `luisandelizabeth.net` server.
