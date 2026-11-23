# Processamento de Linguagem Natural

Repositório voltado ao estudo de técnicas básicas sobre Processamento de Linguagem Natural.

---

## Objetivos
- Compreender os conceitos básicos de Processamento de Linguagem Natural  
- Realizar uso de bibliotecas como re (expressões regulares), nltk, spacy e alguns modelos recentes de LLM 

---

## Ferramentas usadas
- Python: NumPy, Matplotlib, NLTK, SpaCy, Scikit-learn
- Jupyter notebook, Google Colab

---

## Estrutura do repositório
- `resultados`: Pasta com arquivos .csv e imagens de resultados
- `src`: Pasta com os códigos

---

## Ambiente virtual (venv)
Para executar os códigos localmente (fora do Google Colab), recomenda-se criar um ambiente virtual na raiz do repositório. Assim, as bibliotecas do projeto ficam isoladas das demais instalações de Python da máquina.
 
### 1. Clonar o repositório
```bash
git clone <url-do-repositorio>
cd <nome-do-repositorio>
```
 
### 2. Criar o ambiente virtual
 
**Linux**
```bash
python3 -m venv .venv
```
 
**Windows**
```powershell
python -m venv .venv
```
 
### 3. Ativar o ambiente virtual
 
**Linux**
```bash
source .venv/bin/activate
```
 
**Windows (PowerShell)**
```powershell
.venv\Scripts\Activate.ps1
```
 
**Windows (Prompt de Comando - CMD)**
```cmd
.venv\Scripts\activate.bat
```
 
Com o ambiente ativo, o terminal exibe `(.venv)` no início da linha.
 
> **Observação (Windows):** caso o PowerShell bloqueie a execução do script de ativação, execute uma única vez:
> ```powershell
> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
> ```
 
### 4. Instalar as dependências
```bash
pip install --upgrade pip
pip install -r requirements.txt
```
 
 
### 5. Desativar o ambiente virtual
```bash
deactivate
```
 
> A pasta `.venv/` não deve ser enviada ao GitHub: ela já está listada no `.gitignore`. Para registrar novas dependências, use `pip freeze > requirements.txt`.

---

## Contribuições
Sinta-se à vontade para abrir *issues* e *pull requests* com sugestões de melhorias, correções ou novos materiais relacionados.

---

## Licença
Este repositório é licenciado sob a [MIT License](LICENSE).