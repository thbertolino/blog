# Como eu fiz esse blog com Jekyll.

Esse blog em que estou escrevendo meus posts foi feito de maneira bem simples usando o [Jekyll](https://jekyllrb.com/). E aqui irei mostrar como você também pode replicar em um site/blog para você.

## O que é Jekyll?

O Jekyll é uma ferramenta que gera sites estáticos (como este), escrito em Ruby. Mas não se preocupe, você não precisa saber usar Ruby para utilizá-lo.

E o mais legal, é que ele pode ser hospedado facilmente no [GitHub Pages](), que é onde eu estou hospedando este blog.

## Como instalar

Para instalar o Jekyll, você vai precisar instalar o Ruby no seu ambiente de desenvolvimento, você pode conferir tudo [aqui](https://jekyllrb.com/docs/installation).

Após ter todo o ambiente configurado, instale o Jekyll com a linha de comando:

```sh
gem install jekyll bundler 
```

## Criando o site

Para criar o site propriamente dito, digite as seguintes linhas comando:

```sh
jekyll new myblog
```

E ele irá criar o diretório "myblog", com os seguintes arquivos.

![files](/img/jekyll/files.png)
