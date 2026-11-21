# Fênix | Simulado de Atendimento - Roteiros

## Cenário 04 - Solicitação de religação

Versão 1.1 - 20/11/2026

**Objetivo de aprendizado:** Confirmar pagamento, checar débitos remanescentes e pessoas dependentes de energia, e informar o prazo de religação.

**Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.

**Convenção:** A. = atendente (aluno, modelo de fala); C. = cliente (convertido em voz sintética, voz sorteada); [PAUSA] e [ESPERA] marcam o tempo em que o cliente fica em silêncio.

**Aviso:** Dados fictícios: nomes, endereços, telefones, protocolos, valores e prazos são exemplos para treino. Nenhum roteiro cita empresa real; o atendente fala 'Atendimento Fênix' (variável {EMPRESA}). Prazos, valores e regras devem ser ajustados à política da operação onde o treino for aplicado.

**Personas deste arquivo (12):** 01 Cliente calmo; 02 Cliente nervoso; 03 Cliente irritado, que ameaça cancelar; 04 Cliente chato; 05 Cliente lento; 06 Idoso confuso; 07 Cliente apressado; 08 Cliente leigo; 09 Cliente deficiente auditivo; 10 Cliente empresarial; 11 Cliente prolixo (fala demais); 12 Cliente exigente (pede supervisor)

---

## Roteiro 04.01 - Solicitação de religação x Cliente calmo

**Cliente (fictício):** Helena Duarte | **Dificuldade:** 3/8 | **Libera no nível:** Iniciante | **Persona nova**

- **Perfil:** Cliente educado e colaborativo; serve de fase de entrada para fixar o roteiro dos 8 passos.
- **Voz sugerida:** Ritmo normal, tom suave | **Paciência:** 95/100
- **Técnica-chave:** Seguir o roteiro com naturalidade, sem pular itens do checklist.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Acelerar porque o cliente é fácil e esquecer a confirmação positiva. / Não chamar o cliente pelo nome. / Esquecer de informar o e-mail da pesquisa em até 48 h.
- **O avaliador observa:** Todos os 8 passos completos. / Tempo dentro das metas. / Linguagem clara e cordial.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação], meu nome é Helena Duarte.  
**A.** Senhora Helena, no que posso ajudar?  
**C.** A minha energia foi cortada hoje cedo e eu já paguei a fatura.  
**A.** Senhora Helena, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhora Helena, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Claro, a unidade consumidora é 402716-0.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** Sem problema, eu aguardo.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhora Helena, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** Sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Sim, número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Sim.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Claro, vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Sim, não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Não, ninguém.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhora Helena!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Ao lado da farmácia Vida Nova.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Sim, ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhora Helena, foi gerado um protocolo. A senhora pode anotar?  
**C.** Sim, vou pegar uma caneta e um papel.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Já peguei a caneta, pode ditar.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Ok.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** Claro, não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Claro, vou avaliar com sinceridade.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Obrigada, boa noite.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.02 - Solicitação de religação x Cliente nervoso

**Cliente (fictício):** Marcos Tavares | **Dificuldade:** 5/8 | **Libera no nível:** Pleno

- **Perfil:** Cliente agitado e ansioso; fala rápido, interrompe e pede urgência.
- **Voz sugerida:** Ritmo acelerado, tom agudo, respiração curta | **Paciência:** 45/100
- **Técnica-chave:** Validar a emoção, falar com calma e devolver o controle em passos curtos.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Falar mais rápido que o cliente. / Dizer 'calma' em tom de ordem. / Prometer prazo que o sistema não confirma.
- **O avaliador observa:** Frase de empatia logo no início. / Passos explicados em frases curtas. / Sem promessa fora do sistema.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]... eu preciso de ajuda urgente! Meu nome é Marcos Tavares!  
**A.** Senhor Marcos, no que posso ajudar?  
**C.** Ai, meu Deus, a minha energia foi cortada hoje cedo e eu já paguei a fatura!  
**C.** Eu não aguento mais isso! Vocês têm que resolver esse corte de energia agora!  
**A.** Entendo a sua preocupação, senhor Marcos, e vou cuidar disso agora com o senhor. Vamos resolver juntos, passo a passo.  
**A.** Senhor Marcos, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Marcos, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Olha, a unidade consumidora é 402716-0, rápido por favor!  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** Vai demorar muito? Eu estou ficando desesperado!  
**A.** São só 20 segundos, senhor Marcos. Já volto com o senhor.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Marcos, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** Tá, sim, é nesse endereço mesmo!!  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Ai, meu Deus, sim!  
**C.** Por que eu preciso fazer isso? Não dá para mandar alguém logo?  
**A.** Essas verificações aceleram o atendimento e evitam uma visita desnecessária. É rápido.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91, rápido por favor!  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Tá, não, ninguém!!  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Marcos!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** E até quando isso fica resolvido? Preciso de um prazo agora!  
**A.** Vou informar o prazo previsto assim que o protocolo for gerado, senhor Marcos. Só preciso fechar os dados.  
**C.** Ao lado da farmácia Vida Nova.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse!  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Marcos, foi gerado um protocolo. O senhor pode anotar?  
**C.** Olha, sim, vou pegar uma caneta e um papel, rápido por favor!  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Pode ser rápido? Estou com a mão tremendo, nem consigo escrever!  
**A.** Fique tranquilo, vou falar devagar e confirmo cada número com o senhor.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Tá, ok!!  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Não, só quero que resolva!  
**A.** Fica registrado, senhor Marcos. Tudo o que conversamos seguirá no protocolo.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Tá, tá, pode dar a nota que for.  
**A.** Agradeço, senhor Marcos. A pesquisa é rápida e a sua opinião ajuda a melhorar.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Espero que cumpram, hein!  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.03 - Solicitação de religação x Cliente irritado, que ameaça cancelar

**Cliente (fictício):** Roberto Nunes | **Dificuldade:** 7/8 | **Libera no nível:** Sênior

- **Perfil:** Cliente já ligou outras vezes; reclama alto, acusa a empresa e ameaça cancelar o contrato e reclamar em órgãos.
- **Voz sugerida:** Ritmo firme, tom alto e seco | **Paciência:** 25/100
- **Técnica-chave:** Pedir desculpas pelo transtorno, não rebater, assumir o caso e focar no que dá para resolver.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Rebater a acusação ou se justificar. / Dizer 'não posso fazer nada'. / Subir o tom de voz.
- **O avaliador observa:** Pedido de desculpas e assunção do caso. / Tom constante e cordial. / Registro claro do protocolo.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]. Roberto Nunes. E já adianto: é a terceira vez que eu ligo!  
**A.** Senhor Roberto, no que posso ajudar?  
**C.** Olha, a minha energia foi cortada hoje cedo e eu já paguei a fatura. Que absurdo!  
**C.** Isso é um absurdo! Se isso não for resolvido hoje, eu cancelo tudo e reclamo em todo lugar!  
**A.** Lamento muito, senhor Roberto. O senhor tem razão em estar chateado. Vou assumir o seu caso agora e fazer o possível para resolver nesta ligação.  
**A.** Senhor Roberto, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Roberto, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Escuta, a unidade consumidora é 402716-0. Vocês não sabem de nada?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** Mais espera? Vocês só me fazem esperar!  
**A.** Entendo. É uma consulta curta, de 20 segundos. Peço licença e já volto.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Roberto, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** É óbvio: sim, é nesse endereço mesmo!  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Olha, sim. Que absurdo!  
**C.** Eu não sou técnico de vocês! Mande alguém e pronto!  
**A.** Eu sei, senhor Roberto. Essas verificações são rápidas e ajudam a enviar a solução certa na primeira vez.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91. Vocês não sabem de nada?  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** É óbvio: não, ninguém!  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Roberto!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Quero um prazo certo e o nome de quem vai resolver. Senão, eu cancelo tudo!  
**A.** O prazo previsto eu informo agora, junto com o protocolo, senhor Roberto. O contato será feito antes da visita.  
**C.** Ao lado da farmácia Vida Nova.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse. Que absurdo!  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Roberto, foi gerado um protocolo. O senhor pode anotar?  
**C.** Escuta, sim, vou pegar uma caneta e um papel. Vocês não sabem de nada?  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Anota aí que eu vou reclamar no órgão regulador!  
**A.** O senhor tem esse direito, e o protocolo vai servir de registro. Posso passar o número?  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** É óbvio: ok!  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Só quero que isso seja resolvido.  
**A.** Vou deixar tudo registrado para que isso aconteça, senhor Roberto.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Não vou dar nota boa nenhuma enquanto não resolverem.  
**A.** Sem problema, senhor Roberto. A avaliação é sobre o atendimento de hoje e a sua opinião é importante.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Hunf. Tá bom.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.04 - Solicitação de religação x Cliente chato

**Cliente (fictício):** Valter Prado | **Dificuldade:** 5/8 | **Libera no nível:** Pleno

- **Perfil:** Cliente que questiona cada pergunta, pede justificativas e checa o atendente.
- **Voz sugerida:** Ritmo pausado, tom irônico | **Paciência:** 50/100
- **Técnica-chave:** Responder cada dúvida em uma frase objetiva e voltar ao roteiro com educação.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Ficar na defensiva diante das perguntas. / Dar respostas longas e se perder do passo. / Ceder e pular itens obrigatórios.
- **O avaliador observa:** Respostas curtas e corretas. / Retomada do passo após cada pergunta. / Cordialidade até o fim.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]. Valter Prado. Antes de tudo: esta ligação está sendo gravada?  
**A.** Senhor Valter, no que posso ajudar?  
**C.** Hmm, a minha energia foi cortada hoje cedo e eu já paguei a fatura. Isso vai constar no sistema?  
**C.** Por que o senhor pergunta tanto? Esses dados não estão aí no sistema?  
**A.** São perguntas rápidas, senhor Valter, para confirmar que estou falando com o senhor e resolver mais depressa.  
**A.** Senhor Valter, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Valter, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Tá, mas a unidade consumidora é 402716-0. O senhor anotou direito?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** Por que o sistema fica mudo? Não dá para consultar falando?  
**A.** Para consultar sem erro. É rápido, e se precisar, é só me chamar.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Valter, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** Se eu falar, sim, é nesse endereço mesmo.  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte. Isso vai constar no sistema?  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Hmm, sim. O senhor anotou direito?  
**C.** E se eu não quiser fazer essas verificações? Está no contrato?  
**A.** É opcional, senhor Valter, mas aumenta a chance de resolver sem visita. Posso explicar o motivo de cada uma.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Se eu falar, não, ninguém. Isso vai constar no sistema?  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Valter!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Para que o senhor precisa desses dados? Vão usar para quê?  
**A.** Somente para tratar o seu pedido e avisar o senhor sobre a equipe ou a resposta, senhor Valter.  
**C.** Ao lado da farmácia Vida Nova. O senhor anotou direito?  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Valter, foi gerado um protocolo. O senhor pode anotar?  
**C.** Tá, mas sim, vou pegar uma caneta e um papel. Isso vai constar no sistema?  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Quero que o senhor repita o protocolo duas vezes e soletre.  
**A.** Claro, senhor Valter: repito e soletro devagar, e confirmo com o senhor dígito a dígito.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Se eu falar, ok. O senhor anotou direito?  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Já que perguntou: e aquela outra dúvida que eu tinha do mês passado?  
**A.** Posso registrar essa outra dúvida em um novo protocolo, senhor Valter. Quer que eu faça isso agora?  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Qual vai ser a pergunta exatamente? Vai valer para o senhor?  
**A.** A pesquisa é sobre o meu atendimento, e a nota é de o senhor, de 0 a 10.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Anotei o seu nome. Boa tarde.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.05 - Solicitação de religação x Cliente lento

**Cliente (fictício):** Antônio Brito | **Dificuldade:** 4/8 | **Libera no nível:** Júnior

- **Perfil:** Cliente que pensa e fala devagar, demora a achar documentos e a responder.
- **Voz sugerida:** Ritmo muito lento, tom grave, pausas longas | **Paciência:** 70/100
- **Técnica-chave:** Esperar sem preencher o silêncio, fazer uma pergunta de cada vez e confirmar para ajudar a memória.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Atropelar o cliente. / Fazer duas perguntas na mesma frase. / Estourar a meta sem manter a cordialidade.
- **O avaliador observa:** Pausas respeitadas. / Uma pergunta por vez. / Cronômetro de etapa controlado.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]... (pausa de 3 s) ...meu nome é Antônio Brito.  
**A.** Senhor Antônio, no que posso ajudar?  
**C.** É... a minha energia foi cortada hoje cedo e eu já paguei a fatura... pronto.  
**C.** (pausa de 4 s) ...Pois é... como é que eu falo... esse corte de energia.  
**A.** Sem pressa, senhor Antônio. Eu aguardo. Vou perguntar uma coisa de cada vez.  
**A.** Senhor Antônio, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Antônio, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Deixa eu ver... a unidade consumidora é 402716-0... acho que é isso.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** (demora para responder) ...Ah, pode ser... pode consultar.  
**A.** Obrigado, senhor Antônio. Volto em instantes.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Antônio, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** Peraí... sim, é nesse endereço mesmo.  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte... pronto.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Deixa eu ver... sim... acho que é isso.  
**C.** Calma, que eu ando devagar... deixa eu achar o que o senhor pediu.  
**A.** Fique à vontade, senhor Antônio. Eu aguardo na linha e aviso se demorar.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 20 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** É... não, ninguém... pronto.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Antônio!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Espera... não lembro... deixa eu procurar aqui.  
**A.** Pode ir devagar. Se quiser, eu leio o que está no cadastro e o senhor me diz se está certo.  
**C.** Ao lado da farmácia Vida Nova... acho que é isso.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Antônio, foi gerado um protocolo. O senhor pode anotar?  
**C.** É... sim, vou pegar uma caneta e um papel... pronto.  
> **[ESPERA DE 10 s - o cliente pega caneta e papel.]**

**C.** Peraí... onde eu botei a caneta... pronto. Pode falar bem devagar.  
**A.** Falo devagar, em blocos de dois ou três dígitos, e confirmo com o senhor.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Deixa eu ver... ok... acho que é isso.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Ahn... deixa eu pensar... acho que não, não.  
**A.** Se lembrar de algo, é só me chamar, senhor Antônio.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Qual era a pergunta mesmo? Pode repetir?  
**A.** Claro, senhor Antônio. Repito com calma: é sobre o meu atendimento, de 0 a 10.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Está bom, obrigado, viu... boa tarde.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.06 - Solicitação de religação x Idoso confuso

**Cliente (fictício):** Maria das Graças | **Dificuldade:** 5/8 | **Libera no nível:** Pleno

- **Perfil:** Cliente idosa; mistura assuntos, repete informações e se confunde com termos e prazos.
- **Voz sugerida:** Ritmo lento, tom fraco, repete e se perde | **Paciência:** 75/100
- **Técnica-chave:** Linguagem simples, repetir com paciência, resumir em uma ideia por vez e confirmar o entendimento.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Usar jargão (UC, protocolo, aferição) sem explicar. / Falar rápido. / Pedir algo arriscado, como mexer em quadro de energia.
- **O avaliador observa:** Linguagem simples. / Repetição de dados importantes. / Sem pedir ações de risco.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação], meu filho... é a Maria das Graças. Ou será que é Maria da Graça? Maria das Graças, isso.  
**A.** Dona Maria, no que posso ajudar?  
**C.** Ah, filho, a minha energia foi cortada hoje cedo e eu já paguei a fatura, viu?  
**C.** Ai, meu filho, eu me atrapalho com essas coisas... não sei nem explicar direito esse corte de energia.  
**A.** Fique tranquila, dona Maria. Eu ajudo a senhora. Vamos por partes, uma coisa de cada vez.  
**A.** Dona Maria, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Dona Maria, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Como é que é? Ah, a unidade consumidora é 402716-0, meu bem.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** A moça disse que o sistema ia ficar mudo? Mudo? Você sumiu?  
**A.** Não, dona Maria. Eu só vou olhar o seu cadastro, em silêncio, por uns instantes, e continuo na linha.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Dona Maria, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** Deixa eu pensar, sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte, viu?  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Ah, filho, sim, meu bem.  
**C.** Eu não entendo dessas coisas, filho. Onde eu olho isso? Meu neto sabe, mas ele não está.  
**A.** Sem problema, dona Maria. Vou explicando um passo de cada vez e, se a senhora quiser, pode chamar alguém para ajudar.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 15 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Deixa eu pensar, não, ninguém, viu?  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, dona Maria!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** O que o senhor perguntou? Pode repetir? Eu me perdi.  
**A.** Claro, dona Maria. Repito devagar: preciso de um número de telefone para avisar a senhora.  
**C.** Ao lado da farmácia Vida Nova, meu bem.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Dona Maria, foi gerado um protocolo. A senhora pode anotar?  
**C.** Como é que é? Ah, sim, vou pegar uma caneta e um papel, viu?  
> **[ESPERA DE 8 s - o cliente pega caneta e papel.]**

**C.** Espera, filho, que eu esqueci o papel... achei. Pode falar bem devagar?  
**A.** Claro, dona Maria. Vou falar devagar, número por número. Se quiser, posso enviar o número também por mensagem.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Deixa eu pensar, ok, meu bem.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** Ah, tinha uma coisa... era sobre... já esqueci. O que o senhor perguntou?  
**A.** Perguntei se a senhora deseja mais alguma coisa. Se lembrar depois, é só ligar de novo, dona Maria.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Avaliar? O que é nota? De quem?  
**A.** É simples, dona Maria: a senhora vai dar uma nota de zero a dez para a minha conversa de hoje.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Deus lhe abençoe, meu filho. Tchau, tchau, tchau.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.07 - Solicitação de religação x Cliente apressado

**Cliente (fictício):** Camila Ribeiro | **Dificuldade:** 4/8 | **Libera no nível:** Júnior

- **Perfil:** Cliente com pouco tempo; quer resolver já, corta as explicações e pede para pular etapas.
- **Voz sugerida:** Ritmo rápido, tom seco, respostas curtas | **Paciência:** 40/100
- **Técnica-chave:** Ser objetivo, anunciar o tempo de cada passo e entregar o que é obrigatório sem perder a cordialidade.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Pular itens obrigatórios do checklist por pressão. / Falar rápido demais e perder clareza. / Não avisar o tempo de cada pausa.
- **O avaliador observa:** Objetividade sem pular passos. / Tempos anunciados. / Protocolo e previsão informados com clareza.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]. Camila Ribeiro. Tenho cinco minutos.  
**A.** Senhora Camila, no que posso ajudar?  
**C.** Rápido: a minha energia foi cortada hoje cedo e eu já paguei a fatura. Próxima.  
**C.** Só quero a solução para esse corte de energia, sem enrolação.  
**A.** Direto ao ponto, senhora Camila. Vou confirmar só o necessário.  
**A.** Senhora Camila, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhora Camila, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Sim, a unidade consumidora é 402716-0. Anda logo, por favor.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** Vinte segundos? Faz em dez!  
**A.** Vou o mais rápido que o sistema permitir. Já volto.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhora Camila, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** Direto: sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte. Próxima.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Sim, sim. Anda logo, por favor.  
**C.** Não tem como pular isso e já resolver?  
**A.** São verificações rápidas, de cerca de 10 segundos cada, que evitam retrabalho. Posso fazer em sequência.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 5 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Rápido: não, ninguém. Próxima.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhora Camila!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Já dei os dados! Falta muito?  
**A.** Faltam só mais duas informações, senhora Camila, e fecho o seu protocolo.  
**C.** Ao lado da farmácia Vida Nova. Anda logo, por favor.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhora Camila, foi gerado um protocolo. A senhora pode anotar?  
**C.** Rápido: sim, vou pegar uma caneta e um papel. Próxima.  
> **[ESPERA DE 3 s - o cliente pega caneta e papel.]**

**C.** Fala o número depressa, que eu anoto.  
**A.** Falo em dois blocos curtos e confirmo com a senhora.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Sim, ok. Anda logo, por favor.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** Não, é só isso. Pode encerrar.  
**A.** Registrado, senhora Camila.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Pode passar, mas rápido.  
**A.** Será bem rápido, senhora Camila. São só alguns segundos.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Tá, obrigada, tchau.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.08 - Solicitação de religação x Cliente leigo

**Cliente (fictício):** Patrícia Gomes | **Dificuldade:** 4/8 | **Libera no nível:** Júnior

- **Perfil:** Cliente que não entende termos técnicos (disjuntor, aferição, unidade consumidora) e tem receio de errar.
- **Voz sugerida:** Ritmo normal, tom inseguro, perguntas frequentes | **Paciência:** 70/100
- **Técnica-chave:** Traduzir o termo técnico em exemplo do dia a dia e confirmar se ficou claro.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Usar jargão sem explicar. / Responder 'é só ler o aparelho' sem orientar onde. / Não verificar se o cliente entendeu.
- **O avaliador observa:** Termos técnicos explicados. / Exemplos do dia a dia. / Confirmação do entendimento.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação], meu nome é Patrícia Gomes. Desculpa, eu não entendo muito dessas coisas.  
**A.** Senhora Patrícia, no que posso ajudar?  
**C.** Acho que é... a minha energia foi cortada hoje cedo e eu já paguei a fatura, eu acho.  
**C.** Eu nem sei explicar direito esse corte de energia. Qual dado eu preciso ter à mão?  
**A.** Sem problema, senhora Patrícia. Vou orientar. Quando eu pedir algo, explico onde a senhora encontra.  
**A.** Senhora Patrícia, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhora Patrícia, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Não sei bem, mas a unidade consumidora é 402716-0. Está certo?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** O que é 'cadastro'? É o que eu preenchi quando liguei a luz?  
**A.** Exatamente, senhora Patrícia: são os seus dados que a empresa guarda. Vou conferir se estão certos.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhora Patrícia, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** O que é isso? Ah, sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte, eu acho.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Não sei bem, mas sim. Está certo?  
**C.** Eu não entendo nada disso. Pode explicar de um jeito simples?  
**A.** Claro! Vou dizer o que olhar e para que serve, sem termos difíceis.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Acho que é... não, ninguém, eu acho.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhora Patrícia!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Não sei se entendi o que o senhor precisa. Pode explicar?  
**A.** Preciso de um número de telefone, senhora Patrícia, para a equipe avisar a senhora antes de chegar.  
**C.** Ao lado da farmácia Vida Nova. Está certo?  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhora Patrícia, foi gerado um protocolo. A senhora pode anotar?  
**C.** Acho que é... sim, vou pegar uma caneta e um papel, eu acho.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Protocolo? É um número que eu guardo?  
**A.** Isso, senhora Patrícia: é o número do seu pedido. A senhora guarda para acompanhar.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Não sei bem, mas ok. Está certo?  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** O que mais eu posso pedir?  
**A.** Se a senhora não precisar de mais nada, posso encerrar. Se surgir dúvida depois, é só ligar com o protocolo.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Nota? Para quê?  
**A.** É para a empresa saber se o meu atendimento foi bom, senhora Patrícia. Dura só alguns segundos.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Obrigada, desculpa o trabalho.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.09 - Solicitação de religação x Cliente deficiente auditivo

**Cliente (fictício):** Paulo Henrique Lima | **Dificuldade:** 6/8 | **Libera no nível:** Pleno

- **Perfil:** Cliente com perda auditiva parcial; pede para repetir, confunde palavras parecidas e precisa de confirmação por escrito.
- **Voz sugerida:** Ritmo lento, tom alto, pede repetições | **Paciência:** 80/100
- **Técnica-chave:** Falar devagar, pausado e claro, repetir com outras palavras, soletrar com alfabeto de apoio e oferecer canal escrito.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Aumentar o volume gritando. / Repetir exatamente a mesma frase sem reformular. / Não oferecer o protocolo por escrito.
- **O avaliador observa:** Dicção clara e ritmo lento. / Soletrar números e nomes. / Oferta de canal escrito.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]... desculpe, eu tenho dificuldade para ouvir. Meu nome é Paulo Henrique.  
**A.** Senhor Paulo, no que posso ajudar?  
**C.** Como? ... Ah, a minha energia foi cortada hoje cedo e eu já paguei a fatura.  
**C.** Por favor, o senhor pode falar mais devagar e mais alto? Preciso entender esse corte de energia direito.  
**A.** Claro, senhor Paulo. Vou falar devagar e com clareza. Se algo não ficar claro, me avise.  
**A.** Senhor Paulo, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Paulo, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Pode repetir mais devagar? ... a unidade consumidora é 402716-0. Falei certo?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** Como? O sistema ficará... o quê?  
**A.** Vou olhar o seu cadastro e ficar em silêncio por uns 20 segundos. Depois eu volto.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Paulo, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** Não ouvi bem. ... sim, é nesse endereço mesmo.  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Pode repetir mais devagar? ... sim. Falei certo?  
**C.** Não ouvi. O senhor falou o quê? Pode dizer de outro jeito?  
**A.** Claro. Vou dizer com outras palavras, mais devagar.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Como? ... Ah, não, ninguém.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Paulo!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Pode soletrar ou repetir mais devagar? Não ouvi bem o que o senhor pediu.  
**A.** Claro. Vou soletrar com apoio: P de Pedro, A de Ana...  
**C.** Ao lado da farmácia Vida Nova. Falei certo?  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Paulo, foi gerado um protocolo. O senhor pode anotar?  
**C.** Como? ... Ah, sim, vou pegar uma caneta e um papel.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Pode falar o protocolo devagar, dígito por dígito? E mandar por escrito?  
**A.** Claro, senhor Paulo. Repito número por número e também posso enviar o protocolo por mensagem.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Pode repetir mais devagar? ... ok. Falei certo?  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Como? Pode repetir a pergunta?  
**A.** Perguntei se o senhor deseja mais alguma coisa, senhor Paulo.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Como? Nota? Pode repetir a pergunta?  
**A.** É uma nota de zero a dez para o meu atendimento, senhor Paulo. Se preferir, a pesquisa também chega por e-mail.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Obrigado... boa noite. Desculpe o trabalho.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.10 - Solicitação de religação x Cliente empresarial

**Cliente (fictício):** Renata Albuquerque | **Dificuldade:** 6/8 | **Libera no nível:** Pleno

- **Perfil:** Gerente da Comercial Horizonte Ltda (empresa fictícia); linguagem formal, quer prazo, protocolo e comprovação por escrito.
- **Voz sugerida:** Ritmo ágil, tom formal e objetivo | **Paciência:** 55/100
- **Técnica-chave:** Linguagem formal, objetividade, prazos claros e registro por escrito, sem prometer além do sistema.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Informalidade excessiva. / Prometer prazo contratual sem confirmar. / Esquecer o envio do protocolo por e-mail.
- **O avaliador observa:** Linguagem formal. / Prazos e protocolo claros. / Registro por escrito oferecido.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]. Renata Albuquerque, gerente da Comercial Horizonte.  
**A.** Senhora Renata, no que posso ajudar?  
**C.** Objetivamente: a minha energia foi cortada hoje cedo e eu já paguei a fatura.  
**C.** Falo em nome da empresa. Preciso de solução para esse corte de energia e de um número de protocolo para o nosso jurídico.  
**A.** Perfeito, senhora Renata. Vou registrar todos os dados e informar o protocolo ao final.  
**A.** Senhora Renata, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhora Renata, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Para fins de registro, a unidade consumidora é 402716-0, conforme contrato.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** Quanto tempo de espera? Nossa operação está parada.  
**A.** Vinte segundos, senhora Renata. Já retorno.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhora Renata, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** Certo. sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Para fins de registro, sim, conforme contrato.  
**C.** Já fizemos essas verificações com o nosso eletricista. Podemos pular?  
**A.** Posso registrar que foram feitas pela sua equipe, senhora Renata. Peço só uma confirmação rápida do resultado.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Objetivamente: não, ninguém.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhora Renata!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Registre também o e-mail financeiro@horizonte.exemplo para retorno formal.  
**A.** Registrado, senhora Renata. Vou confirmar o e-mail por completo ao final.  
**C.** Ao lado da farmácia Vida Nova, conforme contrato.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhora Renata, foi gerado um protocolo. A senhora pode anotar?  
**C.** Objetivamente: sim, vou pegar uma caneta e um papel.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Envie também o protocolo por e-mail corporativo, por favor.  
**A.** Combinado, senhora Renata. Informo agora o número e depois enviamos por e-mail.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Para fins de registro, ok, conforme contrato.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** Solicito um resumo por escrito do atendimento.  
**A.** Registro o pedido e o resumo segue no e-mail cadastrado, senhora Renata.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Não costumo avaliar, mas darei a nota conforme o desempenho.  
**A.** Perfeito, senhora Renata. A pesquisa é rápida e a sua opinião é importante.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Obrigada. Aguardaremos a equipe.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.11 - Solicitação de religação x Cliente prolixo (fala demais)

**Cliente (fictício):** Zilda Menezes | **Dificuldade:** 5/8 | **Libera no nível:** Pleno | **Persona nova**

- **Perfil:** Cliente simpática que conta histórias e desvia do assunto; consome o tempo da chamada.
- **Voz sugerida:** Ritmo contínuo, tom amistoso, histórias longas | **Paciência:** 65/100
- **Técnica-chave:** Acolher em uma frase, interromper com gentileza e conduzir de volta ao passo.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Deixar o cliente conduzir a chamada. / Interromper de forma ríspida. / Perder o controle do tempo da etapa.
- **O avaliador observa:** Retomada gentil do passo. / Tempo total sob controle. / Todos os itens do checklist cumpridos.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação], minha filha. Zilda Menezes, mas todo mundo me chama de Dona Zilda, desde que eu morava em Monte Alto.  
**A.** Dona Zilda, no que posso ajudar?  
**C.** Então, deixa eu contar, a minha energia foi cortada hoje cedo e eu já paguei a fatura, aliás, meu cunhado também passou por isso no ano passado.  
**C.** Ah, minha filha, deixa eu contar: eu estava na cozinha fazendo o café quando minha neta ligou do Porto Claro, e aí esse corte de energia...  
**A.** Entendo, dona Zilda. Para eu ajudar logo, posso fazer uma pergunta rápida?  
**A.** Dona Zilda, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Dona Zilda, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Olha, a unidade consumidora é 402716-0, mas voltando ao assunto.  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** Ah, enquanto isso eu falo do meu vizinho, que também...  
**A.** Agradeço, dona Zilda. Vou ficar em silêncio uns segundos para consultar e já volto.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Dona Zilda, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua dos Girassóis, correto?  
**C.** Bom, sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte, aliás, meu cunhado também passou por isso no ano passado.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Então, deixa eu contar, sim, mas voltando ao assunto.  
**C.** Isso me lembra de quando o técnico veio em 2019, e foi um dia...  
**A.** Que bom que a senhora lembra, dona Zilda. Para resolver hoje, vamos ao próximo passo.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Bom, não, ninguém, aliás, meu cunhado também passou por isso no ano passado.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, dona Zilda!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Ah, o telefone? É o do fixo... não, o da minha filha, e o da minha irmã...  
**A.** Vamos anotar um só agora, dona Zilda, o mais fácil de a senhora atender. Qual é?  
**C.** Ao lado da farmácia Vida Nova, mas voltando ao assunto.  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Dona Zilda, foi gerado um protocolo. A senhora pode anotar?  
**C.** Olha, sim, vou pegar uma caneta e um papel, aliás, meu cunhado também passou por isso no ano passado.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Ah, pode falar, mas antes me deixa contar uma coisa...  
**A.** Claro, dona Zilda, só depois de anotar o número. Tem papel e caneta à mão?  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Bom, ok, mas voltando ao assunto.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** Mais uma coisa? Tem sim, deixa eu contar...  
**A.** Pode me dizer em uma frase, dona Zilda? Assim eu registro certinho.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora a senhora será redirecionada para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que a senhora possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Ah, a nota! Eu dou, mas deixa eu falar do atendimento do ano passado...  
**A.** Obrigado, dona Zilda. A pesquisa vai ser rápida, e depois eu me despeço.  
**A.** Em até 48 horas, a senhora também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Ai, que bom conversar com você, viu? Tchau, minha filha!  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---

## Roteiro 04.12 - Solicitação de religação x Cliente exigente (pede supervisor)

**Cliente (fictício):** Eduardo Falcão | **Dificuldade:** 6/8 | **Libera no nível:** Pleno | **Persona nova**

- **Perfil:** Cliente que cita direitos, exige registro por escrito, nome e matrícula do atendente e pede o supervisor.
- **Voz sugerida:** Ritmo controlado, tom frio, cita direitos | **Paciência:** 40/100
- **Técnica-chave:** Manter a calma e a postura, informar o que pode ser informado, registrar tudo e oferecer o encaminhamento ao supervisor sem perder o controle da chamada.
- **Armadilha do cenário:** Não perguntar se há equipamento de saúde dependente de energia; prometer prazo sem confirmar o pagamento.
- **Erros comuns nesta persona:** Se irritar ou se defender. / Prometer o que depende do supervisor. / Negar o direito ao registro.
- **O avaliador observa:** Postura profissional. / Registro e protocolo claros. / Encaminhamento ao supervisor conforme política.
- **Dados do chamado:** unidade consumidora 402716-0; endereço Rua dos Girassóis, 230, Parque Horizonte, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação]. Eduardo Falcão. Quero deixar claro que conheço os meus direitos e que vou registrar tudo.  
**A.** Senhor Eduardo, no que posso ajudar?  
**C.** Anote aí: a minha energia foi cortada hoje cedo e eu já paguei a fatura. Quero isso por escrito.  
**C.** Quero o seu nome completo e a sua matrícula. Isso já deveria ter sido resolvido.  
**A.** Meu nome é o que informei no início, senhor Eduardo. Vou registrar o seu pedido e o protocolo vai constar no final.  
**A.** Senhor Eduardo, qual foi a data e a forma do pagamento?  
**C.** Paguei hoje às nove horas, pelo aplicativo do banco.  
**A.** Senhor Eduardo, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Quero que conste que a unidade consumidora é 402716-0. Esse atendimento está sendo gravado?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se o senhor precisar de qualquer coisa, é só me chamar!  
**C.** Esse tempo conta para o atendimento? Vocês estão cronometrando?  
**A.** Sim, o tempo é registrado, senhor Eduardo. São só 20 segundos.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhor Eduardo, obrigado por aguardar. Localizei os seus dados.  
**A.** O senhor reside na Rua dos Girassóis, correto?  
**C.** Segundo o meu direito, sim, é nesse endereço mesmo.  
**A.** Ótimo. O senhor pode me confirmar o número da residência?  
**C.** Número 230.  
**A.** Qual é o bairro?  
**C.** Parque Horizonte. Quero isso por escrito.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou confirmar o pagamento para pedir a religação. Podemos fazer isso?  
**C.** Quero que conste que sim. Esse atendimento está sendo gravado?  
**C.** Por que isso é minha responsabilidade? Vocês devem manter o serviço.  
**A.** As verificações servem para identificar se a causa é interna ou na rede, senhor Eduardo, e não colocam a responsabilidade em o senhor.  
**A.** Pode me informar o valor pago e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Foram R$ 187,40, autenticação 7F3A91.  
**A.** Existe alguma outra fatura em aberto?  
**C.** Não, só essa.  
**A.** Há alguém na casa que dependa de equipamento de saúde ligado à energia?  
**C.** Anote aí: não, ninguém. Quero isso por escrito.  
**A.** Entendido. Vou solicitar a religação.  
**C.** Tudo bem.  
**A.** Entendido, senhor Eduardo!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Preciso de um ponto de referência para a equipe de religação.  
**C.** Quero falar com o seu supervisor.  
**A.** Posso resolver agora e, se o senhor ainda quiser, registro o encaminhamento ao supervisor com prazo de retorno, senhor Eduardo.  
**C.** Ao lado da farmácia Vida Nova. Esse atendimento está sendo gravado?  
**A.** Pode me passar um telefone de contato?  
**C.** É (79) 9 1234-5678.  
**A.** O senhor tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas o senhor pode me chamar quando quiser.  
**C.** Ok.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhor Eduardo, foi gerado um protocolo. O senhor pode anotar?  
**C.** Anote aí: sim, vou pegar uma caneta e um papel. Quero isso por escrito.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Quero o protocolo por escrito, por mensagem e por e-mail.  
**A.** Combinado, senhor Eduardo. Informo o número agora e envio por escrito.  
**A.** O protocolo é o 26230982-4.  
**C.** Anotado.  
**A.** A religação será feita em até 4 horas após a compensação do pagamento, ou seja, até as 17h (prazo de exemplo).  
**C.** Quero que conste que ok. Esse atendimento está sendo gravado?  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** O senhor deseja algo mais?  
**C.** Sim: como faço para formalizar uma reclamação?  
**A.** Abro agora uma manifestação formal, senhor Eduardo, com protocolo próprio.  
**C.** Não, é suficiente.  

### 7º Passo - Pesquisa de satisfação
*Meta: 30 s  |  Checklist: Avisar o redirecionamento; falar da pesquisa sobre o atendimento e pedir a avaliação com educação, sem insistir; informar o e-mail em até 48 h.*

**A.** Agora o senhor será redirecionado para o setor de avaliação.  
**A.** A primeira pergunta é sobre o meu atendimento, e espero que o senhor possa me dar uma nota positiva, que é muito importante para mim.  
**C.** Darei a nota conforme o atendimento. Que conste.  
**A.** Perfeito, senhor Eduardo. A pesquisa vai seguir o registro.  
**A.** Em até 48 horas, o senhor também receberá um e-mail para avaliação.  

### 8º Passo - Despedida
*Meta: 15 s  |  Checklist: Agradecer em nome da empresa; saudação final adequada ao horário; encerrar com cortesia.*

**A.** A Fênix agradece. Tenha uma excelente [tarde/noite/dia, pela hora do aparelho]!  
**C.** Aguardo o retorno. Boa tarde.  
> **[FIM DA CHAMADA - o cronômetro total para junto com a despedida.]**


---
