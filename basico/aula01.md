# Não vamos perder muito tempo
Se você quer conhecer a historia do JS primeiro vá neste [link](https://developer.mozilla.org/pt-BR/docs/Aprender/Getting_started_with_the_web/JavaScript_basico)
Atráves do material contido nele, vou seguir com o básico de JS para que possamos ser eficientes!
## Sem mimimi, vamos aos cods!
- Comentários Single-line (uma linha): São caractérs especiais os quais em tempo de execução, ao serem identificados pelo interpretador de codigos JavaScript, fazem com que a partir de sua posição o resto da linha onde se encontra seja ignorada pela execução do codigo!
```
\\Este é um comentário de uma linha e tudo que está após "\\" não será executado em seu programa
```
- Comentários Multiline (várias linhas): São caractérs especiais usados para ignorar a interpretação de um bloco de caracters pelo interpretador de códigos:
Assim, quando eu quero fazer uma conscideração, ou passar a ignorar um bloco de codigos, eu uso os delimitadores "\*" e "*\"
```
\* Este
   é
   um
   comentário
   em
   multiplas
   linhas
*\
```
Assim como no comentário de uma linha, este não diz repeito ao que vem antes de seus caracters. Logo, o que vier antes dos caracters será executado pelo seu interpretador de codigos. Na verdade, o comentário em bloco, só irá ignorar o que estiver entre os delimitadores, logo o que vier antes e depois será executado e caso não seja um codigo interpretável será interrompido com erro!

- Variáveis: São containeres que vão armazenar os nossos dados em tempo de execução para que possamos executar transações,
Assim, quando eu quero armazenar um valor eu primeiro preciso definir um local para que ele possa ser guardado para que então eu possa acessar este container e usufruir de seu conteudo!
```
var variavel = "teste";
