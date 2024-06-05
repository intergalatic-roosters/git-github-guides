1. **Criar um Ambiente Virtual**:
   - Instale o `virtualenv` se ainda não estiver instalado:
     ```bash
     pip install virtualenv
     ```
   - Crie um novo ambiente virtual em um diretório específico (substitua `<nome_do_ambiente>` pelo nome desejado):
     ```bash
     virtualenv <nome_do_ambiente>
     ```

2. **Ativar o Ambiente Virtual**:
   - No Windows:
     ```bash
     .\<nome_do_ambiente>\Scripts\activate
     ```
   - No macOS e Linux:
     ```bash
     source <nome_do_ambiente>/bin/activate
     ```
   O prompt de comando deve agora mostrar o nome do ambiente virtual.

3. **Instalar as Dependências do `requirements.txt`**:
   - Certifique-se de que o arquivo `requirements.txt` esteja presente no diretório do seu projeto.
   - Instale as dependências listadas no arquivo `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

4. **Desativar o Ambiente Virtual**:
   - Quando terminar de trabalhar no projeto, desative o ambiente virtual:
     ```bash
     deactivate
     ```

Este tutorial fornece os passos básicos para configurar um ambiente virtual usando `venv` e instalar as dependências listadas em um arquivo `requirements.txt`.
