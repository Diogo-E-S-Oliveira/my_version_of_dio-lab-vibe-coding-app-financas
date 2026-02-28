# 💸 Meu App de Organização de Finanças Pessoais com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto de Vibe Coding da DIO utilizando O Lovable e o Copilot Web. A proposta é criar um aplicativo de organização financeira pessoal baseado em iterações em linguagem natural.

---

PRD refinado no Copilot Web:

```markdonw
# PRD – App de Organização Financeira com Conversa Natural

## 1. Visão Geral
Desenvolver um aplicativo de finanças pessoais baseado em interação conversacional em linguagem natural, permitindo que o usuário registre e acompanhe seus gastos sem precisar lidar com planilhas ou interfaces complexas.  
O objetivo é oferecer uma experiência intuitiva, acessível e personalizada, transformando o controle financeiro em algo simples e engajador.

## 2. Problema a Resolver
- Usuários abandonam apps financeiros por serem burocráticos e pouco amigáveis.  
- A entrada manual de dados e a falta de personalização dificultam a adesão.  
- Necessidade de uma solução que combine simplicidade, personalização e acessibilidade.

## 3. Público-Alvo
- Pessoas que desejam iniciar o controle financeiro sem complicações.  
- Usuários iniciantes, com pouca familiaridade com aplicativos tradicionais.  
- Pessoas que valorizam conversas naturais em vez de formulários.

## 4. Funcionalidades-Chave
1. Registro de gastos via chat  
   - Exemplo: “gastei R$ 30 no mercado”.  
   - Entrada em linguagem natural, sem necessidade de campos rígidos.  

2. Classificação automática de transações  
   - Algoritmos de NLP categorizam gastos (alimentação, transporte, lazer etc.).  

3. Metas financeiras  
   - Definição e acompanhamento de objetivos como “economizar R$ 500 até o fim do mês”.  

4. Agente Financeiro Inteligente  
   - Recomendações personalizadas para economia e melhor uso dos recursos.  

5. Relatórios simples e visuais  
   - Gráficos e resumos adaptados ao estilo do usuário.  
   - Feedback claro sobre progresso e hábitos.  

## 5. Princípios de Design Universal
A solução será construída com base em Design Universal, garantindo que o aplicativo ofereça uma experiência inclusiva e acessível para o maior número possível de usuários.  
Isso significa:  
- Interface fácil de navegar, com menus intuitivos e organização clara.  
- Navegação simples, sem sobrecarga de informações.  
- Compatibilidade com leitores de tela e comandos por voz.  
- Feedbacks visuais e auditivos para facilitar o uso.  
- Inclusão desde o protótipo, considerando diferentes idades, níveis de alfabetização digital e limitações físicas ou cognitivas.  

## 6. Entregável da IA (Plano de MVP)
- Principais telas:  
  - Chat de interação  
  - Tela de metas  
  - Relatórios e gráficos  

- Recursos técnicos necessários:  
  - Processamento de linguagem natural (NLP)  
  - Motor de categorização automática  
  - Sistema de recomendações personalizadas  

- Estratégia de validação inicial:  
  - Testes com usuários reais em pequenos grupos  
  - Coleta de feedback qualitativo e quantitativo  
  - Iterações rápidas de melhoria  

- Tom e linguagem:  
  - Português acessível, educativo e amigável  
  - Explicações simples para iniciantes  

- Aplicação de Design Universal:  
  - Interface clara e menus intuitivos  
  - Inclusão desde o protótipo  
  - Testes com diversidade de perfis de usuários  
```

---

Interações com o Lovable:

> Crie um App de Finanças Pessoais usando o seguinte PRD (Product Requirements Document) como base: {PRD}

> Tentei criar uma meta de reserva de emergência na aba de metas pedindo para o chat criar, mas a meta não foi criada e não obtive nenhuma resposta do chat. Gostaria também q a tela inicial fosse a tela "resumo", gostaria também de uma aba de extrato.
  
> Gostaria que o chat atualizasse o status da meta conforme passo as informações para ele. Também gostaria de funções manuais para alterar o andamento das metas e para marcá-las como concluídas.
  
> Gostaria q houvesse categorias separadas para "viagem" e "lazer". Também gostaria de uma função que permitisse colocar manualmente uma fonte de receita e que ela possa ser registrada, se for o caso, com uma frequência com que é recebida (salario mensal, por exemplo) e nesse caso, ser possível também registrar o dia do recebimento, quando chegar o dia, o aplicativo registra automaticamente o recebimento. Gostaria que o mesmo fosse possível para despesas, poder registra-las como tendo uma frequência e tudo mais. Claro q isso também deve ser possível apenas passando as informações para o chat. Gostaria também de uma aba de receitas e uma de despesas para que seja possível ver separadamente o que há em cada uma, receitas e despesas frequentes e suas frequências (se forem frequentes). Gostaria também que no dashboard a aba "resumo" seja a primeira da lista, já que ela é a aba de início.
  
  > Gostaria de mudar o nome da pagina, pois "FinChat" já está sendo usado. Gostaria de "Oura Finances" e que "Oura" fosse o nome do bot/IA do chat.

---

Resultado Final no Lovable: https://oura-finances.lovable.app

<img width="1864" height="884" alt="image" src="https://github.com/user-attachments/assets/fa8de4f5-5451-4507-a471-f4e788b5c553" />



---

# Funcionalidades do Site de Organização Financeira

## 1. Resumo do Mês
- Exibe **receitas, despesas e saldo atual**.  
- Identifica a **maior categoria de gasto** (ex.: Viagem).  

## 2. Despesas por Categoria
- Gráfico de pizza mostrando a distribuição dos gastos.  
- Categorias como Viagem, Alimentação e Transporte.  
- Facilita a visualização rápida de onde o dinheiro está sendo gasto.  

## 3. Histórico Financeiro
- Gráfico de barras com dados dos **últimos 6 meses**.  
- Permite acompanhar tendências de receitas e despesas ao longo do tempo.  

## 4. Navegação por Menus
- Seções principais: **Resumo, Chat, Receitas, Despesas, Metas e Extrato**.  
- Estrutura clara e intuitiva, alinhada ao princípio de **Design Universal**.  

## 5. Chat de Interação
- Área dedicada para registrar gastos ou interagir com o assistente financeiro.  
- Uso de **linguagem natural** para simplificar o processo.  

## 6. Gestão de Metas
- Menu específico para criação e acompanhamento de **objetivos financeiros**.  
- Exemplo: “economizar R$ 500 até o fim do mês”.  

---

## Reflexão
  ### O que funcionou bem?
  O refinamento do Product Requirements Document (PRD) utilizando o Copilot se mostrou extremamente eficiente, visto que os crédito do Lovable (gastos em cada iteração) são gastos rapidamente.
  
  ### O que não funcionou como o esperado?  
  A pouca quantidade de créditos na plataforma Lovable nos obriga a esperar o dia seguinte (quando os créditos voltarm) se ainda forem necessárias outras iterações. 
  
  ### O que aprendeu sobre conversar com IAs?
  Apredi que passar contexto muitas vezes auxilia no processo para que a IA traga o tipo de resposta que se espera.

