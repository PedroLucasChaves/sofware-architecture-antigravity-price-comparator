# 🚀 Antigravity Price Comparator

Um comparador de preços de produtos com painel web interativo. Ele processa um JSON base de produtos da Amazon, classifica as categorias e exibe históricos e variações de preços na interface visual.

## 🛠 Como Rodar o Projeto

Você precisa apenas do **Python 3** instalado (nenhum `pip install` é necessário, tudo roda nativamente).

Siga os passos abaixo na pasta raiz:

### 1. Classificar e Salvar Produtos no Banco
Primeiro, classifique os dados do JSON bruto e salve o registro atual no banco SQLite.
```bash
python classify_products.py
python main.py
```
*(Dica: Rode esses scripts diariamente caso o arquivo `.json` receba novas ofertas para criar o histórico).*

### 2. Abrir o Dashboard Web
Para visualizar o comparador:
```bash
python presentation/web_dashboard/app.py
```
*(Caso encontre erros ao imprimir na tela do console no Windows, você pode rodar usando o comando `$env:PYTHONIOENCODING="utf-8"; python presentation/web_dashboard/app.py` no PowerShell).*

### 3. Acessar
Abra seu navegador e entre em:
👉 **http://localhost:8080**
# sofwareArchitectureAntigravityPriceComparator
