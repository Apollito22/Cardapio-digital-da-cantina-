# Nosso Workflow de Trabalho

# Título nível 1 – Equivalente ao h1
## Título nível 2 – Equivalente ao h3
### Informações - Equivalente ao p
...

Nós utilizamos o **GitHub Flow**. Toda nova funcionalidade deve ser criada em uma branch separada (ex: `feature/nova-pagina`) e, após finalizada, fazemos o merge para a branch `main`.

"Optamos por utilizar o GitHub Flow porque somos uma equipe de apenas duas pessoas desenvolvendo um projeto inicial, o que exige agilidade e entregas rápidas, sem a necessidade de processos de revisão excessivamente complexos que criariam gargalos".

## Nossos Commits Semânticos Customizados
Além dos padrões (feat, fix, docs), criamos 3 tipos novos para organizar melhor o projeto:
* **`ui:`** Usado exclusivamente quando alteramos estilos no arquivo CSS.
* **`content:`** Usado quando mudamos textos (sinopses, títulos) dentro do HTML.
* **`asset:`** Usado para inserção, remoção ou organização de imagens e mídias.