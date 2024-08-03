---
layout: post
title:  "Setup Maven Environment "
date:   2024-08-02 13:07:00 -0400
categories: [programming,java]
---
# Adding Maven to Your PATH Environment on macOS

To add Maven to your PATH environment on a MacBook, follow these steps:

## 1. Download Apache Maven

1. Visit the [Apache Maven download page](https://maven.apache.org/download.cgi).
2. Download the binary zip archive for the latest version of Maven.

## 2. Extract the Archive

1. Open your Terminal.
2. Navigate to the directory where the downloaded file is located.
3. Extract the archive using the following command (replace `apache-maven-x.y.z-bin.tar.gz` with the actual file name):

    ```sh
    tar -xvf apache-maven-x.y.z-bin.tar.gz
    ```

## 3. Move the Extracted Directory

Move the extracted directory to a location where you want to keep Maven (e.g., `/usr/local/apache-maven`):

`sudo mv apache-maven-x.y.z /usr/local/apache-maven`

## 4. Set Up Environment Variables

1. Open your profile file in a text editor. Depending on the shell you are using, it could be `~/.bash_profile`, `~/.zshrc`, or `~/.profile`. For example, if you are using zsh (which is the default on macOS Catalina and later):
    `nano ~/.zshrc`
2. Add the following lines to set the M2_HOME environment variable and update the PATH:

    `export M2_HOME=/usr/local/apache-maven`

    `export PATH=$M2_HOME/bin:$PATH`

### 5. Apply the Changes

1. Save the file and exit the text editor (Ctrl+O to save, Ctrl+X to exit).
2. Apply the changes by sourcing the profile file. Again, this depends on the shell you are using:
    `source ~/.zshrc`

### 6. Verify the Installation

Verify that Maven is installed correctly by running:
    
   `mvn -version`

You should see the Maven version and other details displayed.
That's it! Maven should now be successfully added to your PATH environment on your MacBook.