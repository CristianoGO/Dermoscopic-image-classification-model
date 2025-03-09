## Construção da rede neural otimizada com base na arquitetura MobileNetV2 para a classificação de lesões de pele em imagens dermatoscópicas

## Instruções do projeto

Neste repositório, você irá encontrar os arquivos e as recomendações para construção do modelo otimizado.
 
### Sistema operacional

* Linux Ubuntu (versão 24.04.1 LTS).
 
### Linguagem de programação 

* Python (versão 3.11.7).

### Ambiente de desenvolvimento da rede neural

* Jupyter Notebook ou Jupyter Lab nas versões mais recentes (versão 4.0.11). 
   
## Resultados:

### Relatório com os dados de treinamento:
 
![Relatório com os dados de treinamento](https://github.com/user-attachments/assets/a74592f4-1147-4854-968a-3d7d07d54e0a)

### Relatório com os dados de teste:
 
![Relatório com os dados de teste](https://github.com/user-attachments/assets/02207d75-1419-4625-b5c3-841593ff26f4)
 
![Matriz de confusão dos dados de teste](https://github.com/user-attachments/assets/9c72ef52-5772-447f-bb9c-fb9a3260b30f)

## Observação!
### Caso queria implementar o modelo em um aplicativo móvel será necessario alguns requisitos como:

* Converter o modelo para o formato TFLite, instruções disponíveis em: (https://www.tensorflow.org/lite/guide?hl=pt-br);
* caso queira testar o aplictivo com a rede neural implantada no formato TFLite acesse o repositório disponível em: (https://github.com/CristianoGO/skin-alert-app-classification.git);
* Fazer as alterações de acordo seu projeto.

## Passos para clonar o repositório para sua máquina local
1. **Abra o terminal e vá até o diretório onde deseja salvar o repositório:**
``` bash
   user@user-ubuntu-desktop:~$ cd /home/local_para_clonar
```
2. **Execute o seguinte comando para clonar:**
``` bash
   user@user-ubuntu-desktop:~$ git clone git clone https://github.com/usuario/repo.git
```
Substitua usuario pelo nome do dono do repositório e repo pelo nome do repositório.
Se o repositório for privado, você precisará de autenticação. Pode ser necessário usar um token de acesso do GitHub.

3. **Depois de clonar, entre no diretório do repositório com:**
``` bash
   user@user-ubuntu-desktop:~$ cd repo
```
4. **Instalar Dependências. Dependendo do tipo do projeto, você precisará instalar algumas dependências antes de executar.**
Python (se for um projeto Python)
Compile e execute usando:
``` bash
   pip install -r requirements.txt
```
5. **Execute o projeto (para rodar um projeto Python):**
``` bash
   python app.py
```
Após esses passos faça as alteraçẽos necessárioa no projeto para funcionar em seu ambiente de desenvolvimento.





