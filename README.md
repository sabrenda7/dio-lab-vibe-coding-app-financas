# 💸 App de Finanças Pessoais com Vibe Coding by Brenda
Este projeto foi desenvolvido como um desafio de projeto da DIO utilizando Lovable e o Copilot Web. A proposta foi de criar um aplicativo de organização de finanças pessoais desenvolvido com a abordagem de **Vibe Coding**, uma experiência simples e acessível para quem deseja começar a controlar seus gastos sem complicações, utilizando conversas em linguagem natural em vez de formulários complexos.  
O app foi estruturado a partir de um **PRD refinado** e prototipado no Lovable, com foco em funcionalidades práticas como registro de gastos via chat, definição de metas financeiras, relatórios visuais e autenticação de usuários, sempre seguindo princípios de **Design Universal** para garantir usabilidade ao maior número possível de pessoas.

PRD refinado no Copilot Web:

```
# PRD – Aplicativo de Organização de Finanças Pessoais

## 1. Contexto
Criar um aplicativo de organização financeira pessoal que funcione por meio de conversas em linguagem natural, tornando o controle de gastos mais simples e intuitivo.
O objetivo é eliminar a complexidade de formulários e planilhas, oferecendo uma experiência fluida e acessível.

## 2. Problema
- Usuários desistem de controlar suas finanças porque os apps atuais exigem entrada manual excessiva.
- Falta de personalização e de recomendações práticas.
- Necessidade de uma solução que combine simplicidade com aconselhamento inteligente.

## 3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças sem complicações.
- Principalmente iniciantes que nunca usaram apps financeiros ou que desistiram por achar difícil.

## 4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações (ex.: alimentação, transporte, lazer).
3. Definição e acompanhamento de metas financeiras (ex.: guardar R$ 200/mês).
4. Agente Financeiro: dicas personalizadas de economia e hábitos financeiros.
5. Relatórios simples e visuais, adaptados ao perfil do usuário.
6. Autenticação de usuários (login e cadastro).
7. Banco de dados individual por perfil, garantindo que cada usuário tenha suas informações separadas e seguras.
8. Criação de metas pelo assistente: quando solicitado, o agente financeiro gera metas e as adiciona automaticamente na aba de metas.

## 5. Design Universal
O aplicativo deve seguir princípios de Design Universal, garantindo que o maior número possível de pessoas tenha uma boa experiência de uso, sem necessidade de adaptações específicas.  
Isso significa:
- Uso equitativo: acessível para diferentes perfis de usuários.
- Flexibilidade: múltiplas formas de interação (voz, texto, toque).
- Simplicidade e intuição: fácil de entender sem instruções complexas.
- Informação perceptível: dados apresentados de forma clara e multimodal (texto, ícones, áudio).
- Tolerância ao erro: reduzir riscos de uso incorreto.
- Baixo esforço físico: interação sem exigir esforço excessivo.
- Espaço e dimensão apropriados: compatível com diferentes dispositivos e contextos.

## 6. Entregável da IA
- Plano de MVP contendo:
  - Principais telas (chat, metas, relatórios, login/cadastro).
  - Recursos necessários (NLP para chat, categorização automática, motor de recomendações, autenticação, banco de dados por perfil).
  - Esboço de validação inicial (testes com usuários iniciantes, feedback sobre clareza e utilidade).
- Linguagem acessível e educativa, em português.

```

Interações com o Lovable:

> Crie um App de finanças pessoais com base no seguinte PRD (Product requirements documents). {PRD}

> Quero que o aplicativo de organização financeira pessoal seja funcional, não apenas um dashboard genérico. Inclua autenticação de usuários (login e cadastro) e configure um banco de dados individual para cada perfil, garantindo que as informações fiquem salvas e acessíveis. O assistente deve ser capaz de criar metas financeiras quando solicitado e adicioná-las automaticamente na aba de metas ...

Resultado Final no Lovale: chat-money-buddy-92

<img width="392" height="635" alt="image" src="https://github.com/user-attachments/assets/f0d04d38-c3ed-443f-9304-663554928ded" />

# Aplicativo de Organização de Finanças Pessoais

## Visão Geral
Este aplicativo tem como objetivo facilitar o controle financeiro pessoal por meio de conversas em linguagem natural, eliminando a complexidade de formulários e planilhas.  
O foco é oferecer uma experiência simples, intuitiva e acessível, baseada em princípios de **Design Universal**.

## Funcionalidades Principais

### Funcionalidades já visíveis no protótipo
- **Aba de Metas**: acompanhamento do progresso financeiro do usuário.
- **Resumo geral**: mostra o total economizado em relação ao valor total das metas.
- **Metas individuais**: exemplo de “Reserva de emergência” com valor-alvo definido.
- **Adicionar meta**: botão para criar novas metas financeiras.
- **Navegação inferior**: acesso rápido às seções de Chat, Metas, Relatórios e Perfil.

### Funcionalidades previstas no PRD
- **Registro de gastos via chat em linguagem natural**.
- **Classificação automática das transações** (alimentação, transporte, lazer etc.).
- **Definição e acompanhamento de metas financeiras** (com suporte do assistente).
- **Agente Financeiro**: fornece dicas personalizadas de economia e pode criar metas automaticamente quando solicitado.
- **Relatórios simples e visuais** para análise do desempenho financeiro.
- **Autenticação de usuários** (login/cadastro).
- **Banco de dados individual por perfil**, garantindo que cada usuário tenha suas informações separadas e seguras.
- **Design Universal**: interface pensada para ser simples, intuitiva e acessível ao maior número possível de pessoas.

  
# Reflexão sobre o processo

### O que funcionou bem?
O refinamento do PRD no Copilot ajudou muito pois os crédios acabaram em apenas 2 iterações.

### O que não funcionou como o esperado?
Esprava interagir mais vezes com o Lovable, mas as iterações feitas foram suficientes para noção de como funciona o vibe coding.

### O que aprendeu sobre conversar com IAs?
Conversar com IA é basicamente conversar com uma pessoa, quanto mais detahes e clareza você dar melhor será a interação.
