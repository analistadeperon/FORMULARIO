# FORMULARIO
<form action="#" method="post">
  <fieldset>
      <fieldset class="grupo">
          <div class="campo">
              <label for="nome">Nome</label>
              <input type="text" id="nome" name="nome" style="width: 10em" value="">
          </div>
          <div class="campo">
              <label for="snome">Sobrenome</label>
              <input type="text" id="snome" name="snome" style="width: 10em" value="">
          </div>
      </fieldset>
      <div class="campo">
          <label>Sexo</label>
          <label>
              <input type="radio" name="sexo" value="masculino"> Masculino
          </label>
          <label>
              <input type="radio" name="sexo" value="feminino"> Feminino
          </label>
      </div>
      <div class="campo">
          <label for="email">E-mail</label>
          <input type="text" id="email" name="email" style="width: 20em" value="">
      </div>
      <div class="campo">
          <label for="telefone">Telefone</label>
          <input type="text" id="telefone" name="telefone" style="width: 10em" value="">
      </div>

      <fieldset class="grupo">
          <div class="campo">
              <label for="cidade">Cidade</label>
              <input type="text" id="cidade" name="cidade" style="width: 10em" value="">
          </div>
          <div class="campo">
              <label for="estado">Estado</label>
              <select name="estado" id="estado">
                  <option value="">--</option>
                  <option value="PR">PR</option>
              </select>
          </div>
      </fieldset>

      <div class="campo">
          <label for="mensagem">Mensagem</label>
          <textarea rows="6" style="width: 20em" id="mensagem" name="mensagem"></textarea>
      </div>

      <div class="campo">
          <label>Newsletter</label>
          <label>
              <input type="checkbox" name="newsletter" value="1"> Gostaria de receber a Newsletter da empresa
          </label>
      </div>

      <button type="submit" name="submit">Enviar</button>
  </fieldset>
</form>
<html>
<head>
<style type="text/css">
input { 
background-color: #B0E0E6; 
font: 12px verdana, arial, helvetica, sans-serif;
color:#003399;
border:2px solid #000099;
}
</style>
</head>
<body>
<form name="form1" method="post" action="">
<input type="radio" name="radiobutton"
 value="radiobutton">
</form>
<form name="form2" method="post" action="">
<input type="checkbox" name="checkbox"
 value="checkbox">
</form>
<form name="form3" method="post" action="">
<input type="text" name="textfield">
</form>
<form name="form4" method="post" action="">
<input type="submit" name="Submit" 
value="Enviar">
</form>
</body>
</html>
<html>
<head>
<style type="text/css">
select { 
background-color: #B0E0E6;
font:12px verdana, arial, helvetica, sans-serif;
color:#003399;
}
</style>
</head>
<body>
<form name="form5" 
method="post" action="">
<select name="select">
<option value="item_1">
item_1 da lista</option>
<option value="item_1">
item_2 da lista</option>
<option value="item_1">
item_3 da lista</option>
<option value="item_1">
item_4 da lista</option>
</select>
</form>
<html>
<head>
<style type="text/css">
textarea { 
background-color: #B0E0E6;
font:12px verdana, arial, helvetica, sans-serif;
color:#072f86;
}
</style>
</head>
<body>
<form name="form6" method="post" action="">
<textarea name="textarea" rows="9"></textarea>
</form>
</body>
</html>
<html>
<head>
<style type="text/css">
form.login { background-color: #FFFFCC; 
width:380px;
font: 11px Verdana, sans-serif;
color: #003399;
border: 2px solid #0000FF;
padding-left:10px;
}
</style>
</head>
<body>
<form name="login"method="post" 
action="#" class="login"> 
<label>Usuário: 
<input name="user" type="text" tabindex="1" size="15"> 
</label>
<label>Senha: 
<input name="password" type="password" tabindex="2" size="15"> 
<input type="submit" name="Submit" value="OK" tabindex="3"> 
</label> 
</form>
</body>
</html>

</body>
</html>
<form name="login"method="post" action="#"> 
  <label>Usuário: 
  <input name="user" type="text" tabindex="1" size="15"> 
  </label>
  <label>Senha: 
  <input name="password" type="password" tabindex="2" size="15"/> 
  <input type="submit" name="Submit" value="OK" tabindex="3"> 
  </label> 
  </form>
