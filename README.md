
js-beautify-v8
==============

It's a faster js beautifier Textmate bundler.

PS: this bundle need the "jsbeautify" command. It's compiled application from http://jsbeautifier.org/ with V8 engine.

Install
=======

1. First: install v8.

PS: I used v8 homebrew Formula.

2. Compile the jsbeautify command..

See:
http://www.sencha.com/blog/2010/10/21/make-a-javascript-formatter-with-v8-and-jsbeautifier/#comment-126884

..or use my homebrew formula (I'm trying submit to oficial repository)

brew install http://github.com/jlbfalcao/homebrew/raw/a10a73e0f54c21aa38329cdfe0f2f8e331aa3712/Library/Formula/jsbeautify.rb

3. Just clone the bundle to your Textmate bundlers directory.

    cd ~/Library/Application\ Support/TextMate/Bundles/;
    git clone git://github.com/jlbfalcao/js-beautify-v8.tmbundle.git;
    osascript -e 'tell app "TextMate" to reload bundles';

Keyboard shortcut
=================

	⌘ + Shift + F 

