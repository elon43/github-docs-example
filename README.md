# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.  
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- Inorder to create codeblocks in markdown you need to use three backticks(`)
- Not to be confused with quotations (')
```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
```
- When you can, you should attempt to apply syntax highlighting to your codeblocks
  
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
```
- Make note of where the backtick button is located.
- It should appear above the tab key, but it may vary based on your keyboard layout.
![Photo of backtick ](assets/what-is-a-tilde2.jpg)
![Photo of the pipe character ](assets/pipe.jpg)
<img src="https://github.com/elon43/github-docs-example/assets/33724977/ac1572a5-8e21-4f52-aa83-b93b6907309c" alt="Image" width="300" height="200" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  example.rb:1:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>
- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emoji (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.    
| Name  | Shortcode | Emoji |
|-------|-----------|-------|
| Cloud | `:cloud:` |:cloud:|
| Cloud with lighting | `:cloud_with_lightning:` |:cloud_with_lightning:|

## Step 5 - How to create a table
You can use the following markdown format to create tables:<sup>[2]</sup>
```md
| Name  | Shortcode | Emoji |
|-------|-----------|-------|
| Cloud | `:cloud:` |:cloud:|
| Cloud with lighting | `:cloud_with_lightning:` |:cloud_with_lightning:|
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (With Extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
