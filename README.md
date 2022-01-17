# ECLAIR Website
This is the GitHub repository containing the code for the UT ECLAIR website. This website was created using the HUGO static site generator and  

## Installing Dependencies
If you are on Windows, you must run the website on Windows Subsystem for Linux (WSL). The only dependency you need is HUGO static site generator which you can install with

```bash=
sudo apt-get install hugo
```
## Running the Website Locally

After cloning the directory, you can host the web server locally by running the command `hugo server` in the root directory of the cloned repository.   

## Deploying the Code to GitHub Pages

In order to deploy the code to Github Pages, you just need to run the command `hugo` in the root direcory of the clone repository. This will make HUGO generate the necessary HTML files that GitHub pages needs in the `docs` directory. If you ever need to change the output directory, it is set in the `config.toml` file as `publicDir`.
