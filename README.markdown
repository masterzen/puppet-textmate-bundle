# Puppet TextMate Bundle

This is a TextMate bundle (http://www.macromates.com/) for 
Puppet manifests (http://www.puppetlabs.com/).

TextMate 2 is Open Source and available from (http://github.com/textmate/textmate).

(It may work for Sublime Edit 2)

## Install
To install, clone this repository, rename it to puppet-textmate.tmbundle, and drag the puppet-textmate.tmbundle directory
on the TextMate icon. The installation will then be automatic.

## Overview
###This bundle directly supports :

   * syntax highlighting of most of the puppet syntax
   * common resources or standard language snippets
   * command to check syntax of manifests (puppet parser validate) with ctrl-shift-v 
   * function menu containing hierarchical class/nodes/define and resources titles
   * validates puppet on save with puppet-lint **
   * validates all puppet in project with ctrl+option+v **

To use last two features you need to have puppet-lint installed, on the command-line. To install it, type on your terminal:

    sudo gem install puppet-lint puppet


#### Other standard textmate functions that are handy for writing puppet code:
	
   * command+option+] aligns the current set of assignments (=>)
   * ctrl-shift-' switches from a single quote to double quote and back.
