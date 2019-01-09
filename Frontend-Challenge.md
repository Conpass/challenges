![](https://dgivdslhqe3qo.cloudfront.net/careers/photos/23661/thumb_photo_1484531612.png)

# Objetivo
O objetivo deste desafio é criar uma aplicação React onde você cria e gerencia Hotspots, tudo na mesma interface.

**O que é um Hotspot?** Um Hotspot nesse contexto é um efeito visual que usamos para mostrar algo novo em uma interface. Geralmente é uma bolinha com alguma animação tentando chamar a atenção do usuário, e ao clicar na bolinha abre-se uma caixa com a explicação. Veja [Imagem 1](#image1)

# Requisitos
- A aplicação deve ser feita usando React, seguindo o layout da [Imagem 2](#image2).
- Ao clicar no botão “Criar Hotspot”, deve-se iniciar o processo de captura do elemento no qual o Hotspot estará vinculado, e também a posição exata do clique. [Imagem 3](#image3)
- Na captura, a cada movimento do mouse, deve-se mostrar ao usuário um feedback de qual elemento ele estará selecionando. Algo como o “Inspecionador do Google Chrome Dev Tools”.
- Ao clicar em algum elemento da página
  - deve mostrar um efeito visual (bolinha vermelha) indicando o local exato em que foi clicado;
  - deve atualizar a lista de hotspots logo abaixo do botão “Criar Hotspot”;
  - não precisa abrir uma caixa para digital texto, como na [Imagem 1](#image1)
  - deve salvar as informações do hotspot (localStorage)
- Na listagem de hotspots, ao clicar em “Delete”, deve-se:
  - Remover o hotspot (efeito visual) da interface e;
  - Atualizar a lista de hotspots
- Utilizar Redux para controlar o estado da aplicação (ex: hotspot cadastrados)

# Bonus
- Criação de testes para os components (Biblioteca fica a seu critério)
- Atenção para o layout
- Usar (quando necessário), features das novas versões do JS
- Documentação

# O que iremos avaliar
- Stack utilizada, nós usamos: React, Redux, Webpack (CSS fica a seu critério)
- Qualidade do código (semântico, legibilidade, modular, etc)



------

## <a name="image1"></a>Imagem 1
<img src="images/fed-hotspot-example.png" width="600" />
<br><br><br>

## <a name="image2"></a>Imagem 2
<img src="images/fed-home.png" width="800" />
<br><br><br>
                                                                                                                            
## <a name="image3"></a>Imagem 3
<img src="images/fed-inspect.png" width="800" />