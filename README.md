
 Luis henrique
 
 calculadora.js

function somaMultiplica(a, b, multiplicador) {
  const soma = a + b;
  const resultado = soma * multiplicador;
  return resultado;
}


function subtraiDivide(a, b, divisor) {
  const subtracao = a - b;
  const resultado = subtracao / divisor;
  return resultado;
}

console.log("Soma e multiplica:", somaMultiplica(2, 3, 4)); // (2+3)*4 = 20
console.log("Subtrai e divide:", subtraiDivide(10, 4, 2));  // (10-4)/2 = 3
