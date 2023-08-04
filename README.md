### Hi, I´m Laura 👋👩‍💻

public class Persona {
    private String carrera;
    private String proyectos;

    public Persona(String carrera, String proyectos) {
        this.carrera = carrera;
        this.proyectos = proyectos;
    }

    public void presentarse() {
        System.out.println("¡Hola a todos!");
        System.out.println("Soy estudiante de Ingeniería en Sistemas.");
        System.out.println("Estoy emocionada por los futuros proyectos de programación.");
        System.out.println("¡Feliz de presentarme con ustedes!");
    }

    public static void main(String[] args) {
        Persona persona = new Persona("Ingeniería en Sistemas", "Desarrollo de una aplicación web");
        persona.presentarse();
    }
}
