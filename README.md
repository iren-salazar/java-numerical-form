# java-numerical-form
using JOptionPane and if else or switch case


package oop;

import javax.swing.JOptionPane;

public class Numericalform {
  		public static void main(String args[]) throws Exception {
			
			
			int month,day, year;
			String choice;
			
			
			month = Integer.parseInt(JOptionPane.showInputDialog(null,"Enter month:"));
			day = Integer.parseInt(JOptionPane.showInputDialog(null,"Enter day:"));
			year = Integer.parseInt(JOptionPane.showInputDialog(null,"Enter year:"));
			
			switch (month) {
			
			case 1:
				JOptionPane.showMessageDialog(null, "January " + day + ", " + year);
				break;
			case 2:
				JOptionPane.showMessageDialog(null, "February " + day + ", " + year);
				break;
			case 3:
				JOptionPane.showMessageDialog(null, "March " + day + ", " + year);
				break;
			case 4:
				JOptionPane.showMessageDialog(null, "April " + day + ", " + year);
				break;
			case 5:
				JOptionPane.showMessageDialog(null, "May " + day + ", " + year);
				break;
			case 6:
				JOptionPane.showMessageDialog(null, "June " + day + ", " + year);
				break;
			case 7:
				JOptionPane.showMessageDialog(null, "July " + day + ", " + year);
				break;
			case 8:
				JOptionPane.showMessageDialog(null, "August " + day + ", " + year);
				break;
			case 9:
				JOptionPane.showMessageDialog(null, "September " + day + ",  " + year);
				break;
			case 10:
				JOptionPane.showMessageDialog(null, "October " + day + ", " + year);
				break;
			case 11:
				JOptionPane.showMessageDialog(null, "November " + day + ", " + year);
				break;
			case 12:
				JOptionPane.showMessageDialog(null, "December " + day + ", " + year);
				break;
			default:
				JOptionPane.showMessageDialog(null, "Invalid date!, Please try again! ");
				break;
			}

  		}	
  			
 }
