# 🚀 POO Desafio: Modelagem e Diagramação de um Componente iPhone
********************************************************************************************

👩🏻‍💻 Descrição do Desafio:

Desafio elaborado durante o bootcampSantander 2024 - Backend com Java da DIO, no qual ficamos responsáveis por modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet, solicitado no contexto a seguir:

Com base no vídeo de lançamento do iPhone de 2007 (link abaixo), você deve elaborar a diagramação das classes e interfaces utilizando uma ferramenta UML de sua preferência. Em seguida, implemente as classes e interfaces no formato de arquivos `.java`.

[Lançamento iPhone 2007](https://www.youtube.com/watch?v=9ou608QQRq8)
 - Minutos relevantes: 00:15 até 00:55

#### Funcionalidades a Modelar
1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo
1. Criar um diagrama UML que represente as funcionalidades descritas acima.
2. Implementar as classes e interfaces correspondentes em Java (Opcional).

## 📊 Meu Diagrama UML

  ![image](https://github.com/Rafagons/diagramacao-classes-iPhone-dio/blob/97b1fe21a1f32732f6db11a77378d0f2fd183dc7/docs/Modelagem%20Iphone.png)



Como opcional eu implementei as classes e interfaces nesse projeto. Aqui explicarei detalhadamenete cada classe representada no meu diagrama de classe do projeto. Cada classe desempenha um papel específico e contribui para a funcionalidade global do sistema.

### `iPhone`

A classe `iPhone` é a classe principal que representa o dispositivo como um todo. Ela implementa as interfaces `ReprodutorMusical`, `AparelhoTelefonico` e `NavegadorInternet`. Isso permite que o iPhone desempenhe os papéis de reprodutor musical, aparelho telefônico e navegador na Internet. 

### `ReprodutorMusical`

A interface `ReprodutorMusical` define os métodos necessários para controlar a reprodução de música, como `tocar()`, `pausar()` e `selecionarMusica()`. As classes que implementam essa interface são capazes de reproduzir músicas.

### `AparelhoTelefonico`

A interface `AparelhoTelefonico` define os métodos para realizar chamadas telefônicas e enviar mensagens, incluindo `ligar()`, `atender()` e `iniciarCorreioVoz()`. As classes que implementam essa interface podem funcionar como dispositivos telefônicos.

### `NavegadorInternet`

A interface `NavegadorInternet` define métodos para a navegação na web, como `exibirPagina()`, `adicionarNovaAba()` e `atualizarPagina()`. As classes que implementam essa interface podem atuar como navegadores da Internet.

Cada classe ou interface desempenha um papel específico no sistema e contribui para a versatilidade do dispositivo iPhone, tornando-o capaz de realizar uma variedade de funções.

## 🛠️ Construído com

* [Java JDK 21](https://www.oracle.com/middleeast/java/technologies/downloads/) - Jdk Java Usado.
* [Visual Studio Code](https://code.visualstudio.com/) - IDE Utilizada para criação e edição do código.
* [Draw.io](https://www.drawio.com/) - Editor de diagramas e fluxogramas online utilizado para criar meu diagrama UML.

---

Se quiser saber mais sobre o projeto as solicitações do professor, clique [aqui.](https://github.com/digitalinnovationone/trilha-java-basico/tree/main/desafios/poo)


⌨Criado por [Rafagons](https://github.com/Rafagons)

