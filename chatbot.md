
import java.util.Scanner;



public class App {
      /**
     * @param args
     * @throws Exception
     */
    public static void main(String[] args) throws Exception {

        Scanner apresentação= new Scanner(System.in);
        Scanner resposta= new Scanner(System.in);
        Scanner idade= new Scanner(System.in);
        Scanner duvida= new Scanner(System.in);
        var study= new Scanner(System.in);
        Scanner college= new Scanner(System.in);



        System.out.println(" Oi, como vai ?");
         String nome = apresentação.nextLine();
         System.out.println("QUAL SEU NOME?");
         String respondeu= resposta.nextLine();
         System.out.println("QUAL SUA IDADE ?");
         int numbero= idade.nextInt();
         System.out.println( "Você tem "+numbero );
         System.out.println("anos de idade? 1-SIM  2- NÃO");
         int escolha= duvida.nextInt();
        

         
           if (escolha==1){
                System.out.println("vamos continuar ");
            
             }else{
                System.out.println(" confirma sua idade de novo"   );
                System.out.println("QUAL SUA IDADE ?");
             int number= idade.nextInt();
             System.out.println( "Você tem "+number );
             System.out.println("anos de idade? 1-SIM  2- NÃO");
             int confirma= duvida.nextInt();
             System.out.println("vamos continuar agora");
             }
        
        
         System.out.println(" Qual é o seu grau de ensino?");
         System.out.println("1 - fundamental I 2- MÉDIO 3-SUPERIOR");
          int estudo= study.nextInt();
          
          System.out.println(" Onde você estudou?");
           String location= college.nextLine();
           



          
         
    
         
    } 
} 
             
          

         
          
        
    
          
            
            
          


    


  

        
       
        
       
         
        

        
     


    

    
