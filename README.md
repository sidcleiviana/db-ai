DB TALK - AI é um aplicativo interativo desenvolvido com Python e Streamlit, que permite aos usuários consultar bancos de dados usando SQL gerado por IA. Ele oferece suporte a modelos locais de IA ou modelos baseados em nuvem (como OpenAI GPT) e fornece resultados como tabelas e gráficos.

🚀 Recursos
Suporta SQLite, PostgreSQL e MySQL
Geração de SQL com tecnologia de IA usando modelos baseados em nuvem ou modelos de IA locais
Extração automática de esquema de banco de dados com confirmação de substituição
Arquivos de esquema salvos com UUIDs exclusivos ou nomes predefinidos
Visualização de gráfico (barra, pizza e linha)
Interface web Streamlit para fácil interação
Gerenciamento seguro de conexões de banco de dados usando um arquivo de configuração
Banco de dados modular suporta bancos de dados SQL
Descoberta de modelo dinâmico para ambos:
Modelos GGUF locais (detectados automaticamente no diretório data/models/)
Modelos locais do Transformer (carregados de data/config/models.json)
Suporta vários provedores de IA:
OpenAI GPT
DeepSeek IA
IA Gêmeos
Grok IA
IA antrópica
Modelos de transformadores locais (usando Hugging Face)
Modelos GGUF locais (usando GPT4All)
Suporta um diretório raiz personalizado usando a variável de ambiente DB_TALK_AI_ROOT
