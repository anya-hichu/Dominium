# Dominium

WIP

Ideas:

/dominium (config/enable/disable/toggle)

- Puppet master like with ACL (token) where can send base64 gzipped "command list" with id/names/alias to share (copy-paste manual operation, possibility to make it look like data:image/gif;base64,xxx or random link param) or generated file - Token gives permission to specific commands to matching characters (regex) for specific duration or until invalidated
- Custom syntax like <do.id> or alias with regex (!alias) or <do.alias> (button to automatically add in chat or copy in clipboard)

Don't need to be installed on both like puppetmaster but command viewer makes it easier to use

# Control Commands

- /dominium (enable|cancel|disable)
- /muffle (on|toggle|off) - muffled chat, defaults to on
- /blind (on|toggle|percentage|off) - black overlay with opacity, defaults to on
- /mute (on|toggle|off) - disable chat input, defaults to on
- /deaf (on|toggle|off) - hide chat messages, defaults to on
- /drunk (on|toggle|off) - screen effect overlay, defaults to on
- /restrain (on|toggle|off) - disable move controls, defaults to on
- /trail target (on|toggle|off) - force follow, defaults to on (quote support)
- /confine (on|toggle|off) - can't leave room/house, defaults to on
- /fpv (on|toggle|off) - force first person view, defaults to on
- /slow (on|toggle|off) - force walk mode

Split in 2 plugons ControlCommands and dominium

Safe keybind by default on END (configuration window)
