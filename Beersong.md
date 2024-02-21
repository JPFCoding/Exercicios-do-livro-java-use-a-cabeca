public class Beersong{
	public static void main(String[] args){
		int BeerNum = 99;
		String word = "bottles";

		while (BeerNum > 0) {
		
		 	if (BeerNum == 1) {
				word = "bottle" ; //no singular, como em UMA garrafa.
			}
			System.out.println (BeerNum + " " + word + " of beer on the wall");
			System.out.println (BeerNum + " " + word + " of beer.");
			System.out.println ("take one down");
			System.out.println ("pass it aroud");
			BeerNum = BeerNum - 1;
			
			if (BeerNum > 0) {
				System.out.println (BeerNum + " " + word + "of beer on the wall");
			} else {
          			System.out.println ("No more bottles of beer on the wall");
			}
		}//fim do while
	}//fim do metodo main
}//fim da classe