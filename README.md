# 🧩 Guia de Uso: Protetor e Embaralhador de Carteira (BIP39)

Bem-vindo! Esta ferramenta foi criada para adicionar uma camada extra de segurança à sua carteira de criptomoedas (suas 12 ou 24 palavras). 

Em vez de guardar suas palavras na ordem correta, nós vamos **escondê-las em um formato diferente** e **embaralhar a ordem**. Para voltar ao normal depois, você precisará de uma **Chave de Recuperação**. 

Pense nisso como desmontar um quebra-cabeça e criar um mapa do tesouro que só você sabe ler.

---

## 🛠️ Fase 1: Criando o seu Quebra-Cabeça

### Passo 1: Inserir a Carteira Original
1. Abra o arquivo no seu navegador.
2. Na seção **"1. Insira sua Carteira Original"**, digite ou cole as suas 12 ou 24 palavras (separadas por espaço).
3. Clique no botão **"Analisar & Codificar"**.
4. A ferramenta vai traduzir suas palavras para a linguagem do computador (Binário e Numérico). *Você não precisa anotar nada nesta etapa.*

### Passo 2: Embaralhar e Esconder
1. Vá para a seção **"2. Embaralhar & Gerar Chave"**.
2. Clique no botão **"Gerar Puzzle (Embaralhar)"**.
3. Agora a mágica acontece! A ferramenta vai gerar duas coisas vitais:
   * **Sua Carteira Embaralhada:** Ela aparecerá em 3 formatos (Palavras fora de ordem, Binário e Numérico). 
   * **Sua Chave de Desembaralhamento:** Esta é a "senha" para desfazer a bagunça. Ela também aparece em 3 formatos (3 Palavras, Binário e Numérico).

---

## 🔐 Fase 2: Como guardar com segurança (Muito Importante!)

Para que sua carteira fique segura, você **nunca deve guardar a Carteira Embaralhada e a Chave no mesmo lugar**. Se alguém achar os dois, conseguirá montar o quebra-cabeça.

Você precisa escolher **UM formato** para a Carteira e **UM formato** para a Chave e anotá-los. 

**Exemplo de como esconder:**
* **No Cofre de casa (A Carteira):** Você anota o código **Numérico Gigante** (da Carteira Embaralhada) num papel. Quem olhar, vai achar que é só uma sequência matemática sem sentido.
* **Na sua gaveta do escritório (A Chave):** Você anota as **3 Palavras** da Chave. Quem achar, não fará ideia do que aquelas três palavras soltas significam.

*Dica: Você pode usar qualquer combinação. Pode guardar o Binário da carteira e o Número da chave, o que for mais fácil para você disfarçar!*

---

## 🔄 Fase 3: Como recuperar sua carteira no futuro

Quando você precisar acessar suas criptomoedas novamente e quiser descobrir a ordem correta das suas 12 ou 24 palavras originais:

1. Abra a ferramenta e vá direto para a seção **"3. Recuperar Carteira Original"** (a caixa de borda vermelha).
2. No campo **"Dados da Carteira"**, digite o que você guardou (pode colar aquele Número Gigante, o Binário cheio de zeros e uns, ou as palavras embaralhadas).
3. No campo **"Chave de Recuperação"**, digite a sua chave (pode ser as 3 palavras, o número curto ou o binário curto).
4. Clique no botão vermelho **"Restaurar Carteira"**.
5. Pronto! Suas palavras originais aparecerão na tela, na ordem exata e prontas para uso.

---

## ⚠️ Dicas de Segurança
* **Use Offline:** Para segurança máxima, abra este arquivo HTML em um computador que esteja desconectado da internet no momento de gerar ou recuperar sua carteira.
* **Não salve em Nuvem:** Evite tirar fotos ou salvar os códigos no Google Drive, iCloud ou WhatsApp. Anote no papel ou grave em metal.
* **Faça um teste:** Antes de transferir dinheiro para essa carteira, faça o processo inteiro (gere o puzzle, anote os códigos, feche o navegador, abra de novo e tente recuperar). Tenha certeza de que entendeu como funciona!

* Abrir no browser sem download:
https://htmlpreview.github.io/?https://github.com/guile84/cripto_way/blob/main/BIP39_Encoder_Cipher_Puzzle
