# 🐾 Bichinho Virtual Moderno para Gemini

Um bichinho virtual que roda inteiramente dentro do **Google Gemini**, combinando a nostalgia dos brinquedos dos anos 90/2000 com mecânicas modernas de inteligência artificial, passagem de tempo, personalidade adaptativa e arte ASCII dinâmica.

## ✨ O que é o jogo?

Diferente de um chatbot comum, este projeto transforma uma conversa do Gemini no motor de um jogo persistente. Você adota um ovo misterioso, escolhe seu nome e o estilo visual da tela, e precisa voltar com frequência ao chat para cuidar da criatura.

### Principais Mecânicas

* **⏳ Passagem de Tempo Real e Narrativa:** Se você demorar horas ou dias para interagir, os níveis de fome, energia, higiene e felicidade caem proporcionalmente.

* **🧬 Ciclo de Vida e Evolução:** O bichinho passa pelos estágios de *Ovo → Bebê → Criança → Adolescente → Adulto → Ancião*. A qualidade dos seus cuidados define se ele terá evoluções raras ou se ficará rebelde/doente.

* **🎨 3 Estilos de Arte ASCII Customizáveis:** Logo no início, você escolhe a estética visual que acompanhará toda a jornada do seu pet:

  1. **Retrô 8-Bit Detalhado** Utiliza blocos de sombreamento (`█`, `▓`, `▒`, `░`) e caracteres geométricos (`▄`, `▀`, `■`) para criar sprites estilo pixel-art clássico com profundidade, contorno definido, chão/plataforma e ícones de status flutuantes (como notas musicais `♪`, gotas de suor `💧` ou `Zzz`).

  2. **Kaomoji Cênico** Vai além do rosto isolado; combina expressões faciais super detalhadas (ex: `(つ✧ω✧)つ`, `(๑•́ ₃ •̀๑)`) com braços, patinhas, objetos na mão, partículas de emoção (`*:･ﾟ✧`, `💢`, `♨️`) e pequenas linhas de cenário ao redor para formar uma micro-cena expressiva de 3 a 5 linhas.

  3. **Ilustrado / Sketch Completo** Arte ASCII ampla (de 7 a 12 linhas dentro da tela) usando traços finos (`/`, `\`, `_`, `|`, `(`, `)`, `~`, `*`) com detalhes anatômicos (orelhas, cauda, textura de pelo/escamas, olhos expressivos) e elementos de ambiente ao fundo (almofadas, tigela de comida, janela, estrelas ou nuvens).

* **🧠 Personalidade Adaptativa:** O jeito como você conversa molda o caráter e os gostos da criatura.

* **🎲 Eventos Aleatórios e Minigames:** Ele pode fazer bagunça na tela, ter sonhos estranhos, encontrar itens ou desafiar você para jogos rápidos de texto.

## 📄 Onde está o Prompt?

Todo o código-fonte (prompt de sistema) necessário para iniciar o jogo está disponível no arquivo [**`PROMPT.md`**](./PROMPT.md) aqui neste repositório.

## 🚀 Como Jogar

Você pode jogar de duas maneiras: iniciando uma conversa comum ou criando um **Gem** personalizado (recomendado para acesso rápido e compartilhamento).

### Opção 1: Executar diretamente em um Chat comum

1. Abra o arquivo [**`PROMPT.md`**](./PROMPT.md) neste repositório e copie todo o seu conteúdo.

2. Acesse o **Google Gemini** (pelo navegador ou aplicativo).

3. Inicie uma **Nova Conversa**, cole o prompt copiado e envie.

4. O Gemini exibirá o painel de status inicial, o ovo prestes a rachar e pedirá que você escolha um **nome** e o **estilo de arte ASCII**.

5. **Dica:** Fixe essa conversa no topo do seu menu lateral para lembrar de alimentar e cuidar do seu pet todos os dias!

### Opção 2: Criar um Gem (Modo Recomendado)

Salvar o jogo como um **Gem** cria um atalho dedicado no seu Gemini, evitando que você precise copiar e colar o prompt toda vez que quiser começar um novo ciclo, além de permitir compartilhar o jogo via link com amigos.

> **📢 Aviso de Atualização do Google Gemini (Migração para Habilidades):**
> A partir de **17 de novembro de 2026**, o Google iniciará a transformação automática de todos os **Gems** em **Habilidades**. Até a conclusão da migração, seus Gems continuarão funcionando e podendo ser editados normalmente. Como este projeto utiliza apenas instruções de texto (sem anexos externos), ele será convertido sem perdas, mas recomenda-se manter o arquivo `PROMPT.md` salvo como backup.

#### 💻 Criando o Gem pelo Navegador (Computador)

1. Acesse [gemini.google.com](https://gemini.google.com) e faça login na sua conta Google.

2. Clique no **ícone de engrenagem (Configurações)** no canto inferior esquerdo (ou no menu lateral) e selecione **Gems** (ou **Gerenciador de Gems**).

3. Clique no botão **+ Novo Gem**.

4. No campo **Nome**, dê um título ao jogo (ex: *Bichinho Virtual*).

5. Abra o arquivo [**`PROMPT.md`**](./PROMPT.md), copie todo o conteúdo e cole dentro do campo **Instruções**.

   > *Nota:* Se desejar, você pode apagar a frase *"O jogo começa agora, no momento em que eu enviar esta mensagem"* na primeira linha para que o Gem aguarde o seu primeiro "Oi" ou "Iniciar".

6. Clique em **Salvar** no canto superior direito.

7. Selecione o Gem criado (ou a Habilidade correspondente após a migração) e envie qualquer mensagem (ex: *"Começar"*) para receber seu ovo!

#### 📱 Criando e Jogando pelo Aplicativo Android

> **⚠️ Importante:** O aplicativo nativo do Gemini para Android permite *jogar* com seus Gems, mas **não possui o botão de criação/edição** na interface do app. Para criar o Gem pelo celular, siga os passos abaixo:

1. Abra o **navegador de internet** do seu celular Android (Chrome, Firefox, Brave, etc.) e acesse [**gemini.google.com**](https://gemini.google.com).

2. Toque no menu de **três pontinhos (`⋮`)** no canto superior direito do navegador e ative a opção **Para computador** (ou *Versão para desktop*).

3. Com a interface completa carregada, toque no **ícone de engrenagem (Configurações)** no menu lateral, acesse **Gems / Gerenciador de Gems** e toque em **+ Novo Gem**.

4. Preencha o **Nome**, cole o conteúdo de [**`PROMPT.md`**](./PROMPT.md) no campo **Instruções** e toque em **Salvar**.

5. Agora, basta fechar o navegador e abrir o **aplicativo oficial do Gemini no Android**. O seu novo Gem já estará sincronizado e pronto para jogar!

## 🤝 Contribuições e Customizações

Sinta-se à vontade para fazer um *fork* deste repositório e modificar o `PROMPT.md` para criar variações temáticas (como pets Cyberpunk, criaturas mágicas, alienígenas ou sistemas de economia com lojinha de itens).

## 📌 Versão e Licença

* **Versão:** 1.0
* **Licença:** Este projeto está licenciado sob a **Licença MIT** — consulte o arquivo [`LICENSE`](./LICENSE) para mais detalhes.
