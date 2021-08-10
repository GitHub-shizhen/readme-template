# Paragraphs
- - -
==============================================
I am writing the first paragraph. (The following blank line contains nothing)

I am writing the second paragraph.

You can use "\\ + enter" or "two blank spaces + enter" to create a line break, for example:

You can use \
		or "two blank spaces" to create  
		a line break.


# Blockquotes
To create a blockquote, start a line with greater than ">" followed by "space":

The quote
> "Somewhere, something incredible is waiting to be known"

has been ascribed to carl sagan.

The quote
> "Somewhere
>> something
>>> incredible is waiting to be known
has been ascribed to carl sagan.


# Links
To create links, use "\[\]" to enclose link text and "\(\)" to enclose link URL:

You can find anything at [google](http://www.google.com).

[Hurricane][1] Erika was the strongest and longest-lasting tropical cyclone in the 1997 Atlantic [hurricane][1] season.

[1]:https://w.wiki/qYn


# Code
To create inline code, wrap with backticks "  \`\`  ".

To create a code block, place 3 backticks "  \'\'\'  " on a line above with code style name and below the code block:

`static` is a keyword used in C programming language. It can be used with both variables and functions.

```c
/*!
 * @brief    gavdp received avdtp init callback
 * @param    avdtp_sep gavdp_s.avdtp_sep points to it
 * @return   @see adi_bt_error_e
 */
static int32_t adi_gavdp_avdtp_init_callback(adi_avdtp_sep_t *avdtp_sep);
```

```bash
dean@dean-OptiPlex-3020:~/adibtstack_merge/app/tws$ git commit -s
dean@dean-OptiPlex-3020:~/adibtstack_merge/app/tws$ git pull --progress -v --no-rebase "origin" dev
```
