# My notes #
### Using emoji ###
You can add emoji to your writing by typing :EMOJICODE:.
@octocat :+1: This PR looks great - it's ready to merge! :shipit:
Rendered emoji
Typing : will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press Tab or Enter to complete the highlighted result.
For a full list of available emoji and codes, check out emoji-cheat-sheet.com.
### Relative links ###
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.
A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. You can use all relative link operands, such as ./ and ../.
Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository