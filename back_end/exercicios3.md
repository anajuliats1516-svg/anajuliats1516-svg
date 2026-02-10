1-Escreva um programa que mostre na tela a seguinte contagem: 6 7 8 9 10 11 Acabou!
// Iteração simples de 0 a 4
for (let i = 6; i <= 11; i++) {
    // i++ é o incremento que evita o loop infinito
    console.log(`Contagem: ${i}`);
}
console.log('acabou');

2-Faça um algoritmo que mostre na tela a seguinte contagem: 10 9 8 7 6 5 4 3 Acabou!
// Iteração simples de 0 a 4
for (let i = 10; i  >= 3; i--) {
    // i++ é o incremento que evita o loop infinito
    console.log(`Contagem: ${i}`);
}
    console.log('acabou');

3-Crie um aplicativo que mostra na tela a seguinte contagem: 0 3 6 9 12 15 18 Acabou!
// Iteração simples de 0 a 4
for (let i = 0; i  <= 18; i+=3) {
    // i++ é o incremento que evita o loop infinito
    console.log(`Contagem: ${i}`);
}
    console.log('acabou');

 4-Desenvolva um programa que mostra na tela a seguinte contagem: 100 95 90 85 80 ... 0 Acabou!
// Iteração simples de 0 a 4
for (let i = 100; i  >= 80; i-=5) {
    // i++ é o incremento que evita o loop infinito
    console.log(`Contagem: ${i}`);
}
    console.log('acabou');

5-Faça um algoritmo que pergunte ao usuário um número inteiro e positivo qualquer e mostre uma contagem até esse valor: Ex: Digite um valor: 35 Contagem: 1 2 3 4 5 6 7 ... 33 34 35 Acabou!
const rl = readline.createInterface({
  input: process.stdin,   // Entrada: teclado
  output: process.stdout  // Saída: terminal
});

rl.question('Digite o primeiroconst readline = require('readline');
 número: ', (num1) => {

for (let i = 0; i <= num1; i++) {
    console.log(`Contagem: ${i}`);
}
 // Fecha a interface de leitura       
 rl.close();     
    
    
});  
console.log('Acabou!');
