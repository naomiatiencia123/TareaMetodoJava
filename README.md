public class PromedioNotas {

    // Método con dos parámetros
    public static double calcularPromedio(double nota1, double nota2) {
        double promedio = (nota1 + nota2) / 2;
        return promedio;
    }

    public static void main(String[] args) {

        double nota1 = 8;
        double nota2 = 6;

        double resultado = calcularPromedio(nota1, nota2);

        System.out.println("El promedio es: " + resultado);
    }
}
