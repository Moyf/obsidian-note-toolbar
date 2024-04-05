![Note Toolbar Obsidian Plugin](./docs/readme_banner.png)

[![GitHub Release](https://img.shields.io/github/v/release/chrisgurney/obsidian-note-toolbar?sort=semver)](https://github.com/chrisgurney/obsidian-note-toolbar/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The Note Toolbar plugin for [Obsidian](https://obsidian.md) provides a flexible way to create toolbars at the top of your notes.

With this plugin, you also get [Note Toolbar Callouts](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Note-Toolbar-Callouts) which you can add anywhere in your notes.

📖 **How to use this plugin: [User Guide](https://github.com/chrisgurney/obsidian-note-toolbar/wiki)** ☕️ **Support me: [Buy me a coffee](https://www.buymeacoffee.com/cheznine)**

![Demo of a sticky toolbar](./docs/note_toolbar_demo.gif)

# Installation

1. Open Obsidian's settings, and click _Community plugins_
2. Search for _Note Toolbar_ and select it
3. _Install_

<details>
<summary>Installing beta versions via BRAT</summary>
<br/>
<a href="https://github.com/TfTHacker/obsidian42-brat">BRAT</a> lets you beta-test plugins, to provide feedback.<br/>
<br/>
As beta versions become available, I welcome <a href="https://github.com/chrisgurney/obsidian-note-toolbar/discussions">your feedback</a> and any <a href="https://github.com/chrisgurney/obsidian-note-toolbar/issues">issues</a> you uncover!<br/>
<br/>
<blockquote>
  <ol>
    <li>Install the BRAT plugin:
      <ul>
        <li>Open <i>Settings > Community Plugins</i></li>
        <li><i>Disable safe mode</i>, if enabled</li>
        <li>Browse, and <i>search for "BRAT"</i></li>
        <li>Install the latest version of <i>Obsidian 42 - BRAT</i></li>
      </ul></li>
    <li>Open BRAT settings (<i>Settings -> Obsidian 42 - BRAT</i>)</li>
    <li>Scroll to the <i>Beta Plugin List</i> section</li>
    <li><i>Add Beta Plugin</i></li>
    <li>Specify this repository: <code>chrisgurney/obsidian-note-toolbar</code></li>
    <li><i>Enable the Note Toolbar plugin</i> (<i>Settings &gt; Community plugins</i>)</li>
  </ol>
</blockquote>
</details>

# Getting Started 🚀

Once enabled, open Note Toolbar's settings:

1. Create a _+ New toolbar_
2. Give the toolbar a _name_.
3. _+ Add toolbar item_
4. Exit settings, and _open a note_.
5. Add a `notetoolbar` property. Set it to the name of your toolbar.

If you want your toolbar to show without using a property, try mapping a folder (like wherever your Daily Notes are stored) to your new toolbar.

# Examples

Toolbar items can be commands, files, or URIs (website URLs and plugin URIs). [See the User Guide](https://github.com/chrisgurney/obsidian-note-toolbar/wiki) for detailed instructions, and examples.

Some quick examples:

| Example | How? |
| --- | --- |
| Link to Next, Previous, and Today's Daily Note | Use the Core _Daily notes_ plugin's commands ([Instructions](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Daily-Notes)) |
| Insert Template | Use [Templater](https://github.com/SilentVoid13/Templater)'s `Open insert template modal` command ([Instructions](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Templates)) |
| Show Bookmarks | Open the Bookmarks panel with the `Bookmarks: Show bookmarks` command ([Instructions](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Bookmarks)), OR use a [Note Toolbar Callout](#note-toolbar-callouts) and [Dataview](https://github.com/blacksmithgu/obsidian-dataview) to generate a toolbar with your bookmarks. ([Instructions](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Bookmarks)) |
| Execute Shell Commands | Using the [Shell Commands](https://github.com/Taitava/obsidian-shellcommands) plugin. ([Instructions](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Shell-Commands)) |

[Let me know](https://github.com/chrisgurney/obsidian-note-toolbar/discussions) how you use your toolbars, and I'll add them to [the examples](https://github.com/chrisgurney/obsidian-note-toolbar/wiki/Examples)!

# User Guide

📖 **See the [User Guide](https://github.com/chrisgurney/obsidian-note-toolbar/wiki).**

Once installed, in Obsidian go to: _Settings... > Note Toolbar_ and click _+ New toolbar_.

![Example of settings configuration](./docs/settings.png)

![Example of settings for a new toolbar](./docs/settings_edit_toolbar_full.png)

# License

Note Toolbar is licensed under Apache License Version 2.0. See the [LICENSE](https://github.com/chrisgurney/obsidian-note-toolbar/blob/master/LICENSE).

# Inspiration and Thanks 🙏

Shout out to other projects and people who helped me with questions I had while developing this plugin:

- Obsidian's [Sample Plugin](https://github.com/obsidianmd/obsidian-sample-plugin), [developer docs](https://docs.obsidian.md/) and [this playlist](https://www.youtube.com/playlist?list=PLIDCb22ZUTBnMCbJa-st4PD5T3Olep078).
- [Templater](https://github.com/SilentVoid13/Templater) - for code, especially around settings.
- [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes/) - for code, and one of the reasons this plugin works well for my own needs... and for liam.cain's help!
- [BRAT](https://github.com/TfTHacker/obsidian42-brat) - for the means to beta test this plugin.
- Everybody on the [Obsidian Discord](https://discord.gg/obsidianmd) #plugin-dev channel for their time and documentation, including but not limited to: claremacrae, dovos, lemons_dev, liam.cain, joethei, sailKite, SkepticMystic

# Contribute 🧑‍💻

Happy to [discuss your ideas](https://github.com/chrisgurney/obsidian-note-toolbar/discussions)! Pull requests are welcome!

# Support 🛟

📖 **See [Troubleshooting](https://github.com/chrisgurney/obsidian-note-toolbar/Troubleshooting) in the [User Guide](https://github.com/chrisgurney/obsidian-note-toolbar/wiki).**

[Ask questions here](https://github.com/chrisgurney/obsidian-note-toolbar/discussions) or [request a feature](https://github.com/chrisgurney/obsidian-note-toolbar/discussions/categories/ideas). If you run into something that looks like a bug, please [log an issue](https://github.com/chrisgurney/obsidian-note-toolbar/issues).

Thank you!