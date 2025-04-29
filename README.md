# hwebify

## Motivation:
This is an idea, an attempt, to help with one's own local
documentation creation and its consumption/navigation.


It starts from the following seemingly trivial observations:
 1. Our text editors are the best tools for editing texts.
      So I don't edit text inside a browser.
 2. Our browsers are the best tools to browse content.
      So I don't read/browse content inside a text editor.
 3. I am much more interested in typing content rather than the layout.

And with our tool here, we do exactly that:
We type our own documentation with our editor.
Then, we run hwebify to generate locally browsable copies.
And finally, we use our browser to read our documentation.


## What hwebify does:
Hwebify parses a given folder on your local computer,
and generates next to it a mirrored directory tree containing
only the text files rendered more easily browsable with
your preferred browser.


## Usage:
1. cd "above" the directory ('theTargetDirName') you are interested
to generate a browsable copy of.

2. Launch the command:
$ path/To/Your/binary/hwebify theTargetDirName



A lot of things can be improved of course.
We will see if the idea is interesting enough
to continue improving this tool.

This project provides us with an opportunity
to practice the Haskell programming language.

Thanks for your interest.

PBL.

www.pointblanklogic.com

