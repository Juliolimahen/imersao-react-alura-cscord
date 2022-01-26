# Imersão React Alura

Desenvolvimento do AluraCord
    (Aplicação WEB simulando o funcionamento de Discord)
### Aula 1
Documentação Next-JS
    - https://nextjs.org/docs/getting-started

Instalando dependências 

    - yarn init -y

    - yarn add next react-dom

    - adicionar  ao package.json 
        "scripts": {
                    "dev": "next dev",
                    "build": "next build",
                    "start": "next start",
                    "lint": "next lint"
                    }

Criando primeira Pagina

    - './pages/index.js'

Comando para rodar aplicação em modo dev
    - yarn dev


Publicando Aplicação 

    - https://coffeecord.vercel.app/

### Aula 2

Aprofundar sobre o funcionamento: 

    - useState 
    - useRouter
    - onChange
    - onSubmit
=======

#### Desafio 1
  Validação 
       - se o campo login tiver menos de 2 caracteres
            não mostrar a imagem e desativar o botão 
       - senão 
           executar normalmente 
