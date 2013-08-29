## Swig Snippets for Sublime Text 2

Nothing special, just a few most popular [Swig](http://paularmstrong.github.io/swig/docs/tags/) tags ready to use with Sublime Text 2.

Snippets are global, so you can use them in whatever filetype you like.

What's Swig?
------------
[Swig](https://github.com/paularmstrong/swig/) is an awesome, Django/Jinja-like template engine for node.js.

Please check Swig [Repository](https://github.com/paularmstrong/swig/) & [Documentation](http://paularmstrong.github.io/swig/docs/).

Installing
----------

#### With Git
Navigate to your Sublime Text 2 user packages directory:

    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/

And clone the repo to a new directory right then and there:

    git clone git@github.com/kepek/Swig-Snippet-for-Sublime-Text-2.git

#### Manually
* Download the .zip file from the GitHub downloads modal
* Unzip the files and rename the folder to "swig-snippets"
* Copy the folder to your Sublime Text 2 user packagers directory:
    - `(~/Library/Application Support/Sublime Text 2/Packages/User/)`


Bugs & Additions
----------------

Have a bug or want to add something? Please create an issue or a pull request right here.

Usage
------------
Write one of this words below and press ``tab``.

    %autoescape
    %block
    %else
    %elif
    %extends
    %filter
    %for
    %if
    %include
    %macro
    %parent
    %raw
    
Example
------------
``%block`` + ``tab``

#### Result:

    {% block content %}
      My Content
    {% endblock %}

Supported Tags
----------
* [autoescape](http://paularmstrong.github.io/swig/docs/tags/#autoescape)
* [block](http://paularmstrong.github.io/swig/docs/tags/#block)
* [else](http://paularmstrong.github.io/swig/docs/tags/#else)
* [elif](http://paularmstrong.github.io/swig/docs/tags/#elif)
* [extends](http://paularmstrong.github.io/swig/docs/tags/#extends)
* [filter](http://paularmstrong.github.io/swig/docs/tags/#filter)
* [for](http://paularmstrong.github.io/swig/docs/tags/#for)
* [if](http://paularmstrong.github.io/swig/docs/tags/#if)
* [include](http://paularmstrong.github.io/swig/docs/tags/#include)
* [macro](http://paularmstrong.github.io/swig/docs/tags/#macro)
* [parent](http://paularmstrong.github.io/swig/docs/tags/#parent)
* [raw](http://paularmstrong.github.io/swig/docs/tags/#raw)

License
------------
Cheers!
