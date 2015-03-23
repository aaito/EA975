import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Calculate {
        public static void main(String[] args) {
               
                int width = 0;
                int length = 0;
                int perimeter = 0;
                       
                try
                {
                        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
                        
                        //recebe o comprimento do retangulo
                        System.out.println("Please enter length of a rectangle");
                        length = Integer.parseInt(br.readLine());
                        
                        //recebe a largura do retangulo
                        System.out.println("Please enter width of a rectangle");
                        width = Integer.parseInt(br.readLine());
                }
                
                //trata a excecao de formato de numero nao correspondente ao esperado
                catch(NumberFormatException ne)
                {
                        System.out.println("Invalid value" + ne);
                        System.exit(0);
                }
                //trata a excecao de erro no formato da entrada
                catch(IOException ioe)
                {
                        System.out.println("IO Error :" + ioe);
                        System.exit(0);
                }
                
                //calcula o perimetro
                perimeter=2*length + 2*width;
                //mostra o valor para o usuario
                System.out.println("Perimeter of a rectangle is " + perimeter);
        }
}