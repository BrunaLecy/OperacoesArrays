# OperacoesArrays
Exercicio - Operações sobre Arrays

1. Após a execução da linha char[] alfabeto = {’A’, ’B’, ’C’, ’D’, ’E’, ’F’, ’G’, ’H’, ’I’}; em um método qualquer, responda:
a) Quantas posições tem o array?
R: 9 posições
b) Qual índice e valor da posição 4?
R: 

2. Qual será o conteúdo dos arrays declarados na aplicação abaixo ao término da execução do método main?

public class Arrays1
{
  public static void main(String[] argumentos)
  {
    double[] valores = {1,2,3,4,5,6};
    double[] primeiraCópia = valores;
    double[] segundaCópia = valores;
    primeiraCópia[1] = 1;
    segundaCópia[2] = valores[0]+primeiraCópia[1];
    primeiraCópia[3] = valores[1]+segundaCópia[2];
    valores[4] = primeiraCópia[2]+segundaCópia[3];
    valores[5] = segundaCópia[3]+primeiraCópia[4];
  }
}

R:

3. Qual será o conteúdo dos arrays declarados na aplicação abaixo ao término da execução do método main?

public class ArrayDeFloats
{
    public static void main(String[] argumentos)
    {
        float[] constantes = {100f,10f,1f,0.1f,0.01f,0.001f};
        float[] duplicata = constantes;
        resetaArray(duplicata);
    }
    private static void resetaArray(float[] array)
    {
        for(int índice=0;índice<array.length;índice++)
          array[índice] = 0f;
    }
}

R:
