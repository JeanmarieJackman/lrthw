# Notes on LRTHW

Notes on the exercise flow from LRTHW.

> These sorts of comments are used for ideas about improving the sequencing flow.

## Exercises

### 00. Introducing the Hard Way

Rules:

1. Read the exercise.
2. Type the sample exactly.
3. Make it run.

Why "The Hard Way"?

1. Reading & Writing. Code is full of weird words and symbols. Get them "under your fingers". Result: speed (typing).
2. Attention to Detail. Computers can't interpret mis-spelled words like humans can. Get used to being precise when writing code. Result: speed (fewer mistakes).
3. Spotting Differences. There are a limited number of ways of doing something in code. Learn the different structures by spotting the differences between them. Result: speed (quicker reading).
4. Do Not Copy-Paste. This is to train your hands (etc), brain, and mind. Copy-paste and you lose the benefit. Result: speed (typing).
5. Practice and Persist. Keep going. Right now, it's as hard as it'll ever be. It can only get easier.

### 0. Setting Up (The Setup)

1. Get set up with Ruby and a text editor on Mac OSX (TextWrangler), Windows (Notepad++), or Linux (gedit).
2. Learn how to Google efficiently, by writing `ruby` and a keyword, e.g. `arrays`.
3. Use the programming loop: write the exercise using TextWrangler. Run the exercise in the Terminal. Fix them in TextWrangler. Repeat.

> The exercise also encourages you to ignore all the programmers who tell you to add extra packages, or use vim, or write "idiomatic" Ruby. These programmers are (unintentionally) trying to confuse you.

> A quiz would be a good way to assess progress on 00 and 0.

### 1. Hello, World! (A Good First Program)

1. Create a file called `ex1.rb`.
2. Add code to the file.

Type out the following code in `ex1.rb`:

```ruby
puts "Hello World!"
puts "Hello Again"
puts "I like typing this."
puts "This is fun."
puts "Yay! Printing."
puts "I'd much rather you 'not'."
puts 'I "said" do not touch this.'
```

> There are screenshots of this exercise in each text editor.

3. Run the file by typing `ruby ex1.rb` in the Terminal.

> There are screenshots of the output from this exercise in each text editor.

> There is a quick explanation about what error messages are and how to use them.

> We could use simple text-matching to check the answer is correct at this stage.

4. Study Drills

a. Make your script print another line.
b. Make your script print only one of the lines.
c. Put a # character at the beginning of the line. What did it do? Try to find out what this character does.

> We'd need some sort of auto-evaluator for this stuff, if we wanted to auto-check it.

5. Common questions

**How do you get colours in your editor?**
Save your file first as a `.rb` file, such as `ex1.rb`. Then you'll have colours when you type.

**I get `ruby: No such file or directory - ex1.rb (LoadError)`.**
You need to be in the same directory as the file you created. Use the `cd` command in the Terminal to go there first. Use the `pwd` and `ls` commands in Terminal to see where you are.

> These little tips would be nice as GIFs with sound/short friendly videos.

### 2. Comments and Pound Characters

> Learn how to leave comments in your programs for other developers, and for yourself in the future.

Comments are notes you can leave in your programs, e.g. to explain what a part of the program does.

> These one-line explanations would be a nice competition to run with new devs. They'd come up with better ones. And then there'd be many examples, which might make a nice library about the concept.

Code to type

```ruby
# A comment. You can write a note after this symbol.
# Anything after the # symbol is ignored by Ruby.

puts "This sentence will be printed." # but this sentence won't.

# You can use comments to disable, or "comment out" lines of code:
# puts "This line will never be run."

puts "This line will be run."
```

What you should see

```bash
$ ruby ex2.rb
This sentence will be printed.
THis line will be run.
```

**Study Drills**

1. Pick a name for the `#` character. You could choose: hash, hashtag, or pound. Whichever one you like: people will know what you're talking about.

> The rest of the study drills aim to develop good debugging practices. But it relies on the program not working, which it would be by now. The reader is encouraged to read the code backwards (weird) and out loud (good idea). There might be better ways to get them to do this.

**Student Questions**

**Why does the # in `puts "Hi # there"` not get ignored?**
The # in that code is inside a string. Google `ruby string` for more.

**How do I "comment out" multiple lines?**
Put a # in front of each one.

**I don't know how to type the # character.**
Google for "how to type a hashtag".

> It feels like this exercise should be optional.

