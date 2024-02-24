public class Beersong{
	public static void main(String[] args){
		int BeerNum = 99;
		String word = "bottles";

		while (BeerNum > 0) {
		
		 	if (BeerNum == 1) {
				word = "bottle" ; //no singular, como em UMA garrafa.
			}
			System.out.println (BeerNum + " " + word + " of beer on the wall, " + BeerNum + " " + word + "off beer, ");
			System.out.println("take one down and pass it around.");
			BeerNum = BeerNum - 1;
			
			if (BeerNum == 0) {
				System.out.println ("No more bottles of beer on the wall");
				System.out.println ("   Codigo revisto por Joao Paulo Ferreira <-- meu verdadeiro nome, do livro Java Use a cabeça.");
			}
		}//fim do while
	}//fim do metodo main
}//fim da classe