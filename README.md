
function dobro(numero: number): number {
    return numero * 2;
}
console.log(dobro(10)); // 20


function situacaoAluno(media: number): string {
    if (media >= 6) {
        return 'Aprovado';
    } else if (media >= 4) {
        return 'Recuperação';
    } else {
        return 'Reprovado';
    }
}
console.log(situacaoAluno(6)); // Aprovado
console.log(situacaoAluno(5)); // Recuperação
console.log(situacaoAluno(3)); // Reprovado

function calcularMedia(nota1: number, nota2: number): number {
    return (nota1 + nota2) / 2;
}
console.log(calcularMedia(4.0, 5.5)); // 8
