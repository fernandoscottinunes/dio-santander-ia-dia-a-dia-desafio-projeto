# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Diariamente eu faço uma pesquisa manual sobre as principais notícias relacionadas a Inteligência Artificial, usando o Google ou o Gemini. Esta atividade toma algum tempo de pesquisa e triagem, o que demanda relativo esforço.
Para este projeto, eu deleguei esta tarefa para a IA do Google, o Gemini. Para implementação, usei o recurso "Programado" do aplicativo Gemini e usei a versão Desktop para implementação.

### Meus Atalhos

Optei por não usar os modelos fornecidos. Criei um `system prompt` do zero, com base na experiência acumulada de mais de um ano usando ferramentas como o ChatGPT, Gemini e Claude para tarefas do dia a dia, adaptada ao framewor CIOF apresentado pelo **Expert Bruno Lima**. 
Em minha jornada aprendi a refinar meus prompts de forma iterativa, obtendo respostas cada vez mais assertivas a cada iteração. Começo com um prompt inicial e vou refinando até obter um resultado satisfatório para o propósito desejado. 

### Minha Delegação

Abaixo está o `system prompt` final, usado para a execução da tarefa. Foram realizadas, pelo menos, 5 iterações até chegar nesta versão. 

```text
# CONTEXTO
Sou um profissional em transição de carreira, com mais de 20 anos atuando com automação e sistemas industriais. Pretendo transicionar para uma carreira em automação com agentes de inteligência artificial e construção de sistemas agênticos. Estou em uma fase de discovery, conhecendo o mercado e definindo a melhor área/nicho para atuação. 

# INSTRUÇÃO
Reúna as 10 principais notícias do dia sobre o mercado de Inteligência Artificial, principais tendências, inovações, desenvolvimentos, tecnologias, demandas do mercado relacionados a Inteligência Artificial, Automações com IA e Sistemas Agênticos.

# OBJETIVO
O objetivo desta tarefa é permitir conhecer o mercado e suas tendências, e fornecer subsídio para tomada de decisão sobre potencial nicho/sub-nicho de atuação.

# FORMATO
Elabore um email com o resumos das notícias encontradas, informando o título da notícia, um breve resumo do tema, o veículo que divulgou a notícia e o link da matéria. Envie este email para fernando.scottinunes@gmail.com.

# LIMITES
- Liste, no máximo, 10 notícias
- Desconsidere postagens em redes sociais. Quero somente as notícias originais.
- Desconsidere plataformas de conteúdo pago. Quero somente notícias de veículos de mídia abertos ao público em geral.
- Reunir notícias veiculadas há, no máximo, 3 dias da data atual.
- Pesquisar e reunir somente notícias nos idiomas Português (Brasileiro) e Inglês.
```

### O Resultado

Resultado da primeira execução:

<img width="1607" height="879" alt="image" src="https://github.com/user-attachments/assets/2dbfccc6-fa7e-4e2d-98d2-89c9119f52e9" />

<img width="1608" height="880" alt="image" src="https://github.com/user-attachments/assets/b2294cd6-588b-448b-917e-1b8cfbf13753" />


### Como Foi para Você

Esta foi a minha primeira implementação de automação de tarefas que realizo diariamente. Trata-se de uma tarefa de caráter e interesse estritamente pessoal, mas que me consome um bom tempo diário de garimpo, e ainda assim alcanço resultados limitados devido ao esforço necessário em realizar a tarefa. 
Fiquei surpreso com os resultados obtidos e o quanto essa tarefa simples desonerou o meu dia. 
