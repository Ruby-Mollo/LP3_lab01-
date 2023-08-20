
public class ejemploJava {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		do {
			vida ++;
			System.out.println("Vida: "+ vida + "\t¿Cual es el numero secreto?");
			rp = sc.nextInt();
			if (rp == 1234)
				fl = true;
		}while(vida < 3 && !fl);
		if (fl == true)
			System.out.println("Adivinaste!!! ");
		else
			System.out.println("ups, perdiste...");
	}

}
