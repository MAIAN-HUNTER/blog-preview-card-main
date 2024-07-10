# Frontend Mentor - Blog preview card solution

Olá a todos! este é mais um desafio de Front End mentor concluído com sucesso! É uma grande satisfação compartilha-lo com o mundo mais uma vez!

## Ideias, Planejamento e Execução
Outra vez, optei por deixar o mais simplificado e objetivo possivél. Porém com uma boa enfase na criatividade do design de layout no estilo blog, sem fugir da simplicidade. nada chamativo, totalmente limpo e facil tanto de interagir (com textos clicaveis) quanto de enxergar e ler. busquei por algo mais clean pois é o que desejo ver em sites na internet no geral, sem poluições visuais desagradaveis. adicionei também responsividades em resoluções diferentes para não fugir do basico para alcançar todos os usuarios possiveis. Foi estilizado um texto de titulo, com uma transição de cor suave, quando for selecionado, clicavel que leva à um site sobre frameworks de responsividade front-end. O outro texto estilizado, foi o nome do usuario que fez a publicação "HTML & CSS foundations", também foi adicionado uma sutil mudança de cor no nome deste usuario quando selecionado e também clicavél, levando o usuario para o meu perfil no linkedIn. Os links "Frontend Mentor"(clicavél, leva o usuario ao site Frontend Mentor) e "MAIAN-HUNTER"(clicavél, leva o usuario para o meu perfil no GitHub) também foram estilizados com a mesma sutileza.

### O que eu aprendi
Estilizações de design mais limpas agradaveis de se enxergar usando os recuros focus e hover, com um foco sutil em cores de destaque e textos com links clicavéis e funcionais.

### Feito usando

- HTML semantico com marcações
- CSS propriedades personalizavéis
- Flexbox

```html
<section class="container">
    <div>
      <img class="ilustration" src="/src/images/JS-imahe.jpg" alt="JS">

      <h1>Learning</h1>

        <p>Published 21 Dec 2023</p>

        <H2><a href="https://get.foundation" target="_blank">HTML & CSS foundations</a></H2>

        <p>These languages are the backbone of every website, defining structure, content, and presentation.</p>

  <img class="profile" src="/src/images/Dev.jpg" alt="User">
                    <a href="https://www.linkedin.com/in/maian-lucas-1a796026a/" target="_blank">Maian Lucas</a>
</div>
</section>
  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://github.com/MAIAN-HUNTER" target="_blank">MAIAN-HUNTER</a>.
  </div>
```
```css
.container{
    background-color: #eeeeee;
    display: flex;
    max-width: 500px;
    justify-content: center;
    border-radius: 22px;
    margin: 0 auto;
    margin-top: 400px;
    box-shadow: 18px 18px black;

}

div{
    margin: 30px;
}

.ilustration{
    max-width: 100%;
    border-radius: 16px;
}

h1{
    background-color: hsl(47, 88%, 63%);
    border-radius: 6px;
    max-width: 130PX;
    text-align: center;
}

h2 a{
    color: black;
    text-decoration: none;
}

h2 a:hover{
    color: hsl(47, 88%, 63%);
    transition: color 0.4s;
}

h2 :focus{
    color: hsl(34, 96%, 49%); 
}

.profile{
    border-radius: 150px;
    max-width: 30px;
    height:40px;
    width: 40px;
    position: relative;
    top: 10px;
}

a{
    text-decoration: none;
    color:black
}

a:hover{
    color: hsl(239, 100%, 50%);
    transition: color 0.4s;
}


.attribution {
 margin-right: 200px;
 padding: 30px;
 
}
/* For desktop */
@media (max-width: 2560px){
    .container{
            margin-left: 1000px;
            margin-bottom: 10px;
            max-width: 800px;
            height: 950px;
            align-items: center;
    }
        .ilustration{
            height: 400px;
        }

    div{
        font-size: 30px;
    }

    h1{
        max-width: 180px;
        height: 40px;
        padding: 10px;
        font-size: 30px;
    }

    .attribution{
        margin-right: 300px;
    }
    
}

@media (max-width: 1440px){
    .container{
        max-width: 390px;
        height: 500px;
        margin:0 auto;
        margin-top: 200px;
        
    }

    .attribution{
        margin: 100px;
        padding-right: 450px;
    }
    .ilustration{
        max-width: 350px;
        height: 200px;
    }

    div{
        font-size: 15px;
    }
    
    h1{
        max-width: 90px;
        height: 20px;
        padding: 5px;     
        font-size: 15px;
    }
}

/* For smartphones */
@media (max-width: 768px) {
    .container{
        max-width: 350px;
        margin-left: 190px;
        height: 400px;
        align-items: center;
}
    .ilustration{
        max-width: 300px;
        height: 150px;
    }

div{
    font-size: 12px;
}

h1{
    max-width: 50px;
    height: 10px;
    padding: 10px;
    font-size: 10px;
}

.attribution{
    padding-right: 220px;
    }
}
```

### Desenvolvimentos futuros
Pretendo continuar com os desafios propostos pelo site Frontend Mentor para aprimorar minha pericia em designs front end


### sites com recursos Úteis
- [site W3schools ](https://www.w3schools.com/css/css3_animations.asp)Este site me auxiliou a me localizar melhor nas diversas ferramentas de estilizações que o CSS tem a oferecer. Com certeza será um site que salvarei nos Favoritos.

## Autor

- Frontend Mentor - [@MAIAN-HUNTER](https://www.frontendmentor.io/profile/MAIAN-HUNTER)
- Linkedin - [Maian-Lucas](https://www.linkedin.com/in/maian-lucas/)

## Conhecimentos
92% de meu conhecimento foi adquirido pelo curso de programação Dev Quest, oa outros 8% foram de documentações de sites da internet como o proprio Frontend Mentor, W3schools e de videos da plataforma youtube.
