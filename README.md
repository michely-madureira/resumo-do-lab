### resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, como o tema: Azrei AI e Azure OpenAI Models
___
# Introdução ao Azure AI e Azure OpenAI Models
* A OpenAI é uma empresa responsável por criar modelos responsáveis pela IA generativa, como ChatGPT, Copilot, entre outros, utilizados para geração de textos, conteúdos e imagens.
* A Microsoft passou a disponibilizar todos esses modelos no Azure AI, dentro da Cloud.
* Todas as aplicações que existem atualmente, serão reinventadas com IA no futuro.
* IA generativa é um tipo de inteligência artificial projetada para criar conteúdo novo, como texto, imagens, música e até vídeos, com base em padrões aprendidos a partir de dados existentes. 
___
### **Dentro do Azure AI temos:** 
+ **Azure AI Language:** Fornece recursos de Processamento de Linguagem Natural (NLP) para entender e analisar textos, incluindo análise de sentimento e extração de entidades.
+ **Azure AI Translate:** Serviço de tradução automática que permite traduzir textos instantaneamente ou em lotes entre mais de 100 idiomas.
+ **Azure AI Speech:** Oferece conversão de fala em texto, texto em fala, tradução de fala e reconhecimento de locutor para criar aplicativos habilitados para voz.
+ **Azure AI Vision:** Capacidades de visão computacional para analisar imagens, ler textos com OCR e detectar rostos, entre outras funcionalidades.
+ **Azure OpenAI Service:** Acesso a modelos avançados da OpenAI, como GPT-4 e DALL-E, para tarefas de geração de texto, código e imagens.
+ **Azure AI Search:** Serviço de busca inteligente que permite integrar capacidades de pesquisa avançada em aplicativos, incluindo pesquisa semântica e de texto completo.
+ **Azure AI Document Intelligence:** Automatiza a extração de informações de documentos, como faturas e recibos, usando IA para melhorar a eficiência operacional.
+ **Azure AI Content Safety:** Detecta e modera conteúdo prejudicial ou inadequado em plataformas digitais, garantindo um ambiente seguro para os usuários.
+ **Azure Machine Learning:** Plataforma para construir, treinar e implantar modelos de aprendizado de máquina, com suporte para MLOps e integração contínua.
___
### **A inteligência artificial do Azure possui os melhores modelos de IA da categoria:**
+ **Azure AI Services:** Soluções pré-treinadas e prontas para uso para aplicações inteligentes.
+ **Azure Machine Learning:** Ferramentas de ciclo de vida completa para projetar e gerenciar modelos de IA.
+ **Responsible AI Tooling:** Cria e gerencia aplicações confiáveis por design.

### Azure AI Studio:
+ _Azure AI Studio:_ É uma plataforma abrangente para desenvolver e implantar copilots personalizados
+ O _Azure AI Studio:_ oferece uma ampla gama de serviços e modelos de IA para criar todo ciclo de vida de desenvolvimento de IA.
+ _Azure AI Studio:_ possui prototipagem rápida e sem atrito para resultados rápidos.
+ O _Azure AI Studio:_ oferece ferramentas de avaliação, segurança e teste de última geração para uma aplicação de LLM.

### Copilot Studio
+ O _Copilot Studio_ possui mais de 1400 conectores disponíveis, prontos para uso ou o usuário poderá também criar o seu próprio conector.
+ O _Copilot Studio_ possui canais como Microsoft Teams, Facebook e Slack, fáceis de configurar
+ O _Copilot Studio_ Possui gerenciamento de diálogos empresariais e orquestração de conversação.
___
# Modelos de linguagem
+ _Modelos de linguagem_ são sistemas de inteligência artificial que aprendem a gerar ou processar texto com base em exemplos de treinamento. Eles funcionam analisando grandes quantidades de texto para prever a próxima palavra ou frase com base no contexto anterior.
+ _Modelos de linguagem_ utilizam redes neurais profundas para capturar padrões e relações no texto. 

### Principais tipos de redes neurais mais usados:
+ **Modelos de Linguagem de Grande Escala (LLM):** São treinados em vastas quantidades de dados textuais para prever a próxima palavra ou frase com base no contexto anterior. Exemplo GPT-4.
+ **Transformers:** são uma arquitetura de redes neurais projetada para lidar com dados sequenciais, especialmente em tarefas de processamento de linguagem natural. Eles utilizam mecanismos de atenção para capturar dependências em longas sequências, permitindo que o modelo foque em partes relevantes da entrada. Isso os torna eficazes para tarefas como tradução automática, resumo de texto e geração de linguagem. Eles são a base de muitos modelos de linguagem modernos, como GPT.

Essas redes neurais permitem que os modelos compreendam e gerem texto de maneira muito semelhante à linguagem humana. 

O **Serviço OpenAI** do **Azure** é alimentado por um conjunto diversificado de modelos com diferentes funcionalidades e  preço. A disponibilidade do modelo varia de acordo com a região e a nuvem.

| Modelos | Descrição |
|---------|-----------|
| GPT-4º / GPT-4o mini / GPT-4 Turbo | Os modelos mais recentes do OpenAI do Azure com versões multimodal que podem aceitar texto e imagens como entrada. |
| GPT-4 | Um conjunto de modelos que aprimoram o GPT-3.5 e podem entender e gerar código e linguagem natural. |
| GPT-3.5 | Um conjunto de modelos que aprimoram o GPT-3 e podem entender e gerar código e linguagem natural. |
| Incorporações | Um conjunto de modelos que podem converter texto em um formulário de vetor numérico para facilitar a similaridade de texto. |
| DALL-E | Uma série de modelos que podem gerar imagens originais a partir de linguagem natural. |
| Whisper | Uma série de modelos em versão prévia que podem transcrever e traduzir uma fala em texto. |
| Conversão de texto em fala (versão prévia)* | Uma série de modelos em versão prévia que podem sintetizar a conversão de texto em fala. |

*Apresentação prévia: apresentação breve de algo antes do seu lançamento oficial.
