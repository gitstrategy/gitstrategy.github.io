# gitstrategy.github.io
A personal site from Gitstrategy by CodeDaddy

Setting up a GitHub Pages site using a **Jekyll** theme is straightforward. Here are the steps to guide you through the process:

**Prerequisites**

**GitHub Account:**    
Ensure you have a GitHub account. If not, [sign up here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).
Git Installed: Make sure Git is installed on your computer. You can download it from [git-scm.com](https://git-scm.com).

**Step 1**: Create a New Repository
Go to [GitHub](https://github.com) and log in.
Click the New button or go to https://github.com/new to create a new repository.
Name your repository *<your-username>.github.io*. This specific naming convention is required for GitHub Pages.
* Optionally, add a description.
* Select Public.
* Check the box to initialize the repository with a README file.
* Click Create repository.

**Step 2**: Clone the Repository Locally
Open a terminal or command prompt.
Clone the repository to your local machine:

`git clone https://github.com/<your-username>/<your-username>.github.io`

Navigate into the cloned directory:

`cd <your-username>.github.io`


**Step 3**: Install Jekyll
Install Ruby: Jekyll requires Ruby. Follow the official Ruby installation guide for your operating system. *OR follow steps in the below part.* 

Install Jekyll and Bundler: Run the following command:

`gem install jekyll bundler`

**Step 4**: Create a New Jekyll Site
Inside your repository directory, create a new Jekyll site:

`jekyll new .`

This command creates a new Jekyll site in the current directory.

**Step 5**: Configure Your Site
Open the *_config.yml* file in a text editor.
Customize your site settings such as title, description, and URL.

**Step 6**: Add a Jekyll Theme
- Choose a theme from the Jekyll Themes website.
- Add the theme to your *_config.yml* file. For example, to use the minima theme:

`theme: minima`

- Install the theme and dependencies:

`bundle install`

**Step 7**: Build and Preview Your Site Locally
- Build and serve your site locally to see the changes:

`bundle exec jekyll serve`

Open http://localhost:4000 in your web browser to preview your site.

**Step 8**: Commit and Push Changes to GitHub
- Stage all changes:

`git add .`

Commit the changes:

`git commit -m "Initial commit with Jekyll site"`

- Push the changes to GitHub:

`git push origin main`

**Step 9**: Enable GitHub Pages
- Go to your repository on GitHub.
- Click on **Settings**.
- Scroll down to the *GitHub Pages* section.
- Under Source, select the main branch and click **Save**.
- Your site should be live at *https://<your-username>.github.io* after a few moments.

**Step 10**: Customize Your Site Further
- Add new posts in the *_posts* directory.
- Customize the *_config.yml* file and CSS files for additional personalization.
Install plugins if needed by adding them to the *_config.yml* file and running bundle install.

**Here are the steps to install Ruby on a Mac:**

**Step 1**: Install Homebrew
Homebrew is a package manager for macOS that makes it easy to install and manage software.

Open Terminal.
Install Homebrew by pasting the following command and pressing Enter:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Follow the on-screen instructions to complete the installation. You might be asked to enter your password.

**Step 2**: Install rbenv and ruby-build
rbenv is a tool that lets you install and manage different versions of Ruby.

Install rbenv and ruby-build using Homebrew:

`brew install rbenv ruby-build`

Add rbenv to your shell to enable shims and autocompletion:

`echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.zshrc`

If you are using a shell other than Zsh (e.g., Bash), replace ~/.zshrc with ~/.bash_profile or the appropriate file for your shell.
Reload your shell:

`source ~/.zshrc`

Step 3: Install Ruby
List all available Ruby versions:

`rbenv install -l`

Install the latest stable version of Ruby (replace x.x.x with the desired version, for example, 3.1.2):

`rbenv install 3.1.2`
Set the global Ruby version to the one you installed:

`rbenv global 3.1.2`
Verify the installation:

`ruby -v`

This command should display the version of Ruby you just installed.

**Step 4**: Install Bundler
Bundler is a tool for managing Ruby gem dependencies.

Install Bundler:

`gem install bundler`
Rehash rbenv to make the Bundler executable available:

`rbenv rehash`

Additional Tips

Updating Homebrew: Before installing or upgrading packages, it's a good idea to update Homebrew:

`brew update`

Installing Gems: To install a Ruby gem, use:

`gem install <gem_name>`

Managing Ruby Versions: If you need to switch between different Ruby versions, you can use rbenv:

`rbenv install <version>`

`rbenv global <version>`
