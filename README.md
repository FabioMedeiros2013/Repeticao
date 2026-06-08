# Estruturas de Repetiçaão em java
A repetirção de rotinas pode ser realizada em Java das seguintes formas:

# Estrutura for

O loop for é ideal quando o número de iterações é conhecido previamente. Ele possui três partes: inicialização, condição e incremento. 

# Exemplo:

public class ExemploFor {
    public static void main(String[] args) {
		for (int i = 0; i < 5; i++) {
			System.out.println("Número: " + i);
		}
        }
    }


# Estrutura while

O loop while é usado quando o número de iterações não é conhecido antecipadamente. Ele continua executando enquanto a condição for verdadeira. Exemplo:

public class ExemploWhile {
    public static void main(String[] args) {
		while ( i < 5; i++) {
			System.out.println("Número: " + i);
			i++;
		}
        }
    }
# Estrutura do-while

O do-while garante que o bloco de código seja executado pelo menos uma vez, pois a condição é verificada após a execução. Exemplo:

public class DoWhile {
    public static void main(String[] args) {
		int i = 0;
			do {
			System.out.println("Número: " + i);
			i++;
			} while (i < 5);
		}
        }

# Estrutura for-each

O for-each é usado para iterar sobre arrays ou coleções de forma simplificada, sem a necessidade de gerenciar índices. Exemplo:

public class ExemploForEach {
    public static void main(String[] args) {
        String[] nomes = {"Ana", "Bruno", "Carlos"};
        for (String nome : nomes) {
            System.out.println("Nome: " + nome);
        }
    }
}



