# Resources

This space is a built with a mix of tools, processes and techniques. The way data is handled and manipulated is often different to the default modes of operation encouraged by the devices and software we might commonly use.

I'm going to outline a few of the terms that I've found useful in unlocking this space. So, suitable for a person without much coding ability/experience but a willing to peer at code and copy/paste solutions from stackoverflow.

The definitions will mostly be my own basic understanding, perhaps with a reason for its inclusion in this glossary, followed by a link to an actual definition or source.

# Glossary

### Dither

Dithering is a process that optimises an image, resulting in a smaller file size. It is often used as a low-energy aesthetic, quickly signalling an intent towards lower-weight files. I applied a dither process to the book cover images created for the epubs. The covers are often the largest part of the epub. By dithering the images the epub is kept to a very modest size.

[Dither it](https://ditherit.com/)

[Low Tech Magazine](https://solar.lowtechmagazine.com/)

### Fediverse

The fediverse is a decentralised platform, facilitating different kinds of communication and interaction around the internet.
You might find a discussion group whose federated server you would like to join.
You will then likely be able to speak within that server, as well as seeing and speaking to people from other groups whose server's are federated with your group.

I am in a group that uses Mastodon which is easy to start with, and works like Twitter.

[Fediverse wikipedia entry](https://en.wikipedia.org/wiki/Fediverse)

### FOSS

Free, Open-Source Software.
There is a lot to unpack here.

Whilst eploring this stuff, you'll more than likely be engaging with the different communities building it.
Often, open source projects allow independent developers to work together and collectively build the tools they need.

The history of these spaces is important.
It's worth reading about, and thinking about how your use of these tools fits into that particular ecology.

[The Telekommunist Manifesto](http://telekommunisten.net/the-telekommunist-manifesto/)

[Post open-source](https://www.boringcactus.com/2020/08/13/post-open-source.html)

[Open source and free software considered harmful](https://write.as/mokou/open-source-and-free-software-considered-harmful)

### Gemini

A different internet protocol.

[Project Gemini](https://gemini.circumlunar.space/)

### Git

Git is a method of version control and development.
It tracks changes made to files.
Working with text files this has obvious benefits, which are increased when we start creating different versions of texts and compiling in different formats.

You will probably need something to use Git with.
Github is very popular, and is accessible to a beginner.
However, many folks are critical of it - and the fact that you are essentially entrusting them with your code. 

As well as using some form of Git within your own projects, it is also essential to be familiar with in order to access different tools.
The code for many projects you might like to use are hosted on Github or similar, so it is helpful to understand the processes of downloading, updating etc.

Other options are Gitlab,Sourcehut or Mattermost.

[What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

[Get Started with Github](https://docs.github.com/en/get-started)

[Why not Github](https://sanctum.geek.nz/why-not-github.html)

### Markdown

>Markdown is a lightweight markup language for creating formatted text using a plain-text editor.
>John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form.
>-Wikipedia

Markdown is used all over the place.
It is reasonably accessible and quick to get to grips with.

I mostly use Sublime Text to edit, which, with some tweaks seems quite comfortable.

Markdown generally allows you to create a basic document, that will then be processed by something else to be displayed to a reader.

It will take simple syntax, such as some hashtags, and turn them into html tags.

There are different flavours of Markdown.
This means that when writing Markdown for different places, such as Github, Glitch, Pandoc, Hugo - you might need to use slightly different syntax.

[Markdown Guide](https://www.markdownguide.org/)

### Static Site Generator

Static sites hold a website as a finished set of files.
Much of the web doesn't really work like this any more, as sites are built around interaction and the delivery of lots of different types of data.

If you go to a library and take out a book, that's the static site.
If you go to a library and then assemble a book from pages scattered all over the library as well as writing a few pages, that's a non-static site.
(Flexing both the metaphor and terms there)

This approach should increase the speed at which a website can load. It is also interesting as an approach to the web that reduces energy use and improves accessibility.

There are many static site generators available.
Glitch recently included one (11ty) in their starter pages, so that might be a good place to play with one.

You might also be able to build your own, like [ovrs](https://github.com/ovrs/aplos).
I'm working very slowly towards that.
Since starting this site I've switched from using a website md-html converter, to controlling that step myself using Pandoc.

### Terminal (CLI)

Terminal is the Mac app that allows you to use the Command Line Interface. This is the little box that looks like most of the screens on Mr. Robot.

It is an incredible way of interacting with your computer.
However, I think I'll write about that more, elsewhere.

You will need some familiarity with your CLI to access and install different tools, or dependencies.
Many tools are installed and updated directly within the CLI.

You will probably have to check and see if you have package managers like NPM or Homebrew installed.

[Beginners Mac Terminal Guide](https://www.makeuseof.com/tag/beginners-guide-mac-terminal/)

[Turing Complete User](http://contemporary-home-computing.org/turing-complete-user/)

### Pandoc

Pandoc is a powerful command line tool, that allows you to convert documents into different formats.
In my process it provided a simple way of getting the individual sections of the texts compiled together as a well-formatted epub.

[Pandoc](https://pandoc.org/epub.html)

