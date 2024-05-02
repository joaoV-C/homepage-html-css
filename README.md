# homepage-html-css
Exercício de criação de uma homepage com HTML/CSS do módulo 3 do curso Avançado em Desenho e Programação de Websites

DOMi & JD BECK homepage

Tentei seguir um pouco da linha estética que percebo ser adotada pela dupla.
As cores são contrastantes, mas não consegui ousar tanto quanto gostaria, já que 
a dupla tem uma estética bastante irreverente e única.
Fiz uma ilustração estilizada através de vetor no Figma e tentei deixá-la como 
ponto de destaque da página.

Dividi meus aquivos css em main, hover e responsive:
    o main contém a maior parte do código e basicamente tem as principais estilizações;
    separei o código do dropdown no hover-styles.css já que é uma estilização mais específica
e facilita o trabalho;
    no responsive.css utilizei tags de mídia para deixar a página minimamente responsiva. Preferi separar
e agrupar todos os @media para conseguir encontrá-los e manipulá-los mais facilmente.

Resultado das validações.

Da primeira vez que validei surgiram alguns problemas. A ferramenta de validação dizia que <h4> e <p>
não poderiam ser filhos de <span>, então substituí os spans da div.tour por <div>. 
Também recomendaram trocar as barras inversas que estavam na src das img.

-->https://validator.w3.org/nu/
-Nu Html Checker-
"Document checking completed. No errors or warnings to show."

-->https://jigsaw.w3.org/css-validator/validator
-Resultados da validação CSS do W3C para main-styles.css (CSS nível 3 + SVG)-
"Parabéns! Não foram encontrados erros na sua folha de estilo."

-Resultados da validação CSS do W3C para hover-styles.css (CSS nível 3 + SVG)-
"Parabéns! Não foram encontrados erros na sua folha de estilo."

-Resultados da validação CSS do W3C para responsive.css (CSS nível 3 + SVG)-
"Parabéns! Não foram encontrados erros na sua folha de estilo."
