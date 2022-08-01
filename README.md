# Alura - Solução do Projeto de Acessibilidade Web da Apeperia

Codificação da parte de acessibilidade de um projeto disponibilizado durante o curso de Front-end da [Alura](https://www.alura.com.br/formacao-front-end).

## Indíce

**Visão Geral**
>[Desafio](#desafio) |
>[Screenshot](#screenshot) |
>[Links](#links)

**Meu Processo**
>[Construído com](#construído-com) | 
>[O que eu aprendi](#o-que-eu-aprendi) | 
>[Recursos úteis](#recursos-úteis)

**Considerações Finais** 
>[Autor](#autor) |
>[Agradecimentos](#agradecimentos)


## Visão Geral

### Desafio

O desafio foi construir a parte de acessibilidade web deste projeto. Todo os usuários devem ser capazes de:

- Ter uma ótima experiência de navegação pelo site;
- Navegar por um site totalmente acessível para todas as pessoas. 

### Screenshot

![Captura de Tela (207)](https://user-images.githubusercontent.com/105252003/182256887-c276b7bb-29e9-4a65-b2ba-15980e7b0db3.png)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-Alura-Acessibilidade-Web/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Alura-Acessibilidade-Web/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- CSS pensado na acessibilidade;
- Proprieadades de acessibilidade web.

### O que eu aprendi

- Instalar e utilizar o leitor de tela NVDA;
- Utilizar os atributos lang, alt, role e aria;
- Fazer um formulário acessível usando label e placeholder;
- Colocar uma legenda em vídeo com a tag track;
- Fazer campos desabilitados com readonly.

```HTML

<a href="http://blog.apeperia.com.br/design/conheca-primeiras-etapas-criacao-logotipo-teste-teste" class="secaoDestaques-link" aria-labelledby="tituloDestaque1">
  <figure class="secaoDestaques-destaque">
    <img src="img/comecando-criar-logotipo.png" class="secaoDestaques-destaque-img" alt="Ferramentas de designer. Ilustração">
    <figcaption class="secaoDestaques-destaque-titulo"  id="tituloDestaque1">
      Conheça as primeiras etapas na criação de um logotipo
    </figcaption>
  </figure>
</a>
        
<label for="endereco">Endereço: </label>
<input type="text" id="endereco" class="contatoCampo-campoDesabilitado" readonly>

<video src="img/formacao-java.mp4" class="secaoInstitucional-video" controls>
  <track src="img/legenda-portugues-brasil.vtt" kind="subtitles" srclang="pt-br" label="Português (Brasil)">
</video>
```

### Recursos úteis

- [WCAG - Diretrizes de Acessibilidade para Conteúdo Web](https://www.w3.org/Translations/WCAG20-pt-br/) - Este é um guia incrível que me ajudou a entender melhor sobre quais são as diretrizes de acessibilidade para web. 
- [Atalhos do leitor de tela NVDA](https://webaim.org/resources/shortcuts/nvda) - Este é um outro guia muito importante para eu conhecer melhor sobre a ferramenta e os atalhos do NVDA.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan | Alura](https://beatrizslan.github.io/Projeto-Alura-Acessibilidade-Web/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.
