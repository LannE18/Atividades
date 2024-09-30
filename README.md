```java
package aula17;

public class Carro17 {
	private String modelo;
	private int ano;
	private int torque;
	
	public String getModelo() {
		return modelo;
	}
	public void setModelo(String modelo) {
		this.modelo = modelo;
	}
	public int getAno() {
			return ano;
	}
	public void setAno(int ano) {
			this.ano = ano;

	}
	public int getTorque() {
		return torque;
	}
	public void setTorque(int torque) {
		this.torque = torque;
	}

}

package aula17;

import java.util.Scanner;

public class Modelos {

	public static void main(String[] args) {
		Scanner ler = new Scanner(System.in);
		Carro17 automovel = new Carro17();
		
		System.out.println("digite o Modelo do carro:");
		String Modelocarro = ler.nextLine();
		System.out.println("digite o ano de lançamento:");
		int anocarro = ler.nextInt();
		System.out.println("digite o torque do carro:");
		int torquecarro = ler.nextInt();
		
		automovel.setModelo(Modelocarro);
		automovel.setAno(anocarro);
		automovel.setTorque(torquecarro);
		
		System.out.println("o nome do carro é: "+automovel.getModelo());
		System.out.println(automovel.getAno());
		System.out.println(automovel.getTorque());
	}

}
```
```
