# Changelog — Fênix | Simulado de Atendimento

## Versão 1.2.1
Criada em 21/11/2026 · modificada em 21/11/2026

- Ícone oficial do Simulador de Atendimento aplicado ao app: tela de abertura, cadastro, login, Sobre, ícone da aba do navegador e ícone de instalação (Android, iPhone e computador), inclusive em formato adaptável (maskable).
- Novos arquivos de ícone: icone-192.png, icone-512.png, icone-maskable-512.png e apple-touch-icon.png (publicar junto do index.html).
- Manifesto do app com endereços absolutos de início e escopo, para instalar em qualquer pasta do GitHub Pages.
- A águia provisória continua no menu lateral e no relatório em PDF, até a Fenix_Logo_Branca oficial ser enviada.

## Versão 1.2
Criada em 21/11/2026 · modificada em 21/11/2026

- Nova área "Aprender" (menu, tela inicial e "Mais"), com dois cenários de aprendizado que usam os 120 roteiros e não valem nota.
- Chamada Modelo: o sistema faz o atendente e o cliente com duas vozes e legenda; anotações do que cada fala faz bem; cadência por passo (palavras por fala, fala do cliente, pausas, perguntas); escolha de passo, velocidade e leitura sem som.
- Chamada Modelo: versão com erros típicos para comparar; "Pare e responda" com comparação; "Repetir depois do modelo" com gravação que fica só na tela.
- Troca de Lugar: o aluno é o cliente, com cartão da situação, respostas prontas, voz ou digitação, medidor de paciência e atendente bom ou ruim sorteado às cegas.
- Troca de Lugar: nota de 0 a 10, falhas percebidas e despercebidas, palpite bom/ruim, reflexão em três perguntas guardada só no aparelho.
- Novas conquistas: Ouvido treinado, Mudou de lado, Olhar de cliente. XP na primeira conclusão de cada roteiro.
- Registrado para a próxima versão: Duelo de alunos (dois aparelhos), que depende da nuvem do Fênix Core.

## Versão 1.1
Criada em 21/11/2026 · modificada em 21/11/2026

- Inclui os 120 roteiros de fábrica (10 cenários × 12 personas) dentro do app, com as falas-modelo do atendente e as respostas do cliente nos 8 passos.
- Dois cenários novos: "Oscilação de energia e aparelho danificado" e "Aviso de corte com fatura já paga". Duas personas novas: "Prolixo" e "Exigente (pede supervisor)".
- Cidades, bairros e ruas dos roteiros trocados por nomes fictícios; a abertura é sempre "Atendimento {EMPRESA}" (padrão Fênix).
- Tela Roteiros por cenário, com "Ver" (roteiro completo), "Baixar .md" e catálogo em .json.
- Treino guiado mostra o diálogo completo do passo (A. e C.); a preparação da chamada mostra perfil do cliente, objetivo e cuidado.
- Relatório mostra o que o avaliador observa e os erros comuns da persona.
- Liberação por nível passa a valer por combinação de cenário e persona.
- Checklist adaptado ao roteiro: item que o roteiro não pede (ex.: ponto de referência) não é cobrado.
- Correção: um item cumprido no mesmo instante do início da chamada podia contar como não cumprido e travar os seguintes.
- Correção: a meta do passo 2 inclui os 20 s de pausa (65 s); metas dos passos 6 e 8 seguem os roteiros (20 s e 15 s).
- Correção: avisos falsos de "fora de ordem" e "não confirmou o protocolo" quando o aluno seguia o roteiro.

## Versão 1.0
Criada em 20/11/2026 · modificada em 20/11/2026

- Primeira versão do app (PWA, Web + Mobile), selo `v1.0 | c 5.8`, Livro das Regras v5.8.
- Simulação por voz em 8 passos, cronômetros, 8 cenários, 10 personas, avaliação, relatório em tela e PDF, métricas, gamificação, supervisor, gravação só no aparelho, teste de 15 dias, backup, exclusão de conta, tema escuro e offline.
