
// Definición de la clase Persona
public class Persona {
  // Atributos o datos de la clase
  String nombre;
  int edad;
  String genero;

  // Método o comportamiento de la clase
  void imprimirDatos() {
    System.out.println("Nombre: " + nombre);
    System.out.println("Edad: " + edad);
    System.out.println("Género: " + genero);
  }
}

// Clase principal
public class EVA1_1_CLASES_OBJETOS {
  public static void main(String[] args) {
    // Declaración de una variable de tipo Persona
    Persona persol;

    // Instanciación de la clase Persona (creación de un objeto)
    persol = new Persona();

    // Asignación de valores a los atributos del objeto
    persol.nombre = "Juan Pérez";
    persol.edad = 10;
    persol.genero = "H";

    // Llamada al método imprimirDatos() del objeto
    persol.imprimirDatos();
  }
}
```
