# homebrew-parcad

The Homebrew tap for [ParCAD](https://github.com/ierehon1905/parcad).

```bash
brew tap ierehon1905/parcad
brew install parcad
brew services start parcad      # the UI on http://127.0.0.1:4242, MCP on /mcp, up at login
```

This installs `parcad`, the host without a window: the whole app is in your
browser, and `parcad mcp` is the MCP server a Claude Code or Codex plugin
launches. Nothing it installs is quarantined.

The desktop app is no longer a cask here; download it from
[Releases](https://github.com/ierehon1905/parcad/releases).

`Formula/parcad.rb` is copied from `packaging/homebrew/Formula/parcad.rb` in
the main repository on each release.
