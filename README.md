# Jogo de Dados Java  :game_die:
## Programa ao ser executado mostrará a face do dado. Bora Jogar!  

[![Linkedin Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white&link=https://www.w3schools.com/java/default.asp)](https://www.w3schools.com/java/default.asp)

```
public class JogoDoDado {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		//Declarando variavel
		char op = 's';
		
		Scanner sc = new Scanner(System.in);
		
		//Lógica usando laço while para gerar número aleatório
		while(op == 's') {
			System.out.println("Lançamento do Dado...");
			System.out.println("");
			
			int dado = (int) (Math.random() * 6 + 1);
			System.out.println("Face do dado: " + dado);
			System.out.print("Deseja lançar o dado novamente: ('s' para sim ou qualquer tecla para sair) ? ");
			op = sc.next().charAt(0);
			System.out.println();
		}		

	}
}
```

