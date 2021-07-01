# brew graph

[martido/brew-graph](https://github.com/martido/brew-graph)

```bash
brew tap martido/brew-graph
brew install brew-graph
```

## Requirements

```bash
brew install graphviz
brew graph --installed | dot -Tpng -ograph.png
brew graph --installed --highlight-leaves | fdp -Tpng -ograph.png
brew graph --installed --highlight-leaves | dot -Tpng -ograph.png
open graph.png
```
