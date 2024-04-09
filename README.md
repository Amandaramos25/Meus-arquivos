# Meus-arquivos

public class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!");
        int v[] = {10,20,30,40,50};
        int soma = 0;
        //soma os valores
        somaValores(soma,v,5);
        //calcula a media
    }

    public static int somaValores(int soma, int v[],int n) {
        for(int i = n;i<1;i++){
            soma = soma + v[i];
        }
        return soma;
    }
    public void calculaMedia() {
        
        
    }
}
