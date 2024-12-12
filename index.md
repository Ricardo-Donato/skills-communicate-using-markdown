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
<hr></hr>

## Função que permite a inserção de pontos e nega a inserção de letras em inputs type text

```javascript
function aplicarFormatacaoDecimal(seletor) {
    $(seletor).on('keypress', function(e) {
        let inputNumber = '';
        setTimeout(() => {
            let input = $(this).val().split("");
            let hasDecimalPoint = false;
            for (let i = 0; i < input.length; i++) {
                if (!isNaN(input[i]) && input[i] != " ") {
                    inputNumber += input[i].trim();
                } else if (input[i] === '.' && !hasDecimalPoint) {
                    inputNumber += '.';
                    hasDecimalPoint = true;
                }
            }
            $(this).val(inputNumber);
        }, 1);
    });
}
```

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
