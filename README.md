# tablas-de-multiplicar-en-JAVA
tablas de multiplicar en java 
es el codigo para las tablas de multiplicar en modo JOptionpanel y al final muestra modo consola.


Scanner entrada = new Scanner(System.in);
		
		int n;
		
		n=Integer.parseInt(JOptionPane.showInputDialog("introduce el numero"));
		
		for (int i = 1; i <=10;i++) {
		System.out.println(n+"*"+i+"="+n*i);
