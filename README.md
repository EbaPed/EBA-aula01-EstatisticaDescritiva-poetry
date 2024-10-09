# **Aula 01- Estatística Descritiva**

---

## **Objetivo da Aula**
Nesta aula, iremos explorar como iniciar uma análise descritiva, abordando os conceitos gerais, medidas de centralidade, dispersão e gráficos mais utilizados.


## **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Além disso, um arquivo `requirements.txt` é fornecido para que você possa instalar as bibliotecas necessárias em um **ambiente virtual** isolado, sem afetar seu sistema operacional.

### **- Passo a passo para configuração do ambiente virtual:**

Crie uma pasta no seu computador onde deseja armazenar o repositório.

Com a pasta criada, navegue até ela e siga os passos abaixo:

**1. Clonar o Repositório**

No seu computador, abra o GitBash e , faça o clone deste repositório para o seu computador:

```bash
git clone https://github.com/EbaPed/EBA_aula01_EstatisticaDescritiva.git
```

**2. Criar um Ambiente Virtual**

Um ambiente virtual permite que você mantenha as bibliotecas utilizadas no projeto isoladas do sistema global. Para criar o ambiente, siga as instruções de acordo com seu sistema operacional:

**Pela linha de comando Windows:**

Abra o terminal (pode ser o **PowerShell ou cmd**).
Navegue até a pasta do repositório clonado:

```powershell
cd caminho/para/sua/pasta
```

Crie o ambiente virtual usando o comando:

```powershell
python -m venv venv
```

Ative o ambiente virtual:

```powershell
.\venv\Scripts\Activate
```

Se você estiver utilizando o **GitBash** para ativar o ambiente virtual faça:

```bash
source venv/Scripts/activate
```

**Observação:** Ao ativar o ambiente virtual, você verá o nome do ambiente (no caso, `venv`) aparecendo no início do seu terminal, indicando que ele está ativo.


**3. Configurar o kernel do notebook para o ambiente virtual**

Com o ambiente virtual ativado, você precisa instalar o ipykernel:

```bash
pip install ipykernel
```
- No Jupyter Notebook, ao abrir ou criar um novo notebook:

- No canto superior direito, você verá uma opção chamada `Kernel`.
Clique em `Kernel > Change kernel`.
Selecione o kernel chamado `Python (venv)` (ou o nome que você usou ao registrá-lo).

Caso o kernel `Python (venv)` não tenha aparecido ainda, rode o código na linha de comando:

```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```


**4. Instalar as Bibliotecas Necessárias**

Com o ambiente virtual ativo, agora você pode instalar todas as bibliotecas listadas no arquivo `requirements.txt`. 
Execute o seguinte comando no notebook:

```python
!pip install -r requirements.txt
```

Isso garantirá que todas as dependências do projeto sejam instaladas localmente no ambiente virtual.

**5. Reproduzir o Gabarito (Opcional)**

Dentro deste repositório, você encontrará um notebook com o gabarito das atividades da aula. Se quiser, pode revisá-lo para entender como implementar as atividades da forma mais eficiente. No entanto, incentivamos que crie seu próprio notebook para desenvolver suas habilidades analíticas. 

**6. Criar seu Próprio Notebook**

Agora que o ambiente está configurado e as bibliotecas estão instaladas, você pode começar a criar seu próprio notebook para a aula, utilizando as mesmas ferramentas e bibliotecas do gabarito.

Crie um novo arquivo notebook (ex: aula01_minhasolucao.ipynb) e siga as instruções da aula para realizar sua própria análise.

Lembre-se de não copiar o código do gabarito, mas sim usar ele como referência para desenvolver seu próprio trabalho.

**7. Como Desativar o Ambiente Virtual**

Após finalizar o trabalho, você pode desativar o ambiente virtual a qualquer momento usando o comando:

```bash
deactivate
```

**8. Executar o Código**

Agora que o ambiente está configurado e as bibliotecas estão instaladas, você pode executar os códigos Python fornecidos no repositório.



