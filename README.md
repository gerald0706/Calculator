# Calculator
My first calculator
/**
	* @bantilan	 ITCC11 B
	* data oct 5 2020
	*/

import javax.swing.*;
import java.awt.*;

class Calculator {

	private JFrame frame;
	private	JPanel mainPanel;
	private JButton one,two,three,four,five,six,seven,eight,nine,zero,Plus,Subtract,Multiply,Divide,Point,Equals,Clear;
	private JTextField t1;


	
	/** constructor **/
	
	public Calculator() {
	

	frame = new JFrame();
	frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	frame.setBounds(100,100,250,385);
	
	
	t1 = new JTextField();
	t1.setBounds(10,11,215,32);
	frame.getContentPane().add(t1);
	t1.setColumns(10);
	
	
	
	Font f = new Font("Tahoma",Font.BOLD,14);
	
	
	// My First Row 
	

	one = new JButton("1");
	one.setFont(f);
	one.setBounds(10,54,45,45);
	frame.getContentPane().add(one);
	
	two = new JButton("2");
	two.setFont(f);
	two.setBounds(66,54,45,45);
	frame.getContentPane().add(two);
	
	three = new JButton("3");
	three.setFont(f);
	three.setBounds(122,54,45,45);
	frame.getContentPane().add(three);
	
	Plus = new JButton("+");
	Plus.setFont(f);
	Plus.setBounds(178,54,45,45);
	Plus.setBackground(Color.PINK);
	frame.getContentPane().add(Plus);
	
	
	// My Second Row 
	four = new JButton("4");
	four.setFont(f);
	four.setBounds(10,110,45,45);
	frame.getContentPane().add(four);
	
	five = new JButton("5");
	five.setFont(f);
	five.setBounds(66,110,45,45);
	frame.getContentPane().add(five);
	
	six = new JButton("6");
	six.setFont(f);
	six.setBounds(122,110,45,45);
	frame.getContentPane().add(six);
	
	Subtract = new JButton("-");
	Subtract.setFont(f);
	Subtract.setBounds(178,110,45,45);
	Subtract.setBackground(Color.PINK);
	frame.getContentPane().add(Subtract);
	
	// My Third Row 
	seven = new JButton("7");
	seven.setFont(f);
	seven.setBounds(10,166,45,45);
	frame.getContentPane().add(seven);
	
	eight = new JButton("8");
	eight.setFont(f);
	eight.setBounds(66,166,45,45);
	frame.getContentPane().add(eight);
	
	nine = new JButton("9");
	nine.setFont(f);
	nine.setBounds(122,166,45,45);
	frame.getContentPane().add(nine);
	
	Multiply = new JButton("*");
	Multiply.setFont(f);
	Multiply.setBounds(178,166,45,45);
	Multiply.setBackground(Color.PINK);
	frame.getContentPane().add(Multiply);
	
	
	
	// My Fourth Row 
	Point = new JButton(".");
	Point.setFont(f);
	Point.setBounds(10,222,45,45);
	frame.getContentPane().add(Point);
	
	zero = new JButton("0");
	zero.setFont(f);
	zero.setBounds(66,222,45,45);
	frame.getContentPane().add(zero);
	
	Equals = new JButton("=");
	Equals.setFont(f);
	Equals.setBounds(122,222,45,45);
	Equals.setBackground(Color.RED);
	frame.getContentPane().add(Equals);
	
	Divide = new JButton("/");
	Divide.setFont(f);
	Divide.setBounds(178,222,45,45);
	Divide.setBackground(Color.PINK);
	frame.getContentPane().add(Divide);
	
	
	
	// My Fifth Row 

	
	Clear = new JButton("Clear");
	Clear.setFont(f);
	Clear.setBounds(66,278,100,45);
	Clear.setBackground(Color.GRAY);
	frame.getContentPane().add(Clear);
	
	
	
	
	
	mainPanel = new JPanel();
	
	t1 = new JTextField();
	one = new JButton("1");
	two = new JButton("2");
	three = new JButton("3");
	four = new JButton("4");
	five = new JButton("5");
	six = new JButton("6");
	seven = new JButton("7");
	eight = new JButton("8");
	nine = new JButton("9");
	zero = new JButton("0");
	Plus = new JButton("+");
	Subtract = new JButton("-");
	Divide = new JButton("/");
	Multiply = new JButton("*");
	Point = new JButton(".");
	Equals = new JButton("=");
	Clear = new JButton("Clear");
	
	
	
	
	
	

	
	frame.add(mainPanel);
	
	}
	
	/**
	*show the program
	*/
	
	public void show() {
		frame.setVisible(true);
		
		}
		public static void main(String[] args) {
			Calculator c = new Calculator();
			c.show();
		}
	}	
	
