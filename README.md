# Site do Espaço Sublime

Este site é estático, ele só tem html + css + js e algumas imagens. O github hospeda ele. Ele foi originalmente criado por Guilherme Rossato. Para contato acesse o [Github](https://github.com/GuilhermeRossato), ou o [Linkedin](https://www.linkedin.com/in/guilherme-rossato/), ou por whats se você tiver ele.

Para fazer alterações bastar instalar o GIT, abrir o terminal e clonar o repositório:

```
git clone https://github.com/EspacoSublime/EspacoSublime
```

Isso vai criar uma pasta chamada `EspacoSublime` onde estará todos os arquivos. Não remova os arquivos `CNAME` ou o `README.md` pois são importantes. A pagina principal é a `./index.html`, e a do cardapio por exemplo é `./cardapio/index.html`.

Depois de fazer suas alterações, editar arquivos etc, abra o terminal na pasta criada e faça um commit e o envie para o github:

```
git add .
git commit -m "modificado"
git push
```

Isso vai pedir o username `EspacoSublime` e a senha vai ser a senha grande (40 caracteres) que começa com `ghp_EP...` e foi enviada por email pelo desenvolvedor original (Guilherme Rossato), é um access token utilizado para subir alterações, mantenha-o seguro e não o coloque em nenhum arquivo.

As alterações ficam visiveis dentro de 5 minutos depois do `git push` funcionar.
