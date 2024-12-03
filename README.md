# Laboratário-de-Ciência-de-Dados
Repositório destinado a disciplina de Laboratório de Ciência de Dados (CK0441)

---

## Pré-requisitos  

Certifique-se de ter o **Python 3.6+** instalado no seu sistema.  

### Verificando a versão do Python  

Execute o seguinte comando no terminal:  
```bash
python --version
# ou
python3 --version
```

Se você não tiver o Python instalado, baixe-o em [python.org](https://www.python.org/downloads/).

---

## Configurando o Ambiente Virtual  


### Criando o ambiente virtual  

1. No diretório raiz do projeto, crie um ambiente virtual:  
   ```bash
   python -m venv env
   # ou, se o comando acima não funcionar
   python3 -m venv env
   ```

2. Isso criará um diretório chamado `env`, onde o ambiente virtual será armazenado.

---

### Ativando o ambiente virtual  

- **No Windows**:  
  ```bash
  .\env\Scripts\activate
  ```

- **No macOS/Linux**:  
  ```bash
  source env/bin/activate
  ```

Você saberá que o ambiente está ativo quando o nome do ambiente (`env`) aparecer antes do cursor no terminal, por exemplo:  
```bash
(env) user@machine:~$
```

---

### Instalando as dependências  

1. Após ativar o ambiente virtual, instale as dependências listadas no `requirements.txt`:  
   ```bash
   pip install -r requirements.txt
   ```

2. Aguarde enquanto as bibliotecas são instaladas. Quando o processo terminar, todas as dependências estarão configuradas no ambiente virtual.

3. No projeto foi utilizado a biblioteca jupyterlab para utilizar um ambiente jupyter, porém é opcional, ou seja, não é necessário para o funcionamento do projeto. Caso queira utilizar também, rode o seguinte código na linha de comando:
```bash
   pip install jupyterlab
   ```
---


## Desativando o Ambiente Virtual  

Quando terminar de trabalhar no projeto, você pode desativar o ambiente virtual usando o comando:  
```bash
deactivate
```

Isso retornará você ao ambiente global do Python.
