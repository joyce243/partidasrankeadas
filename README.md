function calcularNivel(vitorias, derrotas) {
    // Calcula o saldo de Rankeadas
    const saldoVitorias = vitorias - derrotas;
 // Determina o nível com base nas vitórias
    
 
let nivel;
    
  
if (vitorias < 10) {
        nivel = "Ferro";
    } 
    
    
else if (vitorias >= 11 && vitorias <= 20) {
        nivel = "Bronze";
    } 
    
else if (vitorias >= 21 && vitorias <= 50) {
        nivel ="Prata";
}

    
 else if (vitorias >= 51 && vitorias <= 80) {
        nivel ="Ouro";
}
else if (vitorias >= 81 && vitorias <= 90) {
        nivel ="Diamante";
    }
 else if (vitorias >= 91 && vitorias <= 100) {
        nivel ="Lendário";
    } 
     
     else {
        nivel = "Imortal";
    }
// Retorna a mensagem com o saldo e o nível
return `O Herói tem de saldo de ${saldoVitorias} está no nível de ${nivel}`;

console.log(resultado); // Exibe: O Herói tem de saldo de 45 está no nível de Ouro

    
