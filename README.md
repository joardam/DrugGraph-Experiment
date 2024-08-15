# Projeto de Extração de Informações e Criação de Grafos

Este projeto utiliza uma LLM (Large Language Model) para extrair informações de um corpus textual, criando um grafo e estabelecendo suas conexões. O objetivo é visualizar e analisar as relações presentes no texto de forma estruturada e acessível.

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas:**
  - `os`
  - `string.Template`
  - `json`
  - `neo4j` (para conexão e manipulação do grafo)
  - `glob`
  - `timeit`
  - `dotenv`
  - `time`
  - `groq` (LLM utilizada para a extração de informações)
  - `concurrent.futures` (para execução paralela)
  - `logging`

## Estrutura do Projeto

1. **Extração de Informações:** Utiliza a LLM `groq` para analisar o corpus textual e identificar entidades e suas relações.
2. **Criação do Grafo:** As informações extraídas são organizadas em um grafo utilizando a plataforma `neo4j`, permitindo a visualização das conexões entre as entidades.


## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:
   ```
    pip install -r requirements.txt
   ```
3. Configure as variáveis de ambiente no arquivo .env. 
4. Configure suas chaves de API da Groq e do Neon4j. 
6. Sinta-se livre para alterar o Corpus textual e o prompt de obtenção das entidades e relações
7. Execute o script principal:
  python main.py


## Contribuições
Sinta-se à vontade para abrir issues e enviar pull requests. Toda contribuição é bem-vinda!

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.
