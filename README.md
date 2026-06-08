# Estruturas de Repetiçaão em java
A repetirção de rotinas pode ser realizada em Java das seguintes formas:

# Estrutura for

O loop for é ideal quando o número de iterações é conhecido previamente. Ele possui três partes: inicialização, condição e incremento. 

# Um exemplo básico:


for (int i = 0; i < 5; i++) {
 System.out.println("Número: " + i);
}

# Exemplo:

public class DoWhile {
    public static void main(String[] args) {
		int i = 0;
			do {
			System.out.println("Número: " + i);
			i++;
			} while (i < 5);
		}
        }
