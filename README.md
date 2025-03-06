# Análise de Sentenças com Sentimentos Mistos

Este repositório foi criado para explorar como a inteligência artificial pode analisar sentenças com sentimentos mistos, identificando emoções e fornecendo insights úteis para projetos futuros.

## Estrutura do Projeto
- **Pasta `inputs`**: Contém o arquivo `sentencas.txt` com sentenças que misturam emoções positivas, negativas e neutras.
- **Ferramenta utilizada**: Language cognitive do azure para análise de texto.

## Processo
1. Criei o arquivo `sentencas.txt` com sentenças que expressam sentimentos variados.
2. Criei um novo recurso language service no portal do azure.
3. Logo após abri o language studio.
4. No language studio selecionei o recurso criado no portal.
5. Criei um novo projeto de classificação de texto.
6. Escolhi a opção de análise de sentimentos.
7. Selecionei o idioma português e coloquei o meu texto para que fosse analisado o conteúdo e fosse identificado os tons emocionais.

## Resultados e Insights
- **Análise da IA**: 
  - A primeira sentença tem um tom positivo e otimista ("empolgado com as oportunidades").
  - A segunda mostra insegurança e medo ("medo de não acompanhar").
  - A terceira mistura positividade ("dia amanheceu lindo") com cansaço ("exausto").
  - A quarta combina animação ("aprender algo novo me anima") com frustração ("pressão é desgastante").
- **Possibilidades aprendidas**:
  - A IA consegue detectar nuances emocionais em textos curtos, o que pode ser útil em chatbots ou análise de feedback.
  - Esse tipo de análise pode ajudar a personalizar respostas em sistemas automatizados, dependendo do estado emocional identificado.
- **Capturas de tela**: ![image](https://github.com/user-attachments/assets/be16518e-95ab-4c21-ab03-bd701dab19f5)


## Próximos Passos
- Testar a análise com textos mais longos para avaliar a consistência da IA.
- Experimentar categorizar sentimentos em tempo real com base em entradas de usuários.
