# DIO - Trilha Java Básico

## Autor

🔸[wprotheus](https://github.com/wprotheus)

---

## Desafio - Análise de Sentimentos com Language Studio no Azure AI  

Atividade executada conforme orientações abaixo, retiradas do [Descrição do Desafio](https://web.dio.me/lab/analise-de-sentimentos-com-language-studio-no-azure-ai/learning/f6884c74-e7aa-4700-a84b-a3446e0b6d8d)  
<small><sup>Obs.: O link acima somente é acessado através de uma conta na plataforma DIO.</sup></small>

### Descrição do Desafio
#### Em -> CONTEÚDOS  
> Este laboratório tem como objetivo **praticar e aprofundar o uso das ferramentas Azure Speech Studio e Language Studio, focando na análise de fala e linguagem natural**. O objetivo é desenvolver habilidades práticas na criação de soluções baseadas em inteligência artificial voltadas para voz e linguagem. O entregável é um **repositório organizado contendo anotações e insights adquiridos durante a prática**, servindo como material de apoio para estudos e futuras implementações.

#### Em -> INFORMAÇÕES  
> Neste LAB, exploraremos o uso do Azure Speech Studio e a análise linguística proporcionada pelo Language Studio. Durante a prática, teremos a oportunidade de aprofundar nosso entendimento sobre como aproveitar essas ferramentas avançadas da Microsoft Azure. Estaremos focados em aprimorar nossas habilidades na implementação de soluções de análise de fala e linguagem, abrindo portas para uma compreensão mais ampla e prática das capacidades oferecidas por essas tecnologias inovadoras.  

### Objetivos de Aprendizagem  

> **Ao concluir este desafio, você será capaz de:**
> - Aplicar os conceitos aprendidos em um ambiente prático;
> - Documentar processos técnicos de forma clara e estruturada;
> - Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.


# Configurando o Recurso de ***IA + Machine Learning*** na Azure

## Introdução

Neste tutorial, você aprenderá a configurar serviços de **IA + Machine Learning** na plataforma Azure, com foco nos serviços de Linguagem, assim como sua utilização.

### Pré-requisitos

- Conta ativa no Microsoft Azure
- Conhecimentos básicos em inteligência artificial e Azure

## Passo 1: Criando e Configurando o Recurso de Linguagem

### A. Criando um recurso no Azure

1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. Faça login no portal com sua conta.

### B. Criando um Novo Recurso

- No portal Azure, clique em ***+ Criar um recurso***
- Procure por **AI + Machine Learning**
- Selecione **Serviço de Linguagem**
- Clique em **Continue to create your resource**

### C. Configurando o Recurso

- Escolha um nome para o recurso
- Selecione a localização geográfica mais adequada
- Escolha o tipo de conta (por exemplo, **F0 - Gratuito**)

> ⚠️ **Dica:** Recursos gratuitos (como F0) têm limite de uso diário/mensal. Acompanhe pelo painel do Azure para evitar interrupções.

### D. Criando o Recurso

- Clique em **Revisar + Criar**
- Em seguida, clique em **Criar**

## Passo 2: Configurando o Serviço de Linguagem

### A. Acessando o Recurso Criado

- Acesse o [Language Studio](https://language.cognitive.azure.com/home)

### B. Selecionando o Recurso Azure

1. Selecione o **Azure directory** configurado
2. Escolha a **Azure subscription** adequada
3. Selecione o **Resource type** desejado
4. Selecione o **Resource name** criado
5. Clique em **Done**

## Passo 3: Utilizando o ***Language Studio***

### A. Serviços Disponíveis

- Selecione **Classify text**
- Selecione **Analyze sentiment and opinions**

### B. Testando o Recurso

1. **Select text language:** Selecione o idioma desejado
2. **Select your Azure resource:** Selecione o recurso configurado
3. **Enter your own text, upload a file, or use one of our sample texts:** Insira o texto a ser analisado
4. **Acknowledgment checkbox:** Marque a opção informando que compreende possíveis custos
5. Clique em **Run**

### C. O Resultado

- Na seção **Examine the results**:
    - **Result:** Visualização e descrição da análise
    - **JSON:** Exibição dos dados brutos no formato JSON

## Conclusão

Este tutorial cobriu os passos básicos para começar a utilizar o **Language Studio** no Azure. Continue explorando e aprofundando seus conhecimentos para desenvolver soluções mais avançadas em inteligência artificial voltada para linguagem natural.


---
## 📷 Capturas de telas

### Tela #1:
<img src="./img_speech/tela (1).png" alt="Tela criando recurso" width="350px"/>  

### Tela #2:
<img src="./img_speech/tela (2).png" alt="Tela implantação recurso" width="350px"/> 

### Tela #3:
<img src="./img_speech/tela (3).png" alt="Tela listando recurso no grupo" width="350px"/>  

### Tela #4:
<img src="./img_speech/tela (4).png" alt="Tela configurando recurso no Language Studio" width="350px"/>  

### Tela #5:
<img src="./img_speech/tela (5).png" alt="Tela iniciando teste serviço" width="350px"/>  

### Tela #6:
<img src="./img_speech/tela (6).png" alt="Tela resultado 1 de 2" width="350px"/>  

### Tela #7:
<img src="./img_speech/tela (7).png" alt="Tela resultado 2 de 2" width="350px"/>  

---  

### 📚 Documentações Recomendadas

- [Azure AI + Machine Learning - Serviços de Linguagem](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/overview)
- [Language Studio - Sentiment and Opinion Mining](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/sentiment-opinion-mining/overview)
