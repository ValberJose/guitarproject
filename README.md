# guitarproject
Guitarra do Slash
public class Guitarra {

    private String numeroSerie, fabricante, modelo, tipo, madeira;
    private double preco;

    // Criação da classe guitarra
    public Guitarra(String numeroSerie, String fabricante, String modelo, String tipo, String madeira, int preco, int par1) {
        this.numeroSerie = numeroSerie;
        this.fabricante = fabricante;
        this.modelo = modelo;
        this.tipo = tipo;
        this.madeira = madeira;
        this.preco = preco;
    }

    public String getNumeroSerie() {
        return numeroSerie;
    }

    public void setNumeroSerie(String numeroSerie) {
        this.numeroSerie = numeroSerie;
    }

    public String getFabricante() {
        return fabricante;
    }

    public void setFabricante(String fabricante) {
        this.fabricante = fabricante;
    }

    public String getModelo() {
        return modelo;
    }

    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    public String getTipo() {
        return tipo;
    }

    public void setTipo(String tipo) {
        this.tipo = tipo;
    }

    public String getMadeira() {
        return madeira;
    }

    public void setMadeira(String madeira) {
        this.madeira = madeira;
    }

    public double getPreco() {
        return preco;
    }

    public void setPreco(double preco) {
        this.preco = preco;
    }

    public static void main(String[] args) {
        Guitarra minhaGuitarra = new Guitarra("0724758", "valber", "Gibson Les Paul", "elétrica", "mogno anaconda", 49513,24);
        System.out.println(minhaGuitarra.getNumeroSerie());
        System.out.println(minhaGuitarra.getModelo());
        System.out.println(minhaGuitarra.getMadeira());
        System.out.println(minhaGuitarra.getPreco());
        System.out.println(minhaGuitarra.getTipo());
    }
}
