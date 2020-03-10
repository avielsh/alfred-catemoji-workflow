# alfred-catemoji
This workflow allows to quickly find and paste an emoji.

Because I type a lot of emojis, I prefer to use a workflow instead of snippets because it's easier and faster to find an emoji using different search terms.

![alfredCat](https://user-images.githubusercontent.com/47395660/76165274-5048f480-615e-11ea-9e83-d133f4e96e72.gif)

## Installation
[Download](https://raw.githubusercontent.com/avielsh/alfred-catemoji-workflow/master/alfred-catemoji.alfredworkflow) the workflow and double click in finder to import into alfred.

## Usage
### Triggers
`em <term>` - Search an emoji, further terms will filter the results.

`emw <term>` - Search using whole word search.

`emr` - Access recently used emojis.

Optionally assign a hotkey trigger to the workflow.

### Modifiers
`Ctrl` - Continuously add emojis (reopen alfred after each execution).

### Adding tags

<img width="568" alt="Screenshot_2020-03-10 00 55 24_QKWDXt" src="https://user-images.githubusercontent.com/47395660/76264783-65f81000-626b-11ea-97ec-66374939742a.png">

To add a tag

1. Find an emoji.
2. Load it to the argument list using `Tab`.
3. Type `|` and start typing tags (space delimited). Eg `|horses quadrupal`
4. After pressing `Enter`, the tags will be added. Duplicate tags will be skipped.

### Inserting multiple emojis

<img width="574" alt="Screenshot_2020-03-10 17 03 48_LPQYDn" src="https://user-images.githubusercontent.com/47395660/76326390-3b509a80-62f1-11ea-92a6-a82fdcd1f49a.png">


1. Press `tab` to append an emoji to the argument list.
2. Press `space` and start typing another search term.
3. Repeat until satisfaction.
3. Press `Enter` to paste to the front window.

To create a new group from the selected emojis, append `|` and then type some tags.

💡 To quickly access groups, type `G` ( capital ) as the search term.

### Troubleshooting
- Some emojis are displayed as question marks - This workflow uses the emoji-v12.0 font. To fix missing emojis, try upgrading OSX, or just [update the emoji font](https://github.com/joypixels/emojione/tree/master/extras/fonts).

### Thank yous

This project was inspired by [emoji-fzf](https://github.com/mvertescher/emoji-fzf)

