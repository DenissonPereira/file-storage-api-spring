# 👽 File Storage API Spring

# 📑 Sobre o projeto 

O projeto é uma aplicação em **java** desenvolvida utilizando o framework **Spring Boot** para oferecer uma **API** de armazenamento de arquivos. Essa **API** permite que os usuários *enviem*, *baixem* e *listem* arquivos de um diretório específico no servidor. A estrutura do projeto foi organizada de acordo com as práticas recomendadas do **Spring Boot**, incluindo a separação de classes em diferentes pacotes. A funcionalidade principal da **API** inclui o **upload de arquivos**, a **geração de links para download** e a **listagem dos arquivos disponíveis**. Com isso, o projeto proporciona uma solução eficiente e escalável para gerenciar o armazenamento e o acesso a arquivos em um ambiente de aplicação *web*.


## 📚 Stack Tecnológica

<img src="./public/menina.gif" min-width="100px" max-width="100px" width="100px" align="right" alt="Computador iuriCode">

[![Badge](https://img.shields.io/badge/Java-17-%23FFA500?style=flat&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Badge](https://img.shields.io/badge/Spring%20Boot-3.2.3-%236DB33F?style=flat&logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![Badge](https://img.shields.io/badge/Spring_Web-2.6.4-%236DB33F?style=flat&logo=spring&logoColor=white)](https://spring.io/projects/spring-framework)


# 🚀 Como executar o projeto 🚀

## ⬇️ Clonar repositório git

```
git clone https://github.com/DenissonPereira/file-storage-api-spring
```

## 👷 Construir o projeto

```
./mvnw clean package
```

## ✨ Tudo pronto! ✨

Para testar o projeto, após iniciar a aplicação, procure um arquivo e digite no terminal:

```
curl -X POST -F "file=@(nome do arquivo sem parênteses)" http://localhost:8080/api/files/upload
```

Após isso, acesse a pasta do projeto e localize a pasta de uploads. Você verá que o arquivo estará lá dentro. Outra maneira de visualizar o arquivo é usando o caminho "/list". Para isso, digite no seu navegador o seguinte endereço:

```
http://localhost:8080/api/files/list
```

# 📸 Visuals and Screenshots

Dê uma espiada no nosso projeto em funcionamento e esclareça todas as suas dúvidas sobre como executá-lo!

## 🏂 Aplicação em ação
![Web 1](./public/images//upload.giff) 

## 📺 Editor de código

Neste projeto, foi utilizado o Visual Studio Code como editor de código.

[![Badge](https://img.shields.io/badge/VSCode-1.65.0-%23007ACC?style=flat&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)


# 🚨 Aguarde! Ainda não terminou!

>Este projeto está atualmente em desenvolvimento, e está sujeito a futuras atualizações e melhorias conforme evolui. Estamos trabalhando para torná-lo ainda mais robusto e funcional ao longo do tempo. Agradecemos sua paciência e interesse nesta fase inicial.

>Além disso, gostaríamos de ressaltar que este projeto é aberto a contribuições de qualquer pessoa interessada em colaborar. Se você tem ideias, sugestões ou melhorias para oferecer, sinta-se à vontade para participar do desenvolvimento do projeto. Juntos, podemos criar algo incrível e beneficiar a comunidade de forma colaborativa.

## 📜 Licença

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DenissonPereira/file-storage-api-spring/blob/main/LICENSE) 

## ✏️ Autor 

Denisson Pereira Santos

<div> 
<a href="https://www.linkedin.com/in/denisson-pereira" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"  target="_blank"></a> 
<a href="https://denissonpereira.com" target="_blank"><img src="https://img.shields.io/badge/Meu%20Site-%2333cc33?style=for-the-badge&logo=fontawesome&logoColor=white&logoWidth=15&labelColor=black"  target="_blank"></a> 
<a href="https://github.com/DenissonPereira" target="_blank"><img src="https://img.shields.io/badge/GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white&logoWidth=15&labelColor=black"  target="_blank"></a> 
<a href="https://www.instagram.com/denisson_pereira1?igshid=OGQ5ZDc2ODk2ZA%3D%3D&utm_source=qr" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</div>&nbsp;&nbsp;