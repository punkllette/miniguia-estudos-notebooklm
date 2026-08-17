# 🧪 Engenharia de Prompts e Cicatrizes

Esta seção documenta o processo de elaboração e aprimoramento dos prompts utilizados durante o estudo sobre criação de hábitos.

A ideia foi testar diferentes formas de fazer perguntas ao NotebookLM e observar como a especificidade das instruções influenciava a qualidade das respostas.

---

## 1. Compreensão geral do tema

### Prompt inicial

> Explique Hábitos Atômicos.

### Problema encontrado

A pergunta é muito ampla. A resposta pode apresentar conceitos gerais, mas não estabelece uma estrutura específica para o estudo.

### Prompt aprimorado

> Com base nas fontes disponíveis neste notebook, explique os principais conceitos relacionados à criação de hábitos. Organize a resposta em tópicos e apresente exemplos práticos para cada conceito.

### Melhoria

A segunda versão delimita:

* O conjunto de fontes que deve ser utilizado;
* O assunto;
* A estrutura da resposta;
* A necessidade de exemplos.

---

## 2. Identificação das quatro leis

### Prompt

> Com base exclusivamente nas fontes deste notebook, explique as quatro leis da mudança de comportamento. Para cada lei, apresente: definição, objetivo, exemplo de aplicação e estratégia prática.

### Objetivo

Utilizar o NotebookLM para transformar o conteúdo das fontes em uma estrutura de revisão rápida.

### Resultado esperado

Uma explicação organizada que permita comparar as quatro leis e entender como elas podem ser aplicadas na prática.

---

## 3. Comparação entre criação e eliminação de hábitos

### Prompt

> Compare as estratégias utilizadas para criar bons hábitos e eliminar hábitos ruins. Organize a resposta em uma tabela contendo: objetivo, estratégia, exemplo e aplicação prática.

### Por que esse prompt foi utilizado?

A comparação facilita a identificação das diferenças entre os dois processos e transforma conceitos teóricos em uma estrutura de consulta rápida.

---

## 4. Aplicação prática

### Prompt

> Com base nos conceitos encontrados nas fontes, crie um exemplo de aplicação das quatro leis para uma pessoa que deseja desenvolver o hábito de estudar todos os dias. Explique cada etapa e não adicione conceitos que não estejam relacionados às fontes.

### Objetivo

Verificar se os conceitos estudados poderiam ser transformados em uma situação prática.

---

## 5. Prompt para revisão

### Prompt

> Faça uma revisão dos principais conceitos estudados neste notebook. Crie 10 perguntas de revisão, começando por questões básicas e aumentando gradualmente a dificuldade. Depois apresente o gabarito separado das perguntas.

### Objetivo

Transformar o conteúdo pesquisado em uma ferramenta de revisão ativa.

---

# 🔧 Cicatrizes / Troubleshooting

Durante o processo, alguns problemas podem ocorrer ao utilizar IA para estudar.

## Respostas muito genéricas

**Problema:** perguntas muito abertas podem gerar respostas extensas e pouco direcionadas.

**Solução:** especificar o objetivo, formato da resposta, fontes que devem ser utilizadas e nível de profundidade desejado.

---

## Dificuldade para transformar teoria em prática

**Problema:** compreender um conceito não significa necessariamente saber como aplicá-lo.

**Solução:** solicitar exemplos contextualizados e cenários de aplicação.

---

## Excesso de informação

**Problema:** uma resposta muito longa pode dificultar a revisão.

**Solução:** solicitar estruturas como tabelas, tópicos, mapas conceituais, perguntas de revisão e resumos.

---

## Necessidade de verificar as informações

**Problema:** respostas geradas por IA não devem ser consideradas automaticamente verdadeiras.

**Solução:** utilizar fontes selecionadas previamente e solicitar que as respostas estejam fundamentadas nos materiais disponíveis no notebook.

---

# 📌 Principais aprendizados sobre prompting

Durante a atividade, foi possível observar que prompts mais específicos tendem a produzir resultados mais úteis para estudo.

Alguns elementos que contribuíram para melhorar os resultados foram:

1. Definir claramente o objetivo;
2. Delimitar as fontes;
3. Especificar o formato da resposta;
4. Solicitar exemplos;
5. Pedir comparação entre conceitos;
6. Transformar o conteúdo em perguntas de revisão;
7. Verificar as informações nas fontes originais.

---

# ♻️ Prompts reutilizáveis

### Resumo

> Com base exclusivamente nas fontes deste notebook, faça um resumo estruturado sobre [TEMA]. Organize por conceitos, exemplos e aplicações práticas.

### Explicação

> Explique [CONCEITO] de forma simples, como se estivesse ensinando alguém que está tendo o primeiro contato com o assunto. Utilize exemplos baseados nas fontes.

### Comparação

> Compare [CONCEITO A] e [CONCEITO B]. Apresente diferenças, semelhanças, exemplos e aplicações práticas.

### Revisão

> Crie 10 perguntas de revisão sobre [TEMA], começando pelas mais fáceis e aumentando gradualmente a dificuldade. Apresente o gabarito separado.

### Aplicação prática

> Com base nas fontes disponíveis, apresente um exemplo de como [CONCEITO] poderia ser aplicado em uma situação real.

### Síntese

> Reúna os principais conceitos encontrados nas fontes sobre [TEMA] e organize-os em uma estrutura hierárquica, mostrando como eles se relacionam.

### Verificação

> Analise esta afirmação: "[AFIRMAÇÃO]". Verifique se ela é sustentada pelas fontes disponíveis no notebook e indique quais fontes dão suporte à resposta.
