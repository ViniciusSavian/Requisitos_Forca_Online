# Requisitos de Software - Forca Online

Nesse documento é possível visualizar os requisitos funcionais e não funcionais para que deve ter em um jogo de forca online.

## Requisitos Funcionais

Os requisitos funcionais são as especificações que descrevem as funcionalidades que um sistema deve oferecer para atender às necessidades dos usuários. Eles detalham o que o sistema deve fazer e abrangem ações, cálculos, processos e interações com outros sistemas. Para um jogo de forca online, nós temos os seguintes requisitos funcionais:

RF01 - O sitema deve permitir que o jogador escolha entre jogar sozinho ou multiplayer

RF02 - O sistema deve permitir a seleção do nível de dificuldade (fácil, médio, difícil)

RF03 - O sistema deve exibir uma palavra oculta com espaços representando letras que ainda não foram descobertas.

RF04 - O sistema deve permitir que o jogador insira uma letra para tentar adivinhar a palavra.

RF05 - O sistema deve verificar se a letra inserida está na palavra e atualizar a exibição.

RF06 - O sistema deve reduzir a quantidade de tentativas restantes quando o jogador errar uma letra.

RF07 - O sistema deve encerrar a partida quando a palavra for descoberta ou quando o jogador perder todas as tentativas.

RF08 - O sistema deve gerar palavras aleatórias com base em um banco de dados predefinido.

RF09 - O sistema deve permitir o usuário escolher a palavra na sua vez em partidas multiplayer.

RF10 - O sistema deve exibir uma mensagem de vitória quando o jogador adivinhar a palavra corretamente.

RF11 - O sistema deve exibir uma mensagem de derrota quando o jogador esgotar suas tentativas.

RF12 - O sistema deve registrar e exibir a pontuação do jogador ao final de cada partida.

## Requisitos Não Funcionais
Requisitos não funcionais se referem a como as funcionalidades e serviços de uma solução serão oferecidos ao usuário, contemplando características de qualidade de software, como segurança, velocidade, compatibilidade e outros.

No desenvolvimento de requisitos não funcionais costuma ser utilizada a norma ISO/IEC 25010, que define modelos de avaliação da qualidade de softwares e sistemas (ISO 25000, 2024). A norma define 8 características principais, com subcategorias que detalham as especificações. São elas: Funcionalidade, Confiabilidade, Usabilidade, Eficiência, Compatibilidade, Segurança, Manutenibilidade e Portabilidade.

Para um jogo da forca online, nós temos os seguintes requisitos não funcionais:

**Funcionalidade**

RNF01 - O sistema deve garantir que todas as palavras geradas sejam válidas no idioma selecionado.

RNF02 - O jogo deve impedir que um jogador insira a mesma letra duas vezes na mesma tentativa.

**Confiabilidade**

RNF03 - O servidor deve realizar backups automáticos das partidas a cada 5 minutos.

RNF04 - O jogo deve ser capaz de salvar e recuperar automaticamente o progresso do jogador em caso de falha da conexão.

**Usabilidade**

RNF05 - O sistema deve oferecer diferentes esquemas de cores e fontes para melhorar a legibilidade.

RNF06 - O jogo deve fornecer feedback visual e sonoro ao jogador ao acertar ou errar uma letra.

**Eficiência**

RNF07 - As respostas do servidor devem ter uma latência inferior a 200 ms para jogadores na mesma região.

RNF08 - O jogo deve processar cada jogada e atualizar a interface em menos de 100 ms.

**Compatibilidade**

RNF09 - O jogo deve ser compatível com os navegadores Chrome, Firefox e Edge nas versões dos últimos dois anos.

RNF10 - O jogo deve ser acessível tanto em dispositivos desktop quanto móveis sem perda de funcionalidade.

**Segurança**

RNF11 - As senhas dos usuários devem ser armazenadas usando hashing.

RNF12 - O sistema deve bloquear tentativas de login após cinco falhas consecutivas por 15 minutos.

**Manutenibilidade**

RNF13 - O código-fonte do sistema deve ser modularizado para facilitar futuras melhorias e correções.

RNF14 - O jogo deve registrar logs de erros automaticamente e enviá-los ao servidor para análise.

**Portabilidade**

RNF15 - O jogo deve permitir a migração de dados de um servidor para outro sem perda de informações.

RNF16 - O sistema deve permitir a execução em diferentes navegadores sem necessidade de plugins adicionais.