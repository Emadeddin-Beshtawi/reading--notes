# How to trigger JavaScript from HTML

Within a browser, JavaScript doesn't do anything by itself. You run JavaScript from inside your HTML webpages. To call JavaScript code from within HTML, you need the <script> element. There are two ways to use script, depending on whether you're linking to an external script or embedding a script right in your webpage.

# Linking an external script

Usually, you'll be writing scripts in their own .js files. If you want to execute a .js script from your webpage, just use <script> with an src attribute pointing to the script file, using its URL:

**<script src="path/to/my/script.js"></script>**


# Writing JavaScript within HTML

You may also add JavaScript code between <script> tags rather than providing an src attribute.

**<script>
window.addEventListener('load', function () {
  console.log('This function is executed once the page is fully loaded');
});
</script>**

That's convenient when you just need a small bit of JavaScript, but if you keep JavaScript in separate files you'll find it easier to

* focus on your work
* write self-sufficient HTML
* write structured JavaScript applications

# How to Write a Git Commit Message

1) Separate subject from body with a blank line
2) Limit the subject line to 50 characters
3) Capitalize the subject line
4) Do not end the subject line with a period
5) Use the imperative mood in the subject line
6) Wrap the body at 72 characters
7) Use the body to explain what and why vs. how

## Editor method

Run git commit without a message or option and it'll open up your default text editor to write a commit message.

To configure your "default" editor:

**git config --global core.editor nano**

This would configure Git to use nano as your default editor. Replace "nano" with "emacs," "vim," or whatever your preference is.

In the opened editor, the first line is the subject (short description), leave a blank line after it, and everything else is the extended description (body).

**<Summarize change(s) in around 50 characters or less>

<More detailed explanatory description of the change wrapped into about 72
characters>**

## Command Line method

**git commit -m "Subject" -m "Description..."**

The first -m option is the subject (short description), and the next is the extended description (body)

For more information [click here](https://chris.beams.io/posts/git-commit/#separate)
