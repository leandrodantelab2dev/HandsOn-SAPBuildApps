# Exercício 6 - Criação da Funcionalidade de Busca por QR Code

Nesse Step, adicionaremos a funcionalidade de buscar um produto por QR Code, utilizando a camera do dispositivo.

Para isso utilizaremos um acelerador do Build que nos axiliará nesse desafio.

No canto superior esquerdo, clique no menu de navegação.

E selecione a home page.

![MDK](images/img1.png)

Selecione o botão de QR Code Scan, pois é nele que adicionaremos nossa lógica.

E click em: __Add logic to ICON BUTTON 1__.

![MDK](images/img2.png)

Repare que no nosso menu lateral esquerdo também temos nossa lojinha.

Procure por __Scan QR__, e adicione ao board.

![MDK](images/img3.png)

Adicione também __Open Page__, pois assim que realizarmos a leitura do Id do Produto, precisamo navegar para a página de detalhe.

![MDK](images/img4.png)

Interligue os Nodes, para que tenha um fluxo.

![MDK](images/img5.png)

Selecione o node de open Page, e vamos alterar a pagina de abertura.

No canto direito, selecione __Page__.

![MDK](images/img6.png)

Selecione __Page ID__.

![MDK](images/img7.png)

Selecione o Product Detail e __Save__.
![MDK](images/img8.png)

Agora iremos selecionar o que irá conter no __ID Product__.
Utilizaremos uma variavel de outro node, que será do Scan QR.

Selecione __Output value of another node__.

![MDK](images/img10.png)

Selecione __Scan QR/barcode__.

![MDK](images/img11.png)

Selecione também o objeto __Scan QR/barcode content__.

E salve.

![MDK](images/img13.png)

Pronto! Agora temos nossa funcionalidade de busca por QR pronta. Salve seu App e está pronto para testar.

![MDK](images/img14.png)

## Próximo Passo:
[Exercício 07 - Execução e Testes](/exercises/ex7/README.md)