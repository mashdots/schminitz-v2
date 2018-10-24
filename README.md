# schminitz-v2 ZSH Theme

The schminitz theme is great and simple. I've updated it the [Agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) to mimic the look of schminitz, while keeping the support for Git and Powerline patched fonts.

I personally use iTerm 2 with [One Dark](https://github.com/nathanbuchar/atom-one-dark-terminal) colors.

# Compatibility

**NOTE:** In all likelihood, you will need to install a [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts) for this theme to render correctly.

I use [Fira Code](https://github.com/tonsky/FiraCode), which is nice becuase it's clean, is Powerline-patched, and uses ligatures.

To test if your terminal and font support it, check that all the necessary characters are supported by copying the following command to your terminal: `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"`. The result should look like this:

![Character Example](https://raw.githubusercontent.com/mashdots/schminitz-v2/master/characters.png)

## What does it show?

- If the previous command failed (✗)
- User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile). This is currently disabled by default and can be enabled.
- Git status
  - Branch () or detached head (➦)
  - Current branch / SHA1 in detached head state
  - Dirty working directory (±, color change)
- Working directory
- Elevated (root) privileges (⚡)

## Credits

This theme and readme was adapted from  the [Agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) files.