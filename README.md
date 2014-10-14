# Markdown v2

The goal of this project is to extend Markdown while remaining within the terms
of the original [Licence][0]. This is without any legal advice.

Special notice is made to the **third** condition:

> Neither the name “Markdown” nor the names of its contributors may be used
> to endorse or promote products derived from this software without specific
> prior written permission.

This project is a distribution of the original source with some unreleased work
attached to it. The project will make frequent mention of the name "Markdown" in
order to convey topic, but it will never be released without written permission.
This project is welcome to be "claimed back" by the original author if they have
the time or interest. Otherwise it will act as a place for agruments about
Markdown; all of which are welcome.

# The rational standard

When building a Markdown parser of your own, the practical way to achieve this
was to follow the original docs and check against the Perl script. All in all
it was a pretty simple task as long as you knew what you were doing and honored
the original philosophy. Then GitHub introduced a [variant][1] which made a lot
of sense for use in discussions, so the original author [approved][2] of them.

The purpose of this project is to build upon the original files to ensure that
they match up to today; and are ready for tomorow. This will involve making the
original script pluggable and allow things to solidfy. For example; using the
`GFM` syntax to signify code blocks will be a [task][3].

[0]: http://daringfireball.net/projects/markdown/license
[1]: https://help.github.com/articles/github-flavored-markdown/
[2]: http://daringfireball.net/linked/2009/10/23/github-flavored-markdown
[3]: https://github.com/blog/1375
