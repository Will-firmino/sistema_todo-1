# Anotações JS
1. data -> é um seletor utilizado no html que marca uma tag. Com isso você chama esse seletor no js e consegue ter acesso a tag.
2. As variáveis e constantes em JS, são cammelCase
3. As funções em JS também são também cammelCase
4. Os componentes em JS são PascalCase

estrutura: data-button // kebab-case

# Métodos do JS
1. createElement() -> Método que cria um novo elementos
2. appendChild() -> é um metodo que insere uma tag filha na tag pai
3. .add -> método que adiciona algo no contexto
5. .remove() -> Remove algo do DOM
4. .addEventListener() -> método que cria um evento para ser escutado 
6. .preventDefault -> Método que impede o comportamento padrão do formulário que iria "enviar" os dados quando o botão fosse clicado


# Propriedades do JS
1. .innerHTML -> propriedade que insere um elemento dentro de outro elemento. Ex: class, tag
2. .classList -> propriedade que acessa a lista de classes da tag
3. .value -> propriedade que acessa o valor digitado no input
4. .innerText -> propriedade que inclui um texto em uma tag
5. .parentElement -> propriedade que acessa o elemento pai

# Evento da criação da tarefa - Onde/Quando/O que
onde_vai_acontecer.addEventListener('qual_é_o_evento', o_que)

.addEventListener() -> Aqui esse método adiciona um ouvinte de evento ao botão. Caso o botão seja clicad, a função será chamada, permitino que o código responda á ação do usuário e crie uma nova tarefa na lista



