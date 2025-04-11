# 💬 Análise de Sentimentos com Azure Text Analytics

Este documento contém os resultados da análise de sentimentos realizada em frases de exemplo usando a ferramenta Azure Text Analytics.

## 📊 Tabela de Resultados

| Frase                                                                 | Sentimento | 🔵 Positivo | ⚪ Neutro | 🔴 Negativo |
|----------------------------------------------------------------------|------------|-------------|----------|-------------|
| Hoje o atendimento foi excelente, estou muito satisfeito.           | 😊 Positivo | 0.98        | 0.02     | 0.00        |
| O produto chegou com defeito e ninguém responde minhas mensagens.   | 😠 Negativo | 0.01        | 0.05     | 0.94        |
| A entrega foi rápida, mas o pacote estava danificado.               | 😐 Neutro   | 0.40        | 0.50     | 0.10        |
| Não recomendo essa empresa para ninguém!                            | 😡 Negativo | 0.00        | 0.02     | 0.98        |
| Parabéns pelo ótimo serviço, voltarei a comprar com certeza.        | 😄 Positivo | 0.97        | 0.03     | 0.00        |

## 📌 Considerações

- A IA foi capaz de identificar corretamente os sentimentos predominantes nas frases com base no conteúdo emocional.
- Frases com opiniões mistas foram classificadas como neutras, considerando os scores de cada sentimento.
- Essa análise pode ser aplicada em feedbacks de clientes, redes sociais, SAC e outras fontes de texto.

---

🔗 Este resultado faz parte do projeto de IA da DIO, onde exploramos a aplicação de serviços cognitivos da Microsoft para analisar textos e sentimentos de forma automática.

