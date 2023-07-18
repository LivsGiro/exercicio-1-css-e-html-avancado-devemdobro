Este é o primeiro exercício de nível avançado do curso de Desenvolvedor Web Full stack da Dev em Dobro.

"Esse exercício é uma ALTERNATIVA ao desafio do frontend mentor. Onde o principal desafio é criar um cartão que contenha as informações de perfil. Para ser aprimorado as habilidades de posicionamento de elementos usando flexbox." - Dev em Dobro.

Os materiais de apoio para a realização do projeto foram:
 - Família de fonte a ser utilizada (Google fonts).
 - Peso das fontes.
 - Imagem de perfil e favicon.
 - Cor de fundo e cor do texto.
 - Layout do projeto final para desktop e celular.

Primeiramente foram criados os arquivos base: o HTML5, um arquivo de estilo CSS3 para resetar algumas difinições automáticas que poderiam atrapalhar o desenvolvimento da página, e outro arquivo CSS3 para a estilização propriamente dita.

A família da fonte foi obtida no Google Fonts, em que se selecionou os dois pesos indicados (400 e 700) para uso. O link para a fonte foi adicionado no <head> do HTML5, como indicado no próprio Google Fonts e definido o tipo de fonte do projeto no arquivo CSS3 de estilo, no <body>, assim englobando tudo que estiver dentro dele.

Além da fonte, também foram linkados os arquivos CSS3 e adicionado a imagem favicon.

No corpo do HTML5 foi criado o container principal (o cartão de perfil) e dentro dele foi feita uma div, contendo uma outra div para a foto do perfil e os dados (nome, idade, cidade) e a outra "parte", o rodapé de cartão do perfil, foi criada uma lista desordenada para a inserção dos contadores de seguidores, curtidas e fotos.

Cada elemento recebeu uma classe para ser estilizado no arquivo style.css, recebendo características de tamanho de fonte, força da fonte, cor de letra, espaçamento entre os elementos.

A responsividade dessa página foi obtida usando propriedades flex (display flex e flex-direction column) e de box-sizing, usando um margin para o cartão todo, o que permite o cartão de perfil se adaptar até uma tela de 320px de largura sem perder sua conformação.

O flex-box é uma ferramenta interessante para organizar os elementos na tela e deixá-los concisos (relacionados) entre si, o que facilita a responsividade da página mesmo sem o uso de media query ou alguma outra especificidade.

Obrigada por acompanhar o início do meu trabalho. Lívia
