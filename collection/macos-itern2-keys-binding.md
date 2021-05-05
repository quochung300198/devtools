# iTerm additional (Mac-default) key bindings
## from [nikoloza iterm-key-bindings](https://github.com/nikoloza/articles/blob/master/devtools/iterm-key-bindings.md)

As you may know, we have some keys bindings missing in iTerm, like jumping cursor through word or removing whole line, etc. I listed some useful bindings to make it working in our iTerm setup. To start, open your iTerm, go to `Preferences > Keys` and then click to `+` button to add new key bindings.
  
### Clear whole line

- Keys: `⌘`+`⟵(Delete)`
- Action: `Send Hex Code`
  - `0x15`
  
### Jump cursor to line start

- Keys: `⌘`+`←`
- Action: `Send Hex Code`
  - `0x01`
  
### Jump cursor to line end

- Keys: `⌘`+`→`
- Action: `Send Hex Code`
  - `0x05`

### Delete whole word

- Keys: `⌥`+`⟵(Delete)`
- Action: `Send Hex Code`
  - `0x1B 0x08`
  
### Delete word forward

- Keys: `⌥`+`fn`+`⟵(Delete)`
- Action: `Send Escape Sequence`
  - Esc + `d`
  
### Jump cursor to left over whole word

- Keys: `⌥`+`←`
- Action: `Send Escape Sequence`
  - Esc + `b`
  
### Jump cursor to right over whole word

- Keys: `⌥`+`→`
- Action: `Send Escape Sequence`
  - Esc + `f`