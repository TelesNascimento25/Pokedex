# Pokedex

Scanner in = new Scanner(System.in);
		
		System.out.println("Digite o seu texto");
		String texto = in.nextLine();
		
		char primeiraLetra = texto.charAt(0);
		char ultimaLetra = texto.charAt(texto.length()-1);
		
		System.out.println("A primeira letra do texto e: " + primeiraLetra);
		System.out.println("A ultima letra do texto e: " + ultimaLetra);
		System.out.println("O texto que voce digitou tem "+ texto.length() + " letras ");
		
