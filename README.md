<div align="center">

# WWE SmackDown vs. Raw 2011

### Tradução para português brasileiro 🇧🇷

**Menus, textos e legendas · PC · v0.3 em testes**

Reviva as rivalidades, acompanhe a história e entenda os objetivos em português.

**[⬇️ BAIXAR A TRADUÇÃO v0.3](https://github.com/Bielfla27/wwe-svr2011-ptbr/raw/refs/heads/main/WWE_SvR2011_PTBR_v0.3.7z)**

[Como instalar](#como-instalar) · [Compatibilidade](#compatibilidade) · [Relatar um problema](https://github.com/Bielfla27/wwe-svr2011-ptbr/issues/new)

</div>

---

## Sobre o projeto

Este projeto nasceu da vontade de revisitar um jogo marcante e finalmente entender melhor suas histórias, menus e objetivos — e de compartilhar essa experiência com outras pessoas.

A tradução comunitária PT-BR traz os textos de **WWE SmackDown vs. Raw 2011** para o português brasileiro, com um instalador que prepara uma cópia separada do jogo.

> **Esta versão traduz textos e legendas. As vozes continuam em inglês.**
> O pacote não inclui o jogo. É necessário ter a instalação compatível funcionando no seu computador.

## O que está incluído

| Conteúdo | Nesta versão |
| --- | --- |
| Menus e interface | Textos traduzidos, incluindo opções do port PC |
| Mensagens e instruções | Avisos e orientações em português |
| Modos de criação | Textos de opções e configurações |
| Road to WrestleMania | Legendas, diálogos escritos e objetivos |
| Instalador | Verificação de compatibilidade e criação de uma cópia separada |
| Tutorial | Passo a passo completo, disponível sem internet |
| Remoção | Utilitário para retirar a tradução preservando o jogo e os saves |

Nomes próprios, marcas, alguns termos de luta e rótulos técnicos foram preservados. Textos que fazem parte de imagens podem continuar em inglês.

## Download

### [📦 WWE_SvR2011_PTBR_v0.3.7z](https://github.com/Bielfla27/wwe-svr2011-ptbr/raw/refs/heads/main/WWE_SvR2011_PTBR_v0.3.7z)

Baixe o arquivo acima e extraia todo o conteúdo. Dentro da pasta, você encontrará:

| Arquivo | Para que serve |
| --- | --- |
| **Instalar traducao PT-BR.exe** | Instalar a tradução em uma nova cópia do jogo |
| **Tutorial.html** | Ler o tutorial completo no navegador |
| **LEIA-ME.txt** | Consultar as instruções rápidas |
| **VALIDACAO.txt** | Conferir o que foi testado e os limites desta edição |
| **SHA256.txt** | Conferir a integridade dos arquivos extraídos |
| **fonte/** | Consultar o código do instalador |

Mantenha os arquivos que acompanham o instalador juntos na pasta extraída.

## Compatibilidade

| Requisito | Versão necessária |
| --- | --- |
| Jogo | Port para PC **2.1.3 (745aaf2)** |
| Sistema | Windows de **64 bits** |
| Componente | .NET Framework **4.8** |
| Espaço livre | Suficiente para mais uma cópia completa do jogo — cerca de **7 GB** na edição testada |

O instalador verifica três arquivos principais antes de começar. Uma versão diferente ou arquivos principais modificados podem impedir a instalação.

Este pacote foi preparado para o port PC indicado acima. Não é aplicado diretamente em ISO, versão de console ou emulador.

## Como instalar

1. **Baixe e extraia** o arquivo `.7z` completamente, usando um descompactador compatível.
2. **Feche o jogo** antes de continuar.
3. Abra **Instalar traducao PT-BR.exe** na pasta extraída.
4. Em **Procurar…**, escolha a instalação original em inglês, na pasta que contém `svr2011.exe` e a pasta `pac`.
5. Escolha uma **nova pasta de destino**, fora da pasta original. O instalador sugere um nome terminado em `_PTBR`.
6. Clique em **Criar cópia e instalar** e aguarde a mensagem de conclusão.
7. Na nova pasta, abra **Jogar em portugues.exe**.
8. Para acompanhar as cenas, ative **LEGENDAS** em **OPÇÕES DE JOGO**, se necessário.

**Exemplo de pastas:**

```text
D:\Jogos\WWE2011        ← instalação original
D:\Jogos\WWE2011_PTBR   ← nova cópia em português
```

O instalador preserva a pasta original e copia os saves que estiverem dentro dela. Ele não precisa baixar arquivos durante a instalação.

Para instruções detalhadas, abra **Tutorial.html**, incluído no pacote.

## Saves e progresso

Os saves existentes dentro da pasta do jogo são copiados para a nova instalação. A partir daí, **cada cópia mantém seu próprio progresso**.

Na versão PT-BR, o save fica em:

```text
Saves\SaveData.dat
```

Se você usa uma pasta personalizada de saves fora da instalação original, transfira uma cópia desses arquivos para `Saves` da nova instalação, com o jogo fechado. Guarde um backup antes de substituir qualquer save.

## Como remover a tradução

1. Feche o jogo.
2. Na pasta da cópia em português, abra **Remover traducao.exe**.
3. Confirme a remoção.

O utilitário desativa o pacote e remove os arquivos gerados que continuam intactos, preservando o jogo, as configurações e os saves. Arquivos modificados depois da instalação são mantidos.

Para jogar em inglês nessa cópia, abra `svr2011.exe`. O utilitário de remoção e a pasta `.ptbr` podem permanecer como registro.

## Estado da versão 0.3

**Esta é uma versão inicial para testes com a comunidade.**

- **12.871 entradas traduzidas** nos catálogos de textos e diálogos.
- **191 textos da interface PC** traduzidos.
- **114 verificações automatizadas** do instalador aprovadas.
- Abertura do jogo, menus e uma amostra de legendas ou objetivos do modo história confirmados em teste manual.

Essas contagens não representam uma revisão visual de todas as telas. **A campanha inteira ainda não foi revisada**, e podem existir textos cortados, termos a ajustar ou trechos que permaneçam em inglês.

Os testes do instalador foram feitos em uma pasta separada, com os arquivos reais necessários aos patches e saves simulados. Consulte `VALIDACAO.txt` para os detalhes.

## Dúvidas frequentes

<details>
<summary><strong>O instalador diz que a versão é incompatível.</strong></summary>

Confira se selecionou a pasta correta e se está usando o port **2.1.3 (745aaf2)**. Os arquivos principais precisam corresponder à edição usada na tradução. O instalador interrompe o processo quando essa conferência falha.

</details>

<details>
<summary><strong>O jogo continua em inglês.</strong></summary>

Abra **Jogar em portugues.exe** dentro da nova pasta. Um atalho antigo pode iniciar a instalação original. Para as cenas, confira também se as legendas estão ativadas nas opções de jogo.

</details>

<details>
<summary><strong>A instalação foi cancelada ou interrompida.</strong></summary>

A pasta original permanece preservada. Se uma cópia parcial foi criada, ela fica identificada por `INSTALACAO_INCOMPLETA.txt`. Não use essa cópia; escolha uma nova pasta de destino para tentar novamente.

</details>

<details>
<summary><strong>O Windows bloqueou o instalador.</strong></summary>

Esta distribuição inicial não possui assinatura digital. Confira a origem do pacote e registre a mensagem exibida para análise. Não desative a proteção do computador para executar o instalador.

</details>

<details>
<summary><strong>Posso compartilhar a tradução?</strong></summary>

Compartilhe o link deste repositório ou o pacote de tradução. Cada pessoa precisa ter a própria instalação compatível. Não distribua sua pasta completa do jogo, saves, configurações ou dados de conta.

</details>

## Ajude a melhorar

Encontrou um texto estranho, uma tradução cortada ou um problema de instalação? **[Abra um relato na aba Issues](https://github.com/Bielfla27/wwe-svr2011-ptbr/issues/new)** e inclua:

- O modo de jogo e a tela em que aconteceu.
- O texto exibido e, se possível, uma captura de tela.
- O que você esperava encontrar.
- A versão do port e da tradução utilizada.
- Para erros de instalação, a mensagem completa apresentada.

Não inclua dados pessoais ou saves no relato.

## Créditos

Projeto compartilhado por **[Bielfla27](https://github.com/Bielfla27)**, com o objetivo de tornar essa experiência mais acessível à comunidade brasileira.

Tradução comunitária **não oficial**, sem afiliação ou endosso da WWE, THQ ou dos demais titulares. As marcas e os conteúdos originais pertencem aos respectivos titulares.

---

<div align="center">

**Feito para quem quer voltar ao ringue e entender cada objetivo. 🇧🇷**

</div>
