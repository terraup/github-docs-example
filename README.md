# Writing Good Documentation


## Step 1 - Using Codeblocks.


Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share code**. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and past their codeto replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')


```
# Simple Ruby program for user greeting

# Prompt the user for their name
print "Enter your name: "
user_name = gets.chomp

# Print a personalized greeting
puts "Hello, #{user_name}! Welcome to the Ruby programming world."
```

- When you can you should attempt to apply syntax highlighting to your codeblocks
  
```ruby
# Simple Ruby program for user greeting

# Prompt the user for their name
print "Enter your name: "
user_name = gets.chomp

# Print a personalized greeting
puts "Hello, #{user_name}! Welcome to the Ruby programming world."
```



- Adding an image can be done by drag and drop.
- Or, if need can resize the image by adding width.

<img width ="200" src="assets/aws-cloud-quest-solutions-architect.png" />


Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console. 

```bash
# Example of raising a standard error
def perform_dangerous_operation
  # Simulate an error condition
  raise StandardError, "Something went wrong during the dangerous operation!"
end
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emjoi shortcodes
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning and rain | `:cloud_with_lightning_and_rain:` | :cloud_with_lightning_and_rain: |
| Smiley | `:smiley:` | :smiley: |

# Step 5 - how to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning and rain | `:cloud_with_lightning_and_rain:` | :cloud_with_lightning_and_rain: |
| Smiley | `:smiley:` | :smiley: |
```
Gitub extendes the functionality of Markdown tables to provide more alignment and table cell formatting options [<sup>[2]</sup>](#external-references)


## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/#introduction)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text).
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists). <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
