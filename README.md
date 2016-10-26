# CEFET-MG - Latex

Modelo de trabalho acadêmico Latex para o CEFET-MG usando regras da ABNT.

## Instalação e Execução - Linux (testado: debian/Ubuntu)

Faça o checkout:

```bash
      git clone https://github.com/aflavio/CEFET-MG-Modelo-Trabalho-Latex.git
      make
```

Requisitos Basicos:


```bash
      apt-get install texlive-publishers texlive-lang-portuguese texlive-latex-extra texlive-fonts-recommended
      apt-get install texlive-fonts-extra 
```

Requisitos Recomendados:
```bash
      apt-get install texlive-full texlive-fonts-extra
```


O comando make irá executar as instruções dentro do arquivo makefile

## Dicas 

Aconselho usar o editor: [TexStudio](http://www.texstudio.org/)
Talvez seja necessário modificar o mapeamento de char do gtk para o cedilla funcionar corretamente no texStudio: 


```bash
      vi /usr/share/X11/locale/en_US.UTF-8/Compose
```
Procure por todos as instâncias de ć e troque por ç e do Ć para Ç .

## Créditos

Este projeto foi baseado no trabalho do Laboratório de Sistemas Inteligentes 
do CEFET-MG e customizado em cima do modelo criado por: 

Henrique E. Borges, Denise de Souza, Cristiano Fraga G. Nunes, Lauro César

## Licença

GNU GENERAL PUBLIC LICENSE
