# Desafio DIO - Azure Speech Studio & Language Studio

Este repositório contém a documentação e anotações do desafio proposto pela DIO, com foco em **análise de fala** e **processamento de linguagem natural** usando os serviços da **Azure AI**.


## 📌 Objetivos do Desafio
- Praticar o uso do **Speech Studio** para reconhecimento de fala;
- Explorar o **Language Studio** para análise de linguagem natural;
- Documentar o processo de forma clara e estruturada;
- Utilizar o GitHub como ferramenta de compartilhamento de documentação técnica.


## 🛠️ Ferramentas Utilizadas
- [Microsoft Azure Speech Studio](https://speech.microsoft.com/)
- [Microsoft Azure Language Studio](https://language.cognitive.azure.com/)
- [GitHub](https://github.com/)


## 📖 Passo a Passo Realizado

## Speech Studio

1. Acessar o Portal [Speech Studio](https://speech.microsoft.com)
2. Para o primeiro acesso, é necessário a criação de uma conta ou acessar através de uma conta Microsoft existente.
3. Acesse **Configurações → Criar novo recurso**.
4. Na próxima tela, preencha:
- **Nome do novo recurso:** Atribua um nome qualquer.
- **Assinatura:** Azure subscription 1 *(por padrão)*.
- **Região:** Leste dos EUA.
- **Tipo de preço:** Padrão S0.
- **Grupo de recursos:** Crie um novo grupo e atribua um nome qualquer.
- Clique em **Criar um recurso**
5. Após criar um novo recurso, selecione e clique em **Usar o recurso**.
6. Na tela inicial do Speech Studio, acesse "**Conversão de fala em texto em tempo real**"
7. Selecione o idioma desejado, em seguida você pode **importar um áudio** do computador ou gravar com o microfone.
8. Pronto, conversão realizada.

## Language Studio
1. Acessar o [Language Studio](https://language.cognitive.azure.com)
2. Faça login com sua conta do Azure.
3. Assim como no Speech Studio, você pode acessar **Configurações →  Recursos → Criar novo recurso**.
4. Retornando a tela inicial, dentre várias funções do Language Studio, utilizei a Análise de sentimento, acessando **Classify Text →  Analyze sentiment and mine opinions**:
5. Selecione o idioma desejado ou deixe que o sistema identifique automaticamente, cole o texto no qual queira analisar, clique em **Run**.
6. Pronto, desse forma geradas as analises por IA.

## 📷 Evidências
Anexos das etapas realizadas estão disponíveis na pasta [/images](/images)

## ✨ Insights e Aprendizados
Um pequeno resumo sobre minha experiência nesse desafio, veja meus [Insights.md](/insights.md)

## 🔗 Recursos Úteis
- [Documentação Speech Studio](https://learn.microsoft.com/azure/cognitive-services/speech-service/)
- [Documentação Language Studio](https://learn.microsoft.com/azure/cognitive-services/language-service/)


## 📝 Autor
Desenvolvido por **Fábio Barros de Oliveira** para o desafio [DIO](https://www.dio.me/).
