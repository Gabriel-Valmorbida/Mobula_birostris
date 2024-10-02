
# Mobula_birostris
#### Formulário Pogger's

O modelo de formulário foi criado utilizando a linguagem HTML e CSS, na parte do HTML temos 4 campos: Nome, Idade, Cidade e CPF para serem preenchidos e um botão para enviar os dados.
dentro do codigo HTML pode se encontrar o elemento form que formalmente define o formulário e os atributos que definem a maneira como esse formulário se comporta. As tags de <label/> e <input/> ela especifica qual o “rótulo” do input (a que se refere o input, como por exemplo, juntar em um texto “Nome completo”).

  ~~~python
 <label for="nome">Nome:</label>
  <input type="text" id="nome" name="usuario_nome" />
  ~~~
 ~~~python
    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="usuario_idade" 
      min="1" max="100"/>
 ~~~
 >No codigo acima, por exemplo, eu usei o type=number para determinar depois um limite para a idade.
>

No codigo de CSS temos propriedades como o Border, uma propriedade que adiciona um contorno em volta de um elemento HTML. Também temos as propriedades que define a área de margem nos quatro lados do elemento (margin) e que determina a largura da área de conteúdo de um elemento (windth).
~~~css
form {
  margin: 0 auto;
  width: 300px;

  padding: 1em;
  border: 10px solid #5b535f;
  border-radius: 1em

}
~~~
Voltando ao HTML, o codigo do botão é o mais simples de se fazer, basta colocar div class=button e ponhar type=submit
~~~python
<div class="button">
    <button type="submit">Enviar dados</button>
  </div>
~~~
O codigo HTML completo está abaixo.
~~~html
<body>
  <form>
<div>
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="usuario_nome" />
</div>
  <div>
    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="usuario_idade" 
      min="1" max="100"/>
  </div>
  <div>
    <label for="cidade">Cidade:</label>
    <input type="text" id="cidade" name="usuario_cidade"/>
  </div>
  <label for="cpf">CPF:</label>
  <input type="text" id="cpf" name="usuario_cpf"/>
  </div>
  
  <div class="button">
    <button type="submit">Enviar dados</button>
  </div>
  </form>
  <script src="script.js"></script>
</body>
~~~
O codigo CSS completo está abaixo.
~~~CSS
body {
text-align: center
}
form {
  margin: 0 auto;
  width: 300px;

  padding: 1em;
  border: 10px solid #5b535f;
  border-radius: 1em

}
~~~
