# aula-1-de-java

package br.com.fiap.modelo;

public class cliente {

	private String nome;
	private int idade;
	private double peso;
	
	// setters (Entrada)
	public void setNome(String nome) {
		this.nome = nome;	
	} 
	
	public void setIdade (int idade) {
		this.idade = idade;
	}
	public void setPeso(double peso) {
		this.peso = peso; 
	}
	
	//Getters (Saída)
	public String getNome() {
		return nome;
	}
	
	public int getIdade() {
		return idade;
	}
	
	public double getPeso() {
		return peso;
	}
	
	
	
	
}
