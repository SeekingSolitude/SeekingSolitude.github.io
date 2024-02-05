# OneQuantumPH Product Engineering Assignment

### Technologies used

-**Jekyll**: [4.3.3]

-**Github Pages**


### How to Deploy the Website

- **Step 1**: Clone this repository 

- **Step 2**: Cd into the project folder

- **Step 3**: Install Jekyll and dependencies by running the following commands:
    ```bash
    $ gem install bundler
    $ bundle install
    ```
- **Step 4**: Run 
    ```bash
    $ bundle exec jekyll serve
    ```


### Challenges Faced in Development

This was actually my first time using Jekyll and deploying a website through Github pages, so I encountered a few challenges while developing this, which I'll be listing down here.

1. **Website works on local server, but shows up as html in github pages**
    - I fixed this through switching the branch to `gh-pages` and committing the Jekyll build files to that branch.

2. **When running `bundle exec jekyll serve`, "LoadError: cannot load such file -- json"**
    - I fixed this through adding `gem "json", "json version"` in the Gemfile.