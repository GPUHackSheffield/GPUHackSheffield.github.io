# http://gpuhack.shef.ac.uk
Sheffield GPU Hackahthon event website


## Installation

1. Install ruby
    * On Windows, this installer can be used [https://rubyinstaller.org/](https://rubyinstaller.org/)
    * On Linux, follow the instructions according to your distribution e.g. for Debian/Ubuntu:
        ```
        sudo apt install ruby-full
        ```
1. In the terminal, install the rest of the required packages: 
   ```
   gem install bundler jekyll 
   ``` 
1. Go to the root directory of this site and run
    ```
    bundler install 
    ```

Note, if you get an error related to the `public_suffix` package, try installing and updating bundler before rebuilding the site:

```
gem install public_suffix --version 3.0.3
bundler update
```



## Building and previewing the site

* Run the following command to build the site and serve it up on a local server:
    ```
    bundler exec jekyll serve
    ```
* The website can then be found at `http://127.0.0.1:4000`
