## Exercicio 5 -  Criação da Detail Page

Neste step iremos customizar o formulário de Detail Product.

No menu de paginas, no canto superior esquerdo.

Selecione a página, __Product Detail__.

![MDK](images/img1.png)

Vamo inicialmente configurar os Dados.

No switch button selecione variables.

![MDK](images/img2.png)

No menu lateral, selecione __Data Variables__.

Adicione um Data Variable, __Products__.

![MDK](images/img3.png)

Renomeie o Data Variable.
```dv_products_item```

Selecione o Single data record, porque precisamos apenas de um registro.

E qual é o filtro para selecionar o ID, referenciaremos do Data Parameter, que virá da Home Page.

Clique em __ID__.

![MDK](images/img4.png)

Selecione __Formula__.

![MDK](images/img5.png)

Selecione __Create Formula__.

![MDK](images/img6.png)

E adicione como valor:

```NUMBER(params.idproduct)```

E salve.

![MDK](images/img7.png)

Voltaremos para a __View__, para editar o formulário.
Remova o texto que não utilizaremos.

![MDK](images/img8.png)

Altere o conteúdo do titulo para o productName que virá do Data Variable.

![MDK](images/img9.png)

Selecione __Data and Variables__.

![MDK](images/img10.png)

Selecione __Data variable__.

![MDK](images/img11.png)

Selecione __dv_products_item__.

E __Name__.

![MDK](images/img12.png)

Salve o bind do nome do produto.

![MDK](images/img13.png)

Coloque um titulo como cabeçalho para as descrições do produto.

Altere na aba Style sua tipografia, como H3.

![MDK](images/img14.png)

Renomeie para Rating.

![MDK](images/img15.png)

Similar ao Icon Button, procuraremos um novo elemento dentro da lojinha do SAP Build.

Neste caso precisamos de um Star Rating.

![MDK](images/img16.png)

Na loja busque __rating__.

E selecione __Star Rating__.

![MDK](images/img17.png)

Clique em __Install__.

![MDK](images/img18.png)

Agora disponivel como elemento de página, adicione ao Canvas; Altere o maximum value para 5; E altere o bind value.

![MDK](images/img19.png)

Selecione __Data and Variables__.

![MDK](images/img20.png)

Selecione __Data variables__.

![MDK](images/img21.png)

Selecione a data variable configurada.

E selecione o __Rating__.

![MDK](images/img22.png)

Salve a seleção.

Para os demais campos, faça o mesmo até termos o formulário completo.

Sendo os valores:
- Product ID.
- Price.
- Release Date.

![MDK](images/img23.png)
![MDK](images/img24.png)
![MDK](images/img25.png)
![MDK](images/img26.png)
![MDK](images/img27.png)
![MDK](images/img28.png)
![MDK](images/img29.png)
![MDK](images/img30.png)
![MDK](images/img31.png)

Com o formulário de Product Detail temos nossa segunda funcionalidade concluida.

## Próximo Passo:
[Exercício 06 - Criação da Funcionalidade de Busca por QR Code](/exercises/ex6/README.md)
