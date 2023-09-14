# QSelectus

O **QSelectus** é uma pequena biblioteca JavaScript que simplifica a seleção de elementos da interface do usuário. Com esta biblioteca, você pode selecionar facilmente elementos HTML e trabalhar com eles de maneira eficaz.

## Instalação

Você pode instalar o **QSelectus** em seu projeto da seguinte maneira:

```bash
npm install qselectus
```

## Uso

Para começar a usar o **QSelectus**, primeiro importe-o em seu código:

```javascript
import Selectus from 'qselectus';
```

Agora você pode criar uma instância do **Selectus** e passar uma lista de seletores CSS dos elementos que deseja selecionar:

```javascript
const elements = Selectus(['#elemento1', '.elemento2', 'button']);
```

Isso retornará uma lista de elementos HTML correspondentes aos seletores fornecidos. Você pode trabalhar com esses elementos da maneira que desejar.

## Exemplo

Aqui está um exemplo simples de como usar o **QSelectus**:

```javascript
import Selectus from 'qselectus';

const elements = Selectus(['#meu-elemento', '.outro-elemento']);

elements.forEach((element) => {
  // Faça algo com cada elemento selecionado
  element.addEventListener('click', () => {
    console.log(`Elemento clicado: ${element.tagName}`);
  });
});
```

## Contribuições

O **QSelectus** é um projeto de código aberto, e adoraríamos receber contribuições da comunidade. Se você encontrar problemas, tiver ideias para melhorias ou quiser adicionar recursos, sinta-se à vontade para abrir problemas (issues) ou enviar pull requests no [repositório GitHub do QSelectus](https://github.com/seu-usuario/qselectus).

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---

Esperamos que o **QSelectus** facilite a seleção e manipulação de elementos da interface em seus projetos. Se você tiver alguma dúvida ou precisar de assistência, não hesite em entrar em contato.
