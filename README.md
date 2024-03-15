# Análise de código em javascript

# Índice

[Descrição](#descrição)

[Código 1](#código-1)

[Código 2](#código-2-inputs-modificando-após-clique)

[Fontes](#fontes)

[Autores](#autores)

# ``Descrição``

A tarefa consiste em escolher dois códigos em javascript, análisá-los e implementá-los para entender o que cada um faz.

# Código 1: `Abrir Pop-Up no Centro da Página`

1 - **var win = null** ; É uma variável chamada **win** e se inicia com como **null** e será armazenada na sua janela pop-up aberta.
 
2 - **function NovaJanela(pagina, nome, w, h, scroll)**: Isso define a função que abre cinco parâmetros:
• **pagina**: A URL da página que vai ser carregada o pop-up.
 
• **nome**: O nome da janela pop-up.
 
• **w**: A largura da janela pop-up em pixels.
 
• **h**: A altura da janela pop-up em pixels.
 
• **scroll**: Uma string que especifica se a barra de rolagem deve ser oculta ou não( **'yes'** para exibir, **'no'** para ocultar)
 
3 - **LeftPosition** e **TopPosition**: Calculam a posição horizontal e/ou vertical da janela pop-up com base na largura e altura da sua tela.
 
4 - **settings**: Configurações da janela, como posição, tamanho, barras de ferramentas e status.
 
5 - **win = window.open(pagina, nome, settings);**: A função window.open() abre uma nova janela do navegador com a URL específica (pagina), o nome especificado (nome) e as configurações definidas nos **settings** . A referência da janela é armazenada em **win**.
 
O elemento HTML <a></a> possui um evento **onclick** que chama a função **NovaJanela** quando clicado, passando a URL, o nome da janela, largura, altura e exibição da barra de rolagem. O **returnfalse** previne o comportamento padrão de seguir o link, garantindo que apenas a função **NovaJanela** seja executada.


# Código 2: `Inputs Modificando Após Clique`
 
• **type="text"**  : Define o tipo de entrada como texto.
 
• **value="usuario"** : Define o valor inicial do campo como 'usuario'.
 
• **onblur** : Define uma ação a ser executada quando o campo perde o foco.
 
• **if(this.value == ' ') { this.value='usuario';}**: Verifica se o campo esta vazio. Se tiver, define o valor como "usuario".
 
• **onfocus** : Define uma ação a ser executada quando o campo ganha foco.
 
• **if(this.value == 'usuario') {this.value= ' ' ;}**: Verifica se o valor é "usuario" . Se for, limpa o campo.
 
• **value="senha"** : Define o valor inicial do campo como 'senha'
 
• **if(this.value == ' '){ this.value='senha' ; this.type='text';}**: Verifica se o campo está vazio. Se estiver, Define o valor como 'senha' e o tipo como 'text'.
 
• **if(this.value == ' senha '){ this.value=' password' ;}** : Verifica se o valor é 'senha'. Se for, limpa o campo e define como 'password'

# ``Fontes``
https://gg.gg/atividadepratica2-2ano

# ``Autores``

Manuela Araujo dos Santos

https://github.com/camilacasagrande

https://github.com/dudafontinele

https://github.com/belsil5aa