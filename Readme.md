# RubyMotion Templates
A set of template folders for [RubyMotion](http://www.rubymotion.com) 2.0+

Rubymotion 2.0 introduced the concept of "templates" to create pre-configured development startingpoints. This repository is meant to be a place for people to share their custom templates in hopes that others will be able to get up and running quicker with RubyMotion development.

## How To use

1. Clone the repository to the RubyMotion local templates directory with `git clone git@github.com:markrickert/rubymotion-templates.git ~/Library/RubyMotion/templates`
2. Create your project with a new template! `motion create --template=ProMotion` (the template name is the name of the template folder)

## How to contribute

1. Fork the repository
2. Add your template or fix an existing template
3. Generate a project with the template and run `bundle && rake` to make sure the template compiles. I will not merge templates that do not compile as blank projects.
4. Send me a pull request