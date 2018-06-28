Headings
# The largest heading
## The second largest heading
### The second largest heading
#### The smallest heading
##### The smallest heading
###### The smallest heading

Styling text

**This is bold text** or, __This is bold text__

*This text is italicized* or, _This text is italicized_

~~This was mistaken text~~

**This text is _extremely_ important**

Quoting text

In the words of Abraham Lincoln:

> Pardon my French

Creating and highlighting code blocks

Use `git status` to list all new or modified files that haven't yet been committed.

Fenced code blocks
```
git status
git add
git commit
```

or

```
function test() {
  console.log("notice the blank line before this function?");
}
```

Syntax highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Links

Visit https://github.com

This site was built using [GitHub Pages](https://pages.github.com/).

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
