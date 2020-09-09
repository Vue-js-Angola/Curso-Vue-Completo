# Curso-Vue-Completo

## Primeiro exemplo

```
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script> <!-- Importando o Vue JS -->

<div id="app">
    <p>{{ title }} </p> <!-- Pegando o title da minha minha Vue, uso {{}} -->
</div>

<script>
    /* Instanciando uma nova Vue, com o construtor, repare que não precisei fazer " v = new Vue " pois
    o Vue já faz todo esse processo. */
    new Vue({
        el: '#app', /* Qual trecho do html vou controlar, passando o elementoem forma de ID */
        data: { 
            title: "Curso de Vue"
        }
    })
</script>
```
