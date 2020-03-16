# alfred-catemoji
This workflow helps to quickly search and paste an emoji from a categorized list.

### Why❓🤔
Because I type a lot of emojis, I prefer to use a workflow  that allows to search an emoji using different terms, instead of using snippets because it's a bit faster, and has more flexibility in grouping emojis and adding custom terms.

![alfredCat](https://user-images.githubusercontent.com/47395660/76165274-5048f480-615e-11ea-9e83-d133f4e96e72.gif)


## Features 👍
+ 🔎 Search for an emoji quickly using a list of predefined terms.
+ 🍮 Add custom search terms for an emoji.
+ 💚💜❤️  Group multiple emojis together. 
+ ⛓ Chain paste multiple emojis together.
+ 🚀 Recent emoji list.

## Installation
[Download](https://raw.githubusercontent.com/avielsh/alfred-catemoji-workflow/master/alfred-catemoji.alfredworkflow) the workflow and import to Alfred. Simple.

## Usage
### Triggers *⃣
`em <term>` - Search for emojis. Each additional term will filter the results.

`emw <term>` - Search for emojis terms in whole words.

`emr` - Access recently used emojis.

### Modifiers 🔥
`Control ⌃` - Continuously add emojis (reopen Alfred after pasting).

### Adding terms

<img width="568" alt="Screenshot_2020-03-10 00 55 24_QKWDXt" src="https://user-images.githubusercontent.com/47395660/76264783-65f81000-626b-11ea-97ec-66374939742a.png">

To add terms

1. Find an emoji. `em horse`
2. Load it to the argument list using `Tab ↹`. `🐴`
3. Type `|` and the terms to add (space delimited). Eg `🐴|horses riding speed`
4. After pressing `Enter ⌅`, the new terms will be added. Existing terms will be skipped.

### Grouping emojis 🍌🥝🍉
The workflow can create a group of emojis for quick paste.

<img width="574" alt="Screenshot_2020-03-10 17 03 48_LPQYDn" src="https://user-images.githubusercontent.com/47395660/76326390-3b509a80-62f1-11ea-92a6-a82fdcd1f49a.png">
&nbsp;

1. Press `Tab ↹` to append an emoji to the argument list. `em dog ↹`
2. Press `Space ␣` and type another search term. `cat`
3. Press `Tab ↹` to add to the Que. `🐶🐱`
3. When the list is complete, type `|` and add some search terms. `🐶🐱|cute friendly friends`
4. If this is a one off list, just press enter to paste it after step **3.** It's will be available in the recent emojis  `emr` trigger if you want to add terms
   later.

💡 To quickly access groups, type `G` ( capital ) as the search term.

### Troubleshooting 🚧

- Some emojis are displayed as question marks - The workflow uses the emoji v12.0 font. To fix missing emojis, try upgrading OSX, or just [update the emoji font](https://github.com/joypixels/emojione/tree/master/extras/fonts).

### Inspiration 💘

This project was inspired by [emoji-fzf](https://github.com/mvertescher/emoji-fzf)

