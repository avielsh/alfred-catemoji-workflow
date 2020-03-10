# alfred-catemoji
Alfred workflow to search for an emoji by tags

![alfredCat](https://user-images.githubusercontent.com/47395660/76165274-5048f480-615e-11ea-9e83-d133f4e96e72.gif)

## About
This workflow allows you to quickly find and paste an emoji while you're typing something.

I like to use a workflow instead of snippets because it's easier to find an emoji using multiple terms.

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

### Adding tags

<img width="568" alt="Screenshot_2020-03-10 00 55 24_QKWDXt" src="https://user-images.githubusercontent.com/47395660/76264783-65f81000-626b-11ea-97ec-66374939742a.png">

You may add your own tags in the following way:

1. Find an emoji.
2. Load it to the argument list using `Tab`.
3. Type `|` and then your tags (space delimited). Eg `|horses quadrupal`
4. When you press Enter, the tags will be added. Existing tags for that emoji will be skipped.

### Insert multiple emojis

<img width="574" alt="Screenshot_2020-03-10 17 03 48_LPQYDn" src="https://user-images.githubusercontent.com/47395660/76326390-3b509a80-62f1-11ea-92a6-a82fdcd1f49a.png">

&nbsp;

1. Press `tab` to append an emoji to the argument list.
2. Press `space` and start typing another search term.
3. Repeat until you're satisfied.
3. When finished, Press enter to paste to the active window.

To create a new group from the selected emojis, append `|` and the tag names you want to add.

**Tip:** To quickly access your groups type `G` ( capital ) as the search term.

