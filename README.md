public class Main {

	public static void main(String[] args) {
      String nombres[] = {"Shi Xuan", "n/a", "n/a"};
      int edades[] = {20, 0, 0};

      for (int i = 0; i < nombres.length; i++) {
          System.out.printf("Persona nº %d:%nNombre: %s%nEdad: %d%n", i +1, nombres[i], edades[i]);
      }
	}

}
