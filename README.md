//A Java program to initialize the dialogue box for calculating the area of a rectangle//

import javax.swing.*; //Needed for dialogue box

import java.util.*;

public class Practice {

    public static void main(String[] args)
    {
        //import and use Scanner function for user input
        Scanner sc = new Scanner(System.in); 
        
        //initialize a string
        String input; 
        
        //initialize the input dialogue for length
        input = JOptionPane.showInputDialog("Enter Length");
        
        //read the string and covert to innteger
        int length = Integer.parseInt(input);
        
        //input dialogue for width
        input = JOptionPane.showInputDialog("Enter Width");
        
        //read width from string
        int width = Integer.parseInt(input);
        
        //calculation of area
        int area = length*width;
        
        //show output in message box
        JOptionPane.showMessageDialog(null,"Area of rectangle is " + area);
    }
}
