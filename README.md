# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
```
# Get user input for their name
print "Enter your name: "
user_name = gets.chomp

# Print a personalized greeting
puts "Hello, #{user_name}! Welcome to the Ruby world."
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

  ```ruby
  # Get user input for their name
  print "Enter your name: "
  user_name = gets.chomp

  # Print a personalized greeting
  puts "Hello, #{user_name}! Welcome to the Ruby world."
  ```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

<img width="200px" src="https://github.com/eluckeys/github-docs-example/assets/6654498/1b60ff70-ecda-48eb-87a2-947ffe9169d2" />

Good Cloud Engineers use codeblocks for both code and errors that appear in the console.

```bash
NameError: undefined local variable or method `undefined_variable' for main:Object
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists
Github extends Markdown to have a list where you can check off items.<sup>[1]<sup/><sub>[1]<sub/>(#externalreferences)
- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emoji  (Optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Clouds | `:cloud:` | :cloud: |
| Clouds | `:cloud_with_lightning:` | :cloud_with_lightning: |


# Step 5 - How to create a Table

You can use the following markdown (md) format to create tables:

```markdown

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Clouds | `:cloud:` | ☁️: |
| Clouds | `:cloud_with_lightning:` | 🌩️: |
```
:cloud:

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.  [<sup>[2]</sup>](#externalreferences)
- Make note of where the pipe


## External References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]<sup/>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]<sup/>
