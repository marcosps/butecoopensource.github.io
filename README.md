# Buteco Open Source

O Buteco Open Source é um blog feito por, e para pessoas que gostam de compartilhar suas experiências com software livre.

## Entendendo a estrutura do projeto

Atualmente utilizamos o Jekyll como ferramenta para blog.

Anteriormente utilizava-mos o Wordpress.

Todos os artigos entre 2014 e 2016 são frutos da migração do Wordpress para Jekyll.

### Diretórios

| Nome | Descrição |
|:----:|:---------:|
| _data             | Configurações |
| _includes         | Tema |
| _layouts          | Tema |
| _pages            | Páginas |
| _posts            | Artigos |
| assets/content    | Arquivos de artigos do Jekyll (Imagens, Videos, etc) |
| assets/wp-content | Arquivos de artigos do Wordpress (Imagens, Videos, etc) |
| assets/images     | Tema |
| assets/css        | Tema |

Para mais informações consulte a documentação do [Jekyll](https://jekyllrb.com/)

## Rodando o site localmente

> Necessário possuir Docker instalado.

Execute o comando:

`docker-compose up`

Acesse:

[http://localhost:4000](http://localhost:4000)

## Licenças

### Textos em artigos

![cc-by-sa](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Os artigos estão sob a licença [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

### Código fonte em artigos

Os códigos fontes dos artigos estão sob licença MIT, exceto quando indicado outra no próprio artigo.

### Código fonte do blog

Entende-se como código fonte do blog o tema, seus plugins e tudo o que esta relacionado ao Jekyll.

O código fonte está sob licença MIT.

O tema utilizado é baseado no [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes/) e este esta sob licença MIT.

O Jekyll e seus respectivos plugins possuem licença própria, para mais informações consulte os projetos em questão.
