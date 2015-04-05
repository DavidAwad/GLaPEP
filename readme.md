# GLaPEP8

This is my fork of the [HackNY Spring 2015 Hackathon winner!](http://challengepost.com/software/glapep8)

It's very easy to ignore the minor violations of PEP8 style when the existing tools inform you about problems in such a friendly manner. GLaDOS has no time for your laziness.

This is a terminal program that will open up any file you specify and mock the errors you make by generating insults and reading them in the voice of GLaDOS from portal. 

## Installation

GLaPEP8 only works on OS X, because it makes use of the 'say' command. 

```shell
pip install -r requirements.txt

brew install jp2a

``` 

## Usage

./GLaPEP8.py wrong.py


### Pictures

Pictures in the directory 'pics/' will be displayed in the lower-right pane. Files with the extension '.jpg' are converted to ASCII art by jp2a, files with the extension '.ascii' are displayed as-is. You might consider using a HackNY or an Aperture Science logo.

## Contributors
### Adam Obeng who first built this at HackNY. 
