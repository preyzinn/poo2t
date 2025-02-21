import java.util.Scanner;
import java.util.Random;
public class Main
{
	public static void main(String[] args) {
		Integer jogador;
		Integer computador;
		Integer vjogador = 0;
		Integer vcomputador = 0;
		Integer empates = 0;
		Scanner scanner = new Scanner(System.in);
		Random rand = new Random();
		
		while (true){
		    //apresentar o menu
		    System.out.println("\n===MENU===\n"+"1 - Pedra\n2 - Papel\n3 - Tesoura\n");
		    
		    // msg para o Usario entrar com a opcao 
		    System.out.println("Sua opção: ");
		    
		    // ler a opcao 
		    jogador = scanner.nextInt();
		    
		    //sortear a opcao do compuador 
		    computador = rand.nextInt(3) + 1;
		    
		    //verificar quem ganhou ou se empatou
		    if(jogador == computador){
		        System.out.println("Empatou\n");
		        empates++;
		    }
		    
		    else if(jogador == 1 && computador == 3){
		        System.out.println("você ganhou\n");
		        vjogador++;
		    }
		    
		    else if(jogador == 2 && computador == 1){
		        System.out.println("você ganhou\n");
		        vjogador ++;
		    }
		    
		    else if(jogador == 3 && computador == 2){
		        System.out.println("você ganhou\n");
		        vjogador++;
		    }
		    else{
		        System.out.println("Você perdeu\n");
		        vcomputador++;
		    }
		   
		    
		    
		    //apresentar o placar
		    System.out.println("====================" );
		    System.out.println("\nVitorias:" + vjogador );
		    System.out.println("\nEmpates:" + empates);
		    System.out.println("\nDerrotas:" + vcomputador);
		}
		
		
	}
}
