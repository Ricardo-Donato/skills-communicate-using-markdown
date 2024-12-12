# This is a title with h1 size
## This is a title with h2 size
### This is a title with h3 size
#### This is a title with h4 size
##### This is a title with h5 size
###### This is a title with h6 size

<hr></hr>

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` python
import json

def carregar_tarefas():
    try:
        with open('tarefas.json', 'r') as file:
            return json.load(file)
    except FileNotFoundError:
        return []
```
