# Flexbox

**Flexbox** é um conjunto de ferramentas declaradas pela propriedade `display: flex;`, presentes no CSS e usados para facilitar o posicionamento de itens de forma responsiva sem a necessidade atribuições de tamanho específicos, como o `width` ou `margin`.

O **Flexbox** divide-se em dois fatores: **flex-container** e **flex-item**. Os **flex-items** são todos os elementos contidos pelo **flex-container**, declarado através do `display: flex;`. Sendo assim, qualquer propriedade do **Flexbox** só será considerada pelo navegador caso esteja dentro de uma `<div>` ou `<section>`, por exemplo, que tenha a propriedade `display: flex;`.

## Principais Propriedades Flex

As propriedades mais comuns de se ver em projetos Front-end são:

- `flex-direction` => Define a direção da organização dos *flex-items*, que normalmente é `row` (default) ou `column`;

- `flex-wrap` => Informa ao navegador se ele deve quebrar a linha em uma nova quando não houver mais espaço na atual. Usa-se `wrap`, `nowrap` ou `wrap-reverse`;

- `justify-content` => É usada para definir a posição dos *flex-items* em relação ao *main axis*.

- `align-items` => É usada para definir a posição dos *flex-items* em relação ao *cross axis*.

Para entender melhor essa história de *main axis* e *cross axis*, você pode ler [esta página](https://stackoverflow.com/questions/32551291/in-css-flexbox-why-are-there-no-justify-items-and-justify-self-properties).

# To be continued

Esta documentação ainda está em desenvolvimento, portanto, nesse meio tempo eu lhe recomendo [esse guia sensacional](https://stackoverflow.com/questions/32551291/in-css-flexbox-why-are-there-no-justify-items-and-justify-self-properties) sobre o assunto, com exemplos visuais e tudo (tenho o poster impresso e colado na minha parede hahaha). Desde já, obrigado pela leitura!
