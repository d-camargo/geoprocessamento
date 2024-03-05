# Inserir camada vetorial no QGIS

Um dos primeiros passos no QGIS é inserir arquivos vetoriais (depois a gente fala melhor sobre isso) para edição e trabalho dentro da plataforma.
Inicialmente é necessário baixar o arquivo vetorial, extensão shp (shapefile). [Clique aqui](https://www.ibge.gov.br/geociencias/downloads-geociencias.html) para entrar no servidos do IBGE e procurar pelo arquivo da divisão político-administrativa do Brasil. Confira na Figura 1.1 e 1.2.

Figura 1.1 - Passos para encontrar o arquivo 'BR_UF_2020.zip'
![image](https://github.com/d-camargo/geoprocessamento/assets/86422962/73cc2c36-283d-48ce-8765-c2796e1e9589)

Figura 1.2 - Passos para encontrar o arquivo 'BR_UF_2020.zip'
![image](https://github.com/d-camargo/geoprocessamento/assets/86422962/ca4d2be1-69fe-4a5c-b8f4-1fd48a9246e2)

Salve o arquivo em uma pasta de fácil acesso e faça a descompactação do arquivo, que se encontra "zipado". Dentro do arquivo compactado existem mais outros 5 arquivos com as extensões .cpg, .dbf, .prj, .shp e .shx. Toda vez que for abrir um arquivo do tipo .shp é necessário ter esses arquivos. Em termos práticos, quando for realizar a troca de arquivos com alguém você deve enviar todos esses arquivos para que a pessoa consiga abrir o arquivo corretamente.

Abra o QGIS e, também, um novo projeto. Logo após vá até a opção 'Camada' -> 'Adicionar camada' -> 'Adicionar camada vetorial' (ou use o atalho Ctrl+Shft+V). Na Figura 1.3 é possível visualizar este passo.

Figura 1.3 - Adicionando camada vetorial
![image](https://github.com/d-camargo/geoprocessamento/assets/86422962/41e6f6a7-3f14-445f-a736-4c6a5e5a0454)

Logo após uma nova janela irá abrir (Gerenciador de fonte de dados), conforme Figura 1.4. Será possível agora procurar pelo arquivo que você baixou no site do IBGE, clicando na reticências. Escolha pelo arquivo com extensão .shp e então finalize clicando em 'Adicionar', no canto inferior direito da janela do Gerenciador de fonte de dados (Figura 1.4).

Figura 1.4 - Gerenciador de fonte de dados
![image](https://github.com/d-camargo/geoprocessamento/assets/86422962/fd7e39a5-e0bf-4c24-9c8e-a3f2017e2d11)

Se tudo correu bem, sua área de trabalho deverá ter agora um mapa do Brasil com a divisão dos estados e do DF,
conforme Figura 1.5.

Figura 1.5 - Área de trabalho com o conteúdo do arquivo shapefile
![image](https://github.com/d-camargo/geoprocessamento/assets/86422962/430ee356-dbdd-41f3-8e17-7fbad3cfdbf0)

Há, pelo menos, outras duas formas de realizar esse passo. Um deles é através do 'Favoritos', que fica no painel do 'Navegador', é possível ver esse método através [deste vídeo](https://youtu.be/GWm8ekcsv1M?si=UtHkhq4_QxymvC0k&t=176) (avance para o minuto 02:55).

Outro método é arrastar (clicar e segurar) o arquivo shapefile da pasta para a área de trabalho do QGIS (conforme mostra o GIF abaixo)

Até mais!
