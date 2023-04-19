# Multiplication-Table
# Create a Multiplication Table:

--------------------------------------------------------------------------
package com.in28.Firstjavaproject;

public class MultiplicationTable {
	void print() {
		print(5, 1, 10);
	}

	void print(int table) {
		print(table, 1, 10);
	}

	void print(int table, int from, int to) {
		for(int i=from; i <= to; i++) {
			System.out.printf("%d * %d = %d", table, i, table * i).println();
		}
	}
}



-------------------------------------------------------------------------------
package com.in28.Firstjavaproject;

public class MultiplicationTableRunner {

	public static void main(String[] args) {
		MultiplicationTable table = new MultiplicationTable();
		table.print();
//		table.print(6);
//		table.print(6, 11, 20);
	}

}
