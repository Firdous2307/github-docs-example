# Writing Good Documentation

## Step 1 - Using Codeblocks


Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with qoutation (')

```
class Book
  # Constructor
  def initialize(title, author, page_count)
    @title = title        # Instance variable for the book's title
    @author = author      # Instance variable for the book's author
    @page_count = page_count  # Instance variable for the book's page count
  end

  # Instance method to return book information
  def book_info
    "Title: #{@title}, Author: #{@author}, Page Count: #{@page_count}"
  end
end
```


- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
class Book
  # Constructor
  def initialize(title, author, page_count)
    @title = title        # Instance variable for the book's title
    @author = author      # Instance variable for the book's author
    @page_count = page_count  # Instance variable for the book's page count
  end

  # Instance method to return book information
  def book_info
    "Title: #{@title}, Author: #{@author}, Page Count: #{@page_count}"
  end
end
```

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key, 
- but it may vary based on your keyboard layout.




Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
        3: from /path/to/your_script.rb:8:in `<main>'
        2: from /path/to/your_script.rb:4:in `foo'
      RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.





## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 0
- [ ] Finish Step 1
- [x] Finish Step 2


# Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning_and_rain:` | 🌩️ |



# Step 5 - how to create a table


You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning_and_rain:` | 🌩️ |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

- Make note of where the pipe keyboard key is located.
- It should appear above return or enter key
- but it may vary based on your keyboard layout.


## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)  <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>


![JJK TEAM](https://github.com/Firdous2307/github-docs-example/assets/124298708/8e59467b-c516-4e22-8cbe-10c6f10aeffa)

