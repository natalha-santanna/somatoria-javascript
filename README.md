# somatoria javascript
 curso java script, somatoria com parsetIn

<!DOCTYPE html>
<html>

<head>
    <title>js03_parseInt.htm - somatoria</title>
    <meta http-equiv="Content-Type" content="text/html" ; charset=iso-8859-1 ">
<meta http-equiv="Content-Type " content="text/html "; charset=utf-8">
    <meta charset="utf-8" />
</head>
<html>

<body>
    <h3>Somatoria de dois numeros inteiros</h3>
    <script language="JavaScript">
        <!--
        /* Objetivo: desenvolver um ´rograma em JavaScript que faça a leitura de 2 números inteiros e apresente o resultado da soma entre eles.
         */

        /* Definição das variáveis*/
        var js_n1;
        var js_n2;
        var js_soma;

        /* Entrada de Dados */
        js_n1 = parseInt(window.prompt('Informe o primeiro numero:', 'Digite aqui'));
        js_n2 = parseInt(window.prompt('Informe o segundo numero:', 'Digite aqui'));

        /* Processamento de Dados */
        js_soma = js_n1 + js_n2;

        /* Saída de Dados */
        document.write('O Resultado da soma= ' + js_soma);
    </script>
</body>

</html>