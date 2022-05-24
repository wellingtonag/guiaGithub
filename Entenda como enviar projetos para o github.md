# **Entenda como enviar projetos para o github .**

Neste tutorial vamos partir do pressuposto que você já tem o git instalado na sua máquina. 

## **Criando nosso repositório no github**

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image002.png)

 ![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image004.png)

  (Você pode colocar qualquer nome ali em “repository name”)

Agora vamos iniciar o git em uma pasta do seu projeto. Se você já tem um projeto existente, esse tutorial também serve. Vamos lá!

## Iniciando o git na sua pasta:

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image006.jpg)

Clique com o botão direito do mouse dentro da pasta do seu projeto e aparecerá essas opções:  

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image008.png)

Clique em "git bash here" e irá abrir um terminal onde você digitará "git init". Pressione "enter" no teclado. 

## Commitando arquivos em nosso repositório 

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image010.png)

Agora vamos dar o **commit** no projeto. Digite **git commit -m "...''**. Dentro destas aspas vamos colocar qualquer mensagem. Recomenda-se que você digite no commit a modificação que está fazendo no repositório, que no meu caso é o envio de um arquivo de texto. 

 Agora vamos dizer ao git que adicione os arquivos que serão adicionados. 

## Adicionando um novo arquivo ao repositório

Digite **git add nomeDoArquivo** ou se você quiser adicionar todos os arquivos da sua pasta, pode dizer **git add .** 

Esse “.” (ponto) indica para o git “adicione tudo que estiver na pasta”. 

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image011.png)

## Verificando se os arquivos foram adicionados. 

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image012.png)

Agora que adicionamos um arquivo, vamos ver se está tudo ok com o comando **git status** 

Se o nome estiver verde, como no print, tudo ocorreu bem! Se estiver vermelho, você pode verificar se escreveu git add . corretamente, lembrando que o ponto fica separado do add e se você escreveu o nome do arquivo ao invés do ponto, verifique se seu arquivo não tem letras maiúsculas, caracteres especiais ou espaçamentos. 

## Adicionando os arquivos à branch

Estamos a poucos passos. Você deve digitar **git branch -M main** e pressionar **enter**. 

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image013.png)

##  **Conectando-se com seu repositório no github:** 

Assim que você criou seu projeto, deve ter aparecido um link na sua tela,copie esse link, vamos usar ele para referenciar para onde vamos mandar nossos arquivos para o github usando o comando **git remote add origin link**.

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image015.png)

 ![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image016.png)

## Finalmente enviando o arquivo selecionado para o github:

Agora que criamos nosso projeto na máquina local, iniciamos um repositório, adicionamos a mensagem no nosso commit, adicionamos o arquivo aos arquivos que serão enviados e adicionamos o projeto à branch, iremos enviar nosso projeto com o comando **git push -u origin main.** 

Com esse comando você está dizendo a git para dar um push (empurrar, em português) para **main** do repositório.

![img](file:///C:\Users\WELLIN~1\AppData\Local\Temp\msohtmlclip1\01\clip_image017.png)

Pronto! Arquivo enviado ao repositório. 

Fonte: https://minhastack.com/git-e-github/

 

 