// Entrada dos atletas, como nomes e suas notas

let atletas = [
    {
      nome: "Cesar Abascal",
     notas: [10, 9.34, 8.42, 10, 7.88]   
    },
    {
      nome: "Fernando Puntel",
     notas: [8, 10, 10, 7, 9.33]   
    },
    {
      nome: "Daiane Jelinski",
     notas: [7, 10, 9.5, 9.5, 8]
    },
    {
      nome: "Bruno Castro",
     notas: [10, 10, 10, 9, 9.5]
    }
];
  
// Para saída no console de Nome:, Notas: e Média válida de forma que percorra toda a matriz.

for(let i = 0; i < atletas.length; i++){
  let atleta = atletas[i];
  let notas = atleta.notas;
  
  // Calcular a média de notas
  
  let notasAvaliadas = notas.sort((a, b) => b-a);
  notasAvaliadas = notas.slice(1, 4);
  let soma = 0;
  notasAvaliadas.forEach(function (nota){
    soma = soma + nota
  });
  let media = soma / notasAvaliadas.length;
  
  // Para saída no console.log
  
  console.log("Nome: " + atleta.nome);
  console.log("Notas: " + notas);
  console.log("Média válida: " + media);
  console.log("");
}
