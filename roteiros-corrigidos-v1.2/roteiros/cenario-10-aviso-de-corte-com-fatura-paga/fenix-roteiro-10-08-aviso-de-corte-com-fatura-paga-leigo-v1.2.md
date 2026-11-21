# Fênix | Simulado de Atendimento - Roteiro 10.08

Versão 1.1 - 20/11/2026

**Cenário 10:** Aviso de corte com fatura já paga (novo)  
**Persona 08:** Cliente leigo  
**Objetivo de aprendizado:** Tratar pagamento não localizado: validar comprovante, abrir pedido de baixa e orientar sobre a suspensão da ordem de corte.

**Convenção:** A. = atendente (aluno, modelo de fala); C. = cliente (voz sintética sorteada); [PAUSA] e [ESPERA] = silêncio do cliente.

**Aviso:** Dados fictícios: nomes, endereços, telefones, protocolos, valores e prazos são exemplos para treino. Nenhum roteiro cita empresa real; o atendente fala 'Atendimento Fênix' (variável {EMPRESA}). Prazos, valores e regras devem ser ajustados à política da operação onde o treino for aplicado.

---

## Roteiro 10.08 - Aviso de corte com fatura já paga x Cliente leigo

**Cliente (fictício):** Patrícia Gomes | **Dificuldade:** 5/8 | **Libera no nível:** Pleno

- **Perfil:** Cliente que não entende termos técnicos (disjuntor, aferição, unidade consumidora) e tem receio de errar.
- **Voz sugerida:** Ritmo normal, tom inseguro, perguntas frequentes | **Paciência:** 70/100
- **Técnica-chave:** Traduzir o termo técnico em exemplo do dia a dia e confirmar se ficou claro.
- **Armadilha do cenário:** Dizer que o cliente está errado; não pedir o comprovante; prometer suspensão sem abrir o pedido.
- **Erros comuns nesta persona:** Usar jargão sem explicar. / Responder 'é só ler o aparelho' sem orientar onde. / Não verificar se o cliente entendeu.
- **O avaliador observa:** Termos técnicos explicados. / Exemplos do dia a dia. / Confirmação do entendimento.
- **Dados do chamado:** unidade consumidora 063481-6; endereço Rua das Orquídeas, 888, Industrial, Vale Azul.


### 1º Passo - Abertura
*Meta: 60 s  |  Checklist: Saudação pelo horário do aparelho; nome da empresa; nome do atendente; pedir o nome do cliente e chamá-lo pelo nome; triagem; pedir unidade consumidora ou CPF.*

**A.** Atendimento Fênix, [nome do atendente], [bom dia/boa tarde/boa noite, pela hora do aparelho]. Qual o seu nome, por favor?  
**C.** [saudação], meu nome é Patrícia Gomes. Desculpa, eu não entendo muito dessas coisas.  
**A.** Senhora Patrícia, no que posso ajudar?  
**C.** Acho que é... recebi um aviso de corte, mas eu já paguei essa fatura, eu acho.  
**C.** Eu nem sei explicar direito esse aviso de corte. Qual dado eu preciso ter à mão?  
**A.** Sem problema, senhora Patrícia. Vou orientar. Quando eu pedir algo, explico onde a senhora encontra.  
**A.** Senhora Patrícia, qual é o mês da fatura e em que dia a senhora pagou?  
**C.** É a de setembro, paguei no dia 10.  
**A.** Senhora Patrícia, pode me informar o código da unidade consumidora, que fica no canto superior direito da fatura, ou o CPF do titular?  
**C.** Não sei bem, mas a unidade consumidora é 063481-6. Está certo?  

### 2º Passo - Pausa de 20 s e confirmação positiva
*Meta: 20 s de pausa + 45 s de confirmação  |  Checklist: Pedir licença e avisar que o sistema ficará mudo; dizer 'é só chamar'; agradecer ao voltar; confirmar rua, número, bairro e município, um a um.*

**A.** Obrigado(a). Vou consultar o seu cadastro e, enquanto isso, o sistema ficará mudo. Se a senhora precisar de qualquer coisa, é só me chamar!  
**C.** O que é 'cadastro'? É o que eu preenchi quando liguei a luz?  
**A.** Exatamente, senhora Patrícia: são os seus dados que a empresa guarda. Vou conferir se estão certos.  
**C.** Tudo bem, pode consultar.  
> **[PAUSA DE 20 s - cliente em silêncio. O aluno consulta o cadastro; se o cliente chamar, o atendente responde.]**

**A.** Senhora Patrícia, obrigado por aguardar. Localizei os seus dados.  
**A.** A senhora reside na Rua das Orquídeas, correto?  
**C.** O que é isso? Ah, sim, é nesse endereço mesmo.  
**A.** Ótimo. A senhora pode me confirmar o número da residência?  
**C.** Número 888.  
**A.** Qual é o bairro?  
**C.** Industrial, eu acho.  
**A.** E o município?  
**C.** Vale Azul.  
**A.** Ok, obrigado.  

### 3º Passo - Entrevista e testes
*Meta: 120 s  |  Checklist: Pedir permissão para os testes; orientar com clareza; aguardar sem pressionar; fazer perguntas de esclarecimento; confirmar o entendimento.*

**A.** Vou conferir o pagamento com a senhora. Pode ser?  
**C.** Não sei bem, mas sim. Está certo?  
**C.** Eu não entendo nada disso. Pode explicar de um jeito simples?  
**A.** Claro! Vou dizer o que olhar e para que serve, sem termos difíceis.  
**A.** Pode ler o valor e o código de autenticação do comprovante?  
**C.** Vou verificar.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** R$ 204,90, autenticação B91C05.  
**A.** O pagamento foi feito por banco, lotérica ou aplicativo?  
**C.** Pelo aplicativo do banco.  
**A.** Pelo sistema, esse pagamento não aparece. Vou abrir um pedido de baixa por pagamento não localizado. A senhora pode enviar o comprovante?  
**C.** Acho que é... vou verificar, eu acho.  
> **[ESPERA DE 10 s - o cliente verifica; o atendente aguarda sem pressionar.]**

**C.** Posso sim, tenho a foto no celular.  
**A.** Perfeito. Enquanto o pedido é analisado, a ordem de corte será bloqueada.  
**C.** Não sei bem, mas que bom. Está certo?  
**A.** Entendido, senhora Patrícia!  

### 4º Passo - Protocolo e previsão
*Meta: 60 s  |  Checklist: Coletar ponto de referência ou dado do pedido; pedir telefone e um segundo contato; avisar nova pausa e que pode ser chamado.*

**A.** Pode me passar um telefone de contato?  
**C.** Não sei se entendi o que o senhor precisa. Pode explicar?  
**A.** Preciso de um número de telefone, senhora Patrícia, para a equipe avisar a senhora antes de chegar.  
**C.** É (79) 9 1234-5678.  
**A.** A senhora prefere enviar o comprovante por e-mail ou por mensagem?  
**C.** Por e-mail.  
**A.** A senhora tem mais um número de contato?  
**C.** Não, só esse.  
**A.** Ok, entendido. Aguarde só mais um momento. O sistema ficará mudo, mas a senhora pode me chamar quando quiser.  
**C.** Acho que é... ok, eu acho.  

### 5º Passo - Pausa de 10 s
*Meta: 10 s de pausa + 30 s para informar  |  Checklist: Gerar o protocolo; pedir que o cliente anote e aguardar; informar o protocolo pausadamente; confirmar que anotou; informar previsão e orientação.*

> **[PAUSA DE 10 s - cliente em silêncio; o aluno gera o protocolo.]**

**A.** Senhora Patrícia, foi gerado um protocolo. A senhora pode anotar?  
**C.** Sim, vou pegar uma caneta e um papel.  
> **[ESPERA DE 5 s - o cliente pega caneta e papel.]**

**C.** Protocolo? É um número que eu guardo?  
**A.** Isso, senhora Patrícia: é o número do seu pedido. A senhora guarda para acompanhar.  
**A.** O protocolo é o 26248873-7.  
**C.** Não sei bem, mas anotado. Está certo?  
**A.** O pedido será respondido em até 2 dias úteis (prazo de exemplo), e a ordem de corte fica bloqueada nesse período.  
**C.** Ok.  

### 6º Passo - Algo mais?
*Meta: 20 s  |  Checklist: Perguntar se deseja algo mais e resolver ou registrar o pedido extra sem perder o fio.*

**A.** A senhora deseja algo mais?  
**C.** O que mais eu posso pedir?  
**A.** Se a senhora não precisar de mais nada, posso encerrar. Se surgir dúvida depois, é só ligar com o protocolo.  
**C.** O que é isso? Ah, não, é suficiente.  

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
