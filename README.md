# Aplicativo Web com Análise de Dados de Exportação de Vinho Brasileiro entre 2007 e 2021

Este projeto em um aplicativo web que tem por objetivo otimizar a análise de dados referentes a exportação de vinho entre 2007 e 2021 disponibilidados pela Vitibrasil, segmentando a análise por país e apresentando prospecções futuras para auxiliar na tomada de decisão.

### Pré-requisitos

Certifique-se de ter o Python 3.11 instalado em seu sistema.

Para sistemas baseados em Linux (Ubuntu/Debian), instale o suporte ao ambiente virtual:

```bash
sudo apt update && sudo apt install python3.11-venv
```

### Instalação

Siga os passos abaixo para configurar o ambiente e instalar as dependências:

```bash
# clonar o repositório (substitua pela sua URL se necessário)
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

# criar o ambiente virtual
python -m venv venv

# ativar o ambiente virtual
# No Linux/Mac:
source venv/bin/activate
# No Windows:
venv\Scripts\activate

# instalar as dependências
pip install -r requirements.txt
```

### Como Rodar a Aplicação

Com o ambiente virtual ativado, execute o comando abaixo para iniciar o aplicativo localmente:

```bash
streamlit run app.py
```

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **Frontend/App** | **Streamlit** | `1.32.2` | Framework para desenvolvimento de aplicativo web ||
| **Análise de Dados** | **Pandas** | `2.2.1` | Biblioteca para manipulação de dados |
| **Visualização** | **Plotly** |`5.20.0` | Biblioteca para criação de gráficos dinâmicos e interativos |
| **Linguagem** | **Python** | `>=3.11` | Linguagem para desenvolvimento de scripts 
| **Gerenciamento** | **Venv** | `-` | Gerenciador de ambientes virtuais para isolamento de dependências |

### Fonte de Dados

Os dados utilizados neste projeto foram extraídos da site Vitibrasil (Embrapa).

Link para a base de dados: http://vitibrasil.cnpuv.embrapa.br/index.php?opcao=opt_06

### Deploy

O aplicativo web está disponível via Streamlit Cloud.

Link para o aplicativo web: https://postechtechchallengefase1-nzyixopq8dxumqrhuvfe7r.streamlit.app/
