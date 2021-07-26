package Calculadora;
import javax.swing.JOptionPane;

public class Calculadora {
    public static void main(String[] args) {
        float num_1, num_2, suma=0, resta=0, multiplicacion=0, division=0;
        String mensaje=("Programa que realiza las 4 operaciones basicas");
        String mensaje2=("Ingrese 2 numeros");
        
JOptionPane.showMessageDialog(null,mensaje);
JOptionPane.showMessageDialog(null,mensaje2);
num_1=Float.parseFloat(JOptionPane.showInputDialog("Ingrese el primer numero"));
num_2=Float.parseFloat(JOptionPane.showInputDialog("Ingrese el segundo numero"));

suma = num_1+num_2;
resta = num_1-num_2;
multiplicacion = num_1*num_2;
division = num_1/num_2;

JOptionPane.showMessageDialog(null,"Suma: " + suma + "\nResta: " + resta + "\nMultiplicacion: " + multiplicacion + "\nDivision: " + division);
    }
}
