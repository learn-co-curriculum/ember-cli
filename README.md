# Ember CLI

##Objectives

1. Understand what the Ember CLI is
2. Understand how to use it
3. Identify common Ember CLI commands

## Overview
You may recall that CLI is short for Command Line Interface - a program you run by typing commands from your command line. Ember, of course, is a front end JS framework for creating web apps. The people over at Ember wanted to create a CLI to help get your Ember app up and running, and the Ember CLI was born. Ember CLI is key part of Ember as of Ember version 2.0.

You'll use the CLI extensively throughout your project's development. You'll generate boilerplate code, spin up a server, and run your tests all with the Ember CLI. It will be a valuable tool throughout the development of your Ember app.

## Getting Started
Getting started should be pretty straight forward. Run this command in your terminal:
####`npm install ember-cli -g`
Run `ember -v` to see that it installed and to check what version you have.

It's as simple as that. 

If that didn't work, you may need to install Node ([See the Ember Installation Guides](http://guides.emberjs.com/v2.1.0/getting-started/))

## Basic Ember CLI commands
###`ember -v`
Tells you the version of Ember you have. There is a notable difference between Ember 2.x and Ember 1.x. Our tutorials will be using Ember 2.x.

###`ember new your-app-name` || `ember init`
It's as easy as either one of these commands to get started with all the boilerplate code necessary for a new Ember app. Run `ember new your-app-name` if you want to create a new directory. Run `ember init` if you want to create an Ember app in the directory you're currently in.

###`ember serve`
This is how spin up a server. By default it runs at: `http://localhost:4200/`

###`ember generate route your-route-path`
Ember has several generator commands. For now we will stick with routes since these are very important in any Ember app. The generate command can also be used for models and components. 

###`ember destroy route your-route-path`
If you make a mistake, it is simple to remove the files/code you just generated. Run the exact same command that you generated the code with, and just swap out the `generate` for `destroy`.

###`ember test`
This command will run all of the tests