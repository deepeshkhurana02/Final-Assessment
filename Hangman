package w4d2StudyHall;

import java.util.Scanner;
import java.util.Arrays;
import java.io.InputStream;
import java.io.OutputStream;
import java.io.PrintStream;
import java.util.Iterator;
import java.util.Random;

public class W4D2StudyHallExercise {
	/*
	 * <p> Title: Hangman Project. </p>
	 *
	 *
     *
     * Permission is hereby granted, free of charge, to any person obtaining a copy
     * of this software and associated documentation files (the "Software"), to deal
     * in the Software without restriction, including without limitation the rights
     * to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
     * copies of the Software, and to permit persons to whom the Software is
     * furnished to do so, subject to the following conditions:
     * The above copyright notice and this permission notice shall be included
     * in all copies or substantial portions of the Software.

	 * <p> Copyright:  Deepesh Khurana Â© 2019 </p>
	 *
	 * @author Deepesh Dhurana
	 *
	 *
	 */
	private static String usersName;
	private static String inputFromUser;
	private static Scanner keyboard;
	public static void main(String args[]) {


	System.out.println("Welcome");
	System.out.println("Please enter your name followed by a return");
	keyboard = new Scanner(System.in);
	usersName=keyboard.next();
	System.out.println( "Welcome " + usersName + ", to Hangman's Game!" );

while (true) {
	System.out.println(usersName +", please enter a command letter followed by a return!");
	System.out.println( "p -> Play the game +\ns--> View statistics + \nq--> Quit");
	inputFromUser = keyboard.next();
	inputFromUser = inputFromUser.toUpperCase();

	      if (inputFromUser.equals("P")) {
	        System.out.println("Play the game command recognized.");

	     } else if (inputFromUser.equals("S")) {
	         System.out.println("View the statistics command recognized.");

	     } else if (inputFromUser.equals("Q")) {
	         System.out.println("Quit the game command recognized.");
	         System.out.println("Thanks for playing," + usersName );
	         System.exit(1);

	     } else {
	         System.out.println("*** Error ***");
	         System.out.println("Invalid menu item entered. It must be p, s, or q!");
	         System.out.println("The input found was:" +  inputFromUser);

	      }
	}

	}
	}
