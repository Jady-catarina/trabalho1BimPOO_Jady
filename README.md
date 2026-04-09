# trabalho1BimPOO_Jady
## SkyBlue
Para mostrar uma mensagem na tela, podemos utilizar o código:


  public class trabalhoTeste {	
  
		public static void main(String[] args) {
    
				System.out.println("Olá, seja bem vindo(a) à SkyBlue!");
        
		}
    
	}
  

A linha: **public class trabalhoTeste {** define que estamos iniciando a estrutura de uma classe pela palavra reservada ***class*** e é seguida pelo nome da classe. A { define a abertura de um bloco de comando.

Na linha: **public static void main(String[] args) {** é utilizado o método ***main***, onde toda a execução do programa deve ocorrer a partir dele.

Na linha: **System.out.println("Olá, seja bem vindo(a) à SkyBlue!");** o método ***System.out.println*** é responsável por escrever na saída-padrão do computador o conteúdo entre ("..."), como por exemplo, a frase utilizada no código acima: _"Olá, seja bem vindo(a) à SkyBlue!"_.



public class Teste:
public: Modificador de acesso, significa que a classe pode ser acessada por qualquer outra classe.
class: Palavra-chave usada para definir uma classe em Java.
Teste: O nome da classe. Importante: Em Java, se o código estiver em um arquivo, ele deve se chamar Teste.java.
public static void main(String[] args):
Este é o método main. Ele é o ponto de entrada de qualquer aplicação Java; é onde o programa começa a rodar.
static: Significa que o método pode ser chamado sem criar um objeto da classe Teste.
void: Indica que o método não retorna nenhum valor.
(String[] args): Parâmetro que permite passar argumentos de linha de comando para o programa.
System.out.println("...");:
System: É uma classe final pré-definida no Java que fornece acesso ao sistema.
out: É um membro estático da classe System, responsável pela saída padrão (console).
println: É o método (função) usado para imprimir o texto na tela e pular para a próxima linha.
"Olá, seja bem vindo(a) à SkyBlue!":
O texto dentro das aspas duplas é uma String (cadeia de caracteres) que será exibida exatamente como está no console
