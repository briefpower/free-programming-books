道人道：“原来近日风流冤家又将造劫历世，但不知起于何处，落于何方？”那僧道：“此事说来好笑。只因当年这个石头，娲皇未用，自己却也落得逍遥自在，各处去游玩。一日来到警幻仙子处，那仙子知他有些来历，因留他在赤霞宫中，名他为赤霞宫神瑛侍者。他却常在西方灵河岸上行走，看见那灵河岸上三生石畔有棵绦珠仙草，十分娇娜可爱，遂日以甘露灌溉，这绦珠草始得久延岁月。后来既受天地精华，复得甘露滋养，遂脱了草木之胎，幻化人形，仅仅修成女体，终日游于离恨天外，饥餐秘情果，渴饮灌愁水。只因尚未酬报灌溉之德，故甚至五内郁结着一段缠绵不尽之意。常说：‘自己受了他雨露之惠，我并无此水可还。他若下世为人，我也同去走一遭，但把我一生所有的眼泪还他，也还得过了。’因此一事，就勾出多少风流冤家都要下凡，造历幻缘，那绦珠仙草也在其中。今日这石正该下世，我来特地将他仍带到警幻仙子案前，给他挂了号，同这些情鬼下凡，一了此案。”那道人道：“果是好笑，从来不闻有‘还泪’之说。趁此你我何不也下世度脱几个，岂不是一场功德？”那僧道：“正合吾意。你且同我到警幻仙子宫中将这蠢物交割清楚，待这一干风流孽鬼下世，你我再去。如今有一半落尘，然犹未全集。”道人道：“既如此，便随你去来。”





## Contributor License Agreement
By contributing you agree to the [LICENSE](https://github.com/vhf/free-programming-books/blob/master/LICENSE) of this repository.

## Contributor Code of Conduct
By contributing you agree to respect the [Code of Conduct](https://github.com/vhf/free-programming-books/blob/master/CODE_OF_CONDUCT.md) of this repository.

## In a nutshell
1. "An link to easily download a book" is not alway a link to a *free* book. Please only contribute free content. Make sure it's free.
2. You don't have to know git: if you found something of interest which is *not already in this repo*, please open an issue with your links propositions.
    - If you know git, please fork the repo and send pull requests.
3. We have 5 kinds of lists. Choose the right one:
    
    - *Books* : PDF, HTML, ePub, a gitbook.io based site, a Git repo, etc.
    - *Courses* : A course is a learning material which is not a book and where there is no interactive tool embeded in the site. [This is a course](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/).
    - *Interactive Tutorials* : An interactive website which lets the user type code or commands and evaluates the result (by "evaluate" we don't mean "grade"). e.g.: [Try Haskell](http://tryhaskell.org), [Try Github](http://try.github.io).
    - *JavaScript Resources* : Any resources teaching a JavaScript framework or library.
    - *Problem Sets & Competitive Programming* : A website or software which lets you assess your programming skills by solving simple or complex problems, with or without code review, with or without comparing the results with other users.

4. Make sure to follow the [guidelines below](#guidelines) and respect the [Markdown formatting](#formatting) of the files

### Guidelines
- make sure a book is free. Double-check if needed.
- insert your links in alphabetical order. If you see a misplaced link, please reorder it and submit a PR
- use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + no file hosting services (this includes (but is not limited to) Dropbox and Google Drive links)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/book/current/` is better than `http://example.com/dir/book/v1.0.0/index.html`
- if a link has an expired certificate/self-signed certificate/SSL issue of any other kind:
  1. *replace it* with its `http` counterpart if possible (because accepting exceptions can be complicated on mobile devices)
  2. *leave it* if no `http` version but link still accessible through `https` by adding an exception to the browser or ignoring the warning
  3. *remove it* otherwise
- if a link exists in multiple format, add a separate link with a note about each format
- if a resource exists at different places on the Internet
    + use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + if they link to different editions and you judge these editions are different enough to be worth keeping them, add a separate link with a note about each edition
- prefer atomic commits (one commit by addition/deletion/modification) over bigger commits. No need to squash your commits before submitting a PR. (We will never enforce this rule as it's just a matter of convenience for the maintainers)

### Formatting
- All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) syntax. It's simple!
- All the lists start with an Index. The idea is to list and link all sections and subsections there. Keep it in alphabetical order.
- Sections are using level 3 headings (`###`), and subsections are level 4 headings (`####`).

The idea is to have
- `2` empty lines between last link and new section
- `1` empty line between heading & first link of its section
- `0` empty line between two links
- `1` empty line at the end of each `.md` file

Example:

    [...]
    * [An Awesome Book](http://example.com/example.html)
    
    
    ### Example
    
    * [Another Awesome Book](http://example.com/book.html)
    * [Some Other Book](http://example.com/other.html)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome Book] (http://example.com/book.html)
GOOD: * [Another Awesome Book](http://example.com/book.html)
```

- If you wish to mention the author, use ` - ` (a dash surrounded by single spaces)

```
BAD : * [Another Awesome Book](http://example.com/book.html)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.html) - John Doe
```

- Put a single space between the link and its format

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)(PDF)
GOOD: * [Another Awesome Book](http://example.com/book.pdf) (PDF)
```

- Author comes before format:

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.pdf) - John Doe (PDF)
```
