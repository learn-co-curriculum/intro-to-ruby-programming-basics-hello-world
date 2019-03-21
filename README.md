# Introduction to Intro to Programming

## Learning Goals

- Create a new Ruby file from scratch
- Write syntactically valid code to produce "Hello World!"
- Run a Ruby file

## Introduction

![Hello World! Art](https://d32dm0rphc51dk.cloudfront.net/b6JQ66-0nHij79irJT-Pdg/large.jpg)

Hello World is based on a 1974 Bell Laboratories internal memorandum by Brian
Kernighan called Programming in C: A Tutorial, which contains the first known
version of this program. Since then, it has become a common first step into
learning a programming language.

Now, its time for us to do the same. Let's create a program that will print
["Hello World!"][hello] to your terminal!

## Create a New Ruby File From Scratch

To get started, we first need to create a Ruby file to contain our code. We will
call it `hello_world.rb`.

The `.rb` at the end is a filename extension. [Filename extensions][filenames]
are a common convention for specifying the files intended use. We use the `.rb`
file extension to indicate that this file contains Ruby code and needs a Ruby
interpreter to run.

To create a file named `hello_world.rb`, in the command line, type `touch
hello_world.rb` (or, if you are using the Learn IDE, you can use the "Create
New" or "New File" options in the Editor). If that worked as expected, you
should now see the file appear in the main directory of this lesson. Open this
file to start editing it.

## Write Valid Code to Produce "Hello World!"

In the file `hello_world.rb` that you created, you will need to write a single
line of code that prints the `String` "Hello World!" to your terminal.

To print in Ruby, you use the method `puts`. Since "Hello World!" is a string,
you need to surround your text with `""`. Otherwise, `Hello` and `World!` will
be treated as undefined barewords when we run the file, causing an error.

File:

```sh
hello_world.rb
```

Code:

```ruby
puts "Hello World!"
```

## Run a Ruby file

Execute this file by typing `ruby hello_world.rb` into your terminal and
pressing `enter`/`return`. The `ruby` part of that command tells your computer
to use the Ruby interpreter when reading and executing the code in your file.
The second part of the command, `hello_world.rb` is the path to the file you
want to run.

If you are successful at running `hello_world.rb`, you will see:

```bash
$ ruby hello_world.rb
Hello World!
```

## Run the Learn Gem

Confirm everything is working by running the `learn` command. You should see that
all tests are passing (e.g. no red error text).

**Note:** When you write code, the case (uppercase/lowercase) of characters
matters, and so your test will not pass unless you print "Hello World!" exactly.

## Submit a Learn Lab

Submit your solution by typing `learn submit` into your terminal, then click "Next
Lesson" to move forward.

## Conclusion

Your adventure in Ruby has only just begun!

## Resources

- [Hello World! by Brian Kernighan, from Artsy's Algorythm Auction](https://www.artsy.net/artwork/brian-kernighan-hello-world)

[hello]: http://en.wikipedia.org/wiki/%22Hello,_World!%22_program
[filenames]: https://en.wikipedia.org/wiki/Filename_extension
