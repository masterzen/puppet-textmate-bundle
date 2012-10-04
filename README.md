== Puppet TextMate Bundle 

This is a TextMate bundle for 
Puppet (http://www.reductivelabs.com/) manifests.

TextMate 2 is Open Source and available from https://github.com/textmate/textmate.

== Install

TextMate 2:
  git clone git://github.com/mstrauss/puppet-textmate-bundle.git "$HOME/Library/Application Support/TextMate/Managed/Bundles/Puppet.tmbundle"
  
TextMate 1.x.x:
  git clone git://github.com/mstrauss/puppet-textmate-bundle.git  ~/Library/Application\ Support/TextMate/Bundles/Puppet.tmbundle
  osascript -e 'tell app "TextMate" to reload bundles'

== Overview

This bundle supports directly:
 * syntax highlighting of most of the puppet syntax
 * common resources or standard language snippets
 * command to check syntax of manifests (puppet parser validate)
 * function menu containing hierarchical class/nodes/define and resources titles
