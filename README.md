# POC-1-Flexbox
## Sistemas de Informação, 02J L12
### Andreas Caycedo Martinez, 10435302
Nessa semana aprendemos algumas novas funcionalidades de estilização da página HTML, via Flexbox e CSS. Vendo isso, o que eu implementei foi o seguinte:

-Código HTML

![image](https://github.com/user-attachments/assets/15161d4b-60da-4378-99f1-808535296f66)

Nessa imagem vemos o código principal da página. Decidi fazer o código CSS por separado e conectá-lo via link, para deixar tudo mais enxuto. Nele vemos uma div de container na classe body, e dentro dessa div temos outras divs intituladas box ou icon, que irão ter suas funções exercidas conforme certos requisitos de tela que veremos no CSS.

-Código CSS

-- Variáveis

![image](https://github.com/user-attachments/assets/f11fc496-c2b8-4888-bc3a-05dca88a6eff)

Aqui vemos algumas variáveis que utilizei só para não ter que reescrever as mesmas definições posteriormente

-- Computador

![image](https://github.com/user-attachments/assets/6bae435c-d49b-4223-8780-789e3d6d048f)
![image](https://github.com/user-attachments/assets/dc85c2b9-0314-4d26-987a-91f93a74870a)

Aqui vemos os códigos utilizados para configurar o layout da página HTML no contexto de um computador em tela cheia, utilizando programações flexbox nas classes container e box para conter os elementos das divs do código HTML em quadrados verdes, ou então o transform na pseudo classe hover para aumentar o tamanho dos containers ao passarmos o mouse encima deles.

-- Computador com tela diminuída

![image](https://github.com/user-attachments/assets/5c970342-e57a-4e91-8522-cda77d31d429)

Aqui temos o primeiro media querie, que detecta quando o dispositivo atinge o tamanho de tela premeditado para exercer a função programada e mudar o posicionamento de alguns elementos. Podemos ver que dessa vez a classe icon tem permissão para exibir seu conteúdo (display:block), enquanto a classe box span é barrada.

-- Smartphones

![image](https://github.com/user-attachments/assets/29a6a457-d6fa-46a8-842a-819304a1afde)

Eis o segundo (e último) media querie. Ele detecta quando a tela atinge o tamanho máximo de um smartphone e empilha os conteiners um encima do outro, como em uma coluna.

- Resultados
Veremos agora como funciona o código na prática

-- Tela para PC

![image](https://github.com/user-attachments/assets/bd206c9c-78a4-4037-a386-fc0c2d497229)
![Imagem do WhatsApp de 2024-09-01 à(s) 23 14 39_4cdd86cc](https://github.com/user-attachments/assets/b4cc80cb-2bc7-45b0-a843-687094f6a80f)

Vemos a tela inicial com seus campos de texto que aumentam de tamanho conforme você passa o mouse encima

-- Tela diminuída

![image](https://github.com/user-attachments/assets/74412370-0c1a-422a-9450-2a023e06505c)

Aqui vemos que numa tela diminuída, os campos de texto são substituidos por emojis intuitivos, para ocupar menos espaço

-- Tela de smartphone

![image](https://github.com/user-attachments/assets/d7b0d716-600b-4f75-ae3f-0d6e6e390693)

Aqui vemos como ficaria a página numa tela de smartphone, com os ícones um encima do outro

E foi esse o projeto desenvolvido com base no que aprendi de flexbox durante a semana
