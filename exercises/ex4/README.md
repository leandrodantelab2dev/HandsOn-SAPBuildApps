# Exercício 4 - Navegação entre Home Page e Detail

Neste step vamos construir a navegação entre a HomePage e a DetailPage, onde irá conter os dados do produto de forma detalhada.

No canto superior esquerdo, clique em __Home Page__, para acessar a sumarização de todas as páginas.

![MDK](images/img1.png)

Adicione uma nova página, clique em __ADD NEW PAGE__.

![MDK](images/img2.png)

Nomeie como Product Detail.
Clique em __OK__.

![MDK](images/img3.png)

Com a nova página criada, acesse as variavéis para configurar as PAGE PARAMETERS.

![MDK](images/img4.png)

No menu lateral esquerdo, selecione __PAGE PARAMETERS__.

Clique __ADD PARAMETERS__.

Configure o nome do Parameter como:

```idproduct```

![MDK](images/img5.png)

Volte para o editor gráfico, clicando no switch button.

![MDK](images/img6.png)

Acesse o menu de navegação clicando no canto superior esquerdo, na label azul.

E navegue para a home page, para adicionar a lógica de navegação..

![MDK](images/img7.png)

Selecione a lista de produtos para adicionar lógica.

Clique em: __Add logic to ICON LIST ITEM 1__.

![MDK](images/img8.png)

Nos elementos de lógica adicione: __Open page__.

E conecte o evento para o navegation.

![MDK](images/img9.png)

Selecione a pagina que irá abrir, em __Page__.

![MDK](images/img10.png)

Selecione a página __Product Detail__ e __Save__.

![MDK](images/img11.png)

Habilitará um campo: __idproduct__.

Selecione qual o elemento que irá aplicar como valor.

![MDK](images/img12.png)

Selecione __Formula__.

![MDK](images/img13.png)

Selecione __Create formula__.

![MDK](images/img14.png)

Preencha no campo:

STRING(repeated.current.ID)

E salve a fórmula.

![MDK](images/img15.png)

## Próximo Passo:
[Exercício 05 - Criação da Detail Page](/exercises/ex5/README.md)