# Exercício 3 - Criação da Home Page

Agora estamos na hora mágica, vamos customizar nosso formulário.

Vamos começar alterando o titulo, para __Product List__

![MDK](images/img1.png)

Não utilizaremos esse campo de texto, clique encima dele, e clique no __X__ para remover.

![MDK](images/img2.png)

Precisamos agora de um Icon button, para adiciona-lo aos nosso objetos disponiveis.

Clique em __Marketplace__ para acessar a lojinha do SAP Build.

![MDK](images/img3.png)

Procure por __button__.

Selecione __Icon Button__.

![MDK](images/img4.png)

Com o Icon Button selecionado, clique em __Install__.

![MDK](images/img5.png)

Com o icon button disponivel em nossa grade de objetos, adicionaremos ao canvas.

![MDK](images/img6.png)

Altere seu Conteúdo e Icon

![MDK](images/img7.png)

Para a alteração do icone, selecione __Icon__.

![MDK](images/img8.png)

Procure por qr, e selecione o icone.

![MDK](images/img9.png)

Agora vamos adicionar a lista, que irá renderizar todos os produtos.

No menu lateral esquerdo, selecione __Core__, encontre o objeto __Icon list Item__, e adicione ao canvas.

![MDK](images/img10.png)

Troque o icone da lista para um que faça sentido com produto, no meu cenário utilizarei o icone de caixa disponivel na biblioteca Fiori de icones.

![MDK](images/img11.png)

Selecione __Icon__.

![MDK](images/img12.png)

Altere para Biblioteca Fiori de Icons.

![MDK](images/img13.png)

Selecione o icone de Caixa.

![MDK](images/img14.png)

Para alimentar a lista, precisamos vincular a Lista ao Data Variable.

Clique em Repeat With.

![MDK](images/img15.png)

Selecione __Data and Variables__.

![MDK](images/img16.png)

Selecione __Data variable__.

![MDK](images/img17.png)

Selecione __dv_products__.
E salve a seleção.

![MDK](images/img18.png)

Agora temos nossa lista com os elementos de repeat carregados, vamos alterar a label para relacionar com o elemento de carga.

Em primary label, selecione.

![MDK](images/img19.png)

Selecione __Data item in repeat__.

![MDK](images/img20.png)

Procure o elemento Name, que é o dado principal para exibir na lista.

Selecione __current__.

Selecione __Name__.

![MDK](images/img21.png)

Altere também o Set Preview value para:
```ProductName```
 
E salve.

![MDK](images/img22.png)

Vamos alterar também a Secondary Label, para o preço.

![MDK](images/img23.png)

Selecione __Data item in repeat__.

![MDK](images/img24.png)

Procure o elemento Price, que é o dado secundário para exibir na lista.

Selecione __current__.

Selecione __Price__.

![MDK](images/img25.png)

Clique em __SAVE__.

![MDK](images/img26.png)

Por fim, salve sua Home Page, construida por Completo.

![MDK](images/img27.png)

## Próximo Passo:

[Exercício 04 -  Navegação entre Home Page e Detail](/exercises/ex4/README.md)
