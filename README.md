[Fork do projeto ldurans](https://github.com/ldurans/izing.open.io)

## Diferenças dessa versão repositorio ldurans

Versão: v2.2.0 (18-05-2024)

Melhorias:
Liberado Painel SaaS - para acessar use usuario: super@izing.io senha: 123456

Versão: v2.1.0 (14-05-2024)
Bug Fixes:

- Correção encaminhar mensagens
- Correção envio arquivos
- Correção bug montar fluxo (perdia etapa 2 cliques)
- Correção bug envio video
- Correção bug apagar mensagem
- Correção bug apagar mensagem agendada
- Correção arquivos sumir do chatbot

Melhorias:
- Arquivo server.js frontend para facilitar instalacao
- Atualizacao versao whaapp.js^1.23.1-alpha.6 para melhorar a conexao whatsapp
- Abas aberto, pedente, fechado e grupos no painel atendimento 
- Tickets fechados ja vir selecionado atendimento(como coloquei abas para separar atendimentos achei melhor fechados já aparecer)
- Fundo dark whatsapp para modo escuro 
- Botao espiar ticket e adaptacao layout
- Mudanca cache local melhora na conexão(depois varios testes veriquei que com essa mudança a conexão fica mais rapida e da menos erros leitura QRCODE)
- Update libs instagram para melhor conexão com instagram
- Botao modelo planilha para importar contatos 
- Botao modelo POSTMAN api
- Emoji na mensagem de despedida
- Variáveis nas campanhas
- Aceitar audios gravados no whatsapp-formato .ogg
- Evitar duplicar contatos na importação *créditos Luiz Alvez
- Conversão de audio de ogg para mp3 para suporte sistema IOS (necessário ter instalado ffmpeg - apt install ffmpeg)
- Suporte receber localização
- Retirada de bloqueio que não deixava voltar para etapa anterior do fluxo

# Izing

Um sistema para gestão de atendimento multicanais centralizado.

usuario SaaS: super@izing.io senha: 123456

**IMPORTANTE**: não garantimos que a utilização desta ferramenta não irá gerar bloqueio nas contas utilizadas. São bots que em sua maioria utilizam APIs secundarias para comunicação com os fornecedores dos serviços. Use com responsabilidade!

<br/>

## Principais funcionalidades

- Multíplos canais de atendimento ✅
- Multíplos usuários simultâneos por canais de atendimento ✅
- Iniciar conversa com contatos existentes (whatsapp) ✅
- Construção de Chatbot interativo ✅
- Enviar e receber mensagens ✅
- Enviar e receber mídias diversas (imagens/áudio/documentos) ✅
- Multiempresas (abordagem de base compartilhada)

<br/>

## Instalando
Seguem links sugerimos:
-  [Como Instalar o IZING - Método 2024 Video](https://youtu.be/bZ-jXRtcGyc?si=B8oQxv0V0V36fgrF)
-  [Como Instalar o IZING AAPANEL - Método 2024 Video](https://www.youtube.com/watch?v=pw5KMtdVw0s)

-  [Como Instalar o IZING VPS - Método 2024 - UBUNTU 20, 22](docs/INSTALL_VPS_UBUNTU_20_22.md)

-  [Instalador automatico IZING LOCALHOST](https://github.com/cleitonme/izing.local)
-  [Instalador automatico](https://github.com/cleitonme/izing.instalador)
<br/>


## Atualizando

Tem script "update-izing" para facilitar atualização ele somente funciona se tiver instalado pasta izing.io

sh update-izing

<br/>

**IMPORTANTE**: verifique sempre o .env.example e ajuste o seu .env antes de atualizar, uma vez que algumas novas variáveis podem ser adicionadas.


<br/>

## FIQUE ATENTO

A utilização desta ferramenta é feita por sua conta e risco. O código é aberto e todos podem contribuir.

Este projeto não é afiliado, associado, autorizado, endossado por, ou de qualquer forma oficialmente ligado à WhatsApp, ou a qualquer uma das suas filiais ou afiliadas. O website oficial da WhatsApp pode ser encontrado em <https://whatsapp.com>. "WhatsApp", bem como nomes, marcas, emblemas e imagens relacionadas são marcas registadas dos seus respectivos proprietários.

## Recomendação de VPS boa e barata

-  [Powerful cloud VPS & Web hosting.](https://control.peramix.com/?affid=58)

## Consultoria particular

Para quem gostaria de uma consultoria ou que eu faça instalação pode chamar no whatsapp 48 999416725 (será cobrado por isso)
