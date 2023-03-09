import java.util.Scanner;
import java.time.LocalDate;

public class Erapaiva {

	public static void main(String[] args) {
		LocalDate pvm;
		String pwm_string;
		Scanner input = new Scanner(System.in);

		System.out.print("Anna laskun päivämäärä (vvvv-kk-pp): ");
		String pvm_string = input.nextLine();

		try {
			pvm = LocalDate.parse(pvm_string);
			LocalDate erapaiva = pvm.plusDays(14);
			System.out.println("Eräpäivä on " + erapaiva);
		} catch (Exception err) {
			System.out.println("Päivämäärä on virheellinen");
		}
	}

}
