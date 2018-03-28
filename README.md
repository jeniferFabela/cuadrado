# cuadrado
clase cuadrado calcula area y perimetro 
package cuadrado;
import javax.swing.*;
	public class cuadrado extends Menu {
    public static void main(String[] args) {
    	JOptionPane.showMessageDialog(null,"CUADRADO");
    	//System.out.println("dame el tamaño del lado de tu cuadrado");
    	String numero=JOptionPane.showInputDialog("dame el tamaño del lado de tu cuadrado");
    	int lado=Integer.parseInt(numero);
    	int perimetro=lado*4;
    	System.out.println("EL PERIMETRO ES "+perimetro);
        int area=lado*lado;
        System.out.println("EL AREA ES:"+area);
    }
 }
