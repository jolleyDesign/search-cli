# search-cli
Command line tool for searching the web.
Opens search results in your system's default web browser.

TODO: add arguments for opening in alternate browsers. 

## Installation
Download the script: 
```
curl -o search https://raw.githubusercontent.com/jolleydesign/search-cli/main/search
```

Make it executable:
```
chmod +x search
```

Move to your PATH:

#### Linux / macOS (BASH or ZSH)
```
sudo mv search /usr/local/bin/
```

#### Windows (WSL, Git Bash)
```
mkdir -p ~/bin
mv search ~/bin/
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc`
```

## Usage
```
search --options "your search query"
```
or
```
search --options raw search query
```

#### Arguments
| Argument      | Description      |
| ------------- | ------------- |
| `-h, --help` | Shows the help message |
| `-g, --google` | Searches using Google (default) |
| `-d, --duck` | Searches using DuckDuckGo |
| `-b, --bing` | searches using Bing |

# Reccomendations
I reccomend setting an alias in your shell to shorten the `search` keyword, if you use this tool often.
