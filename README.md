# alfred-catemoji
Alfred workflow to search for an emoji by category

![alfredCat](https://user-images.githubusercontent.com/47395660/76165274-5048f480-615e-11ea-9e83-d133f4e96e72.gif)

## About
This workflow allows you to quickly find and paste an emoji while you're typing something.

I like to use a workflow instead of snippets because it's easier to find an emoji by further categorization terms.

If you see some missing emojis (question mark instead of emoji), you're probably using an older OSX. You may need to upgrade it, or just [update the emoji font](https://github.com/joypixels/emojione/tree/master/extras/fonts)

This project was inspired by [emoji-fzf](https://github.com/mvertescher/emoji-fzf)

## Installation
Download the [workflow](https://raw.githubusercontent.com/avielsh/alfred-catemoji-workflow/master/alfred-catemoji.alfredworkflow) and double
click to import to alfred.

You may assign a hotkey in the workflow to accelerate your flow.

## Usage
### Triggers
`em <term>` - Search an emoji, further terms will filter the results.

`emw <term>` - Search using whole word search.

`emr` - Access recently used emojis.

### Modifiers
`Ctrl` - Continuously add emojis (reopen alfred after every execution).

### Adding categories

![Adding Categories](https://user-images.githubusercontent.com/47395660/76264257-ef0e4780-6269-11ea-948f-abfb64b8bbcf.png | width=560)

You may add your own categories in the following way

1. Find an emoji
2. Load it to the argument list using `Tab`
3. Type `|` and then your categories (space delimited). Eg `|horses quadrupal`
4. When you press Enter, the categories will be added. Existing categories for that emoji will be skipped.
