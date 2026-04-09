# trabalho1BimPOO_Jady
## SkyBlue
Para mostrar uma mensagem na tela, podemos utilizar o código:


  public class trabalhoTeste {	
  
		public static void main(String[] args) {
    
				System.out.println("Olá, seja bem vindo(a) à SkyBlue!");
        
		}
    
	}
  


**public class Teste:**
- **public:** Modificador de acesso, significa que a classe pode ser acessada por qualquer outra classe.
- **class:** Palavra-chave usada para definir uma classe em Java.
- **Teste:** O nome da classe. Importante: Em Java, se o código estiver em um arquivo, ele deve se chamar Teste.java.

 **public static void main(String[ ] args):**
- Este é o método main. Ele é o ponto de entrada de qualquer aplicação Java; é onde o programa começa a rodar.
- **static:** Significa que o método pode ser chamado sem criar um objeto da classe Teste.
- **void:** Indica que o método não retorna nenhum valor.
- **(String[ ] args):** Parâmetro que permite passar argumentos de linha de comando para o programa.

**System.out.println("...");:**
- **System:** É uma classe final pré-definida no Java que fornece acesso ao sistema.
- **out:** É um membro estático da classe System, responsável pela saída padrão (console).
- **println:** É o método (função) usado para imprimir o texto na tela e pular para a próxima linha.
  
**"Olá, seja bem vindo(a) à SkyBlue!":**
O texto dentro das aspas duplas é uma String (cadeia de caracteres) que será exibida exatamente como está no console.

Ao executar este programa, o Java localiza o método main, executa a instrução println e exibe no console (terminal).



##  Diferenças entre IDEs na Programação

As IDEs (Ambientes de Desenvolvimento Integrado) são ferramentas essenciais para programadores, pois reúnem editor de código, compilador, depurador e outros recursos em um único ambiente. Cada IDE possui características próprias que influenciam na produtividade e no tipo de projeto desenvolvido.


##  Principais IDEs

###  Eclipse
- IDE tradicional muito utilizada para Java  
- Código aberto e altamente personalizável (plugins)  
- Forte em projetos grandes e corporativos  
- Interface menos intuitiva para iniciantes  


###  Visual Studio Code (VS Code)
- Editor leve que pode se tornar uma IDE completa  
- Suporte a várias linguagens (Python, JavaScript, C++, etc.)  
- Interface moderna e fácil de usar  
- Grande variedade de extensões  
- Excelente desempenho  


###  IntelliJ IDEA
- IDE inteligente com foco em produtividade  
- Forte suporte para Java e outras linguagens  
- Autocompletar avançado e análise de código  
- Interface moderna  
- Versão paga com mais recursos  


###  NetBeans
- IDE completa e pronta para uso  
- Menos dependente de plugins  
- Boa para desenvolvimento em Java  
- Interface simples e funcional  



###  Conclusão

Cada IDE atende a diferentes necessidades:

- **VS Code** → leve, versátil e ideal para vários tipos de projeto  
- **IntelliJ IDEA** → mais completo e produtivo, principalmente para Java  
- **Eclipse** → robusto e muito usado em empresas  
- **NetBeans** → simples e eficiente para iniciantes  
