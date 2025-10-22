# Pagina web de clases online
Aquí hago una documentación de mi pagina web, que se encarga de hacer unos cursos online.
# Nombre del proyecto
Cursos online(Julian)
## 1. Fundamentos del sistema
-Mi empresa se va a encargar de hacer una página web de estudio online

-Mi empresa va a ser de aplicación cerrada mediante suscripciones mensuales, va a ser de software cerrado, comercial.

-Mi empresa va a ser con suscripciones mensuales ya que habla que pagarle a los profesores que hay en la empresa y los demás desarrolladores que se van a encargar de que pongas mas la incrementación de nuevas materias y el mantenimiento y ampliación de la página web.

-Los requisitos mínimos que voy a necesitar van a ser la aplicación donde se permita pagando mensualmente acceder a las clases con un limitante de dependiendo del dinero pueda acceder a ciertas clases o otras, pudiendo acceder a extras mediante otra paga y evidentemente crear los usuarios, las clases y el mantenimiento de las clases cada x tiempo.

## 2. Análisis y especificación de requisitiso
Requisitos funcionales y no funcionales de mi empresa:
  a) Requisitos no funcionales de mi empresa:
  
    i) La empresa debe de estar activa el máximo de tiempo posible (ya que es una página web que esté disponible y no se           caigan los servidores donde está registrada la página web).
    
    ii) La página web debe de ser activa para todos los usuarios tanto para móvil como para pc y notebook.
    
    iii) Las contraseñas que sean seguras y disponibilidad de autentificador de dos pasos.
    
b) Requisitos funcionales de mi empresa:

    i) El usuario podrá crearse una cuenta.
    
    ii) El usuario podrá modificar su perfil a su gusto.
    
    iii) El usuario podrá modificar su búsqueda a su gusto (para que le salgan solo las clases que le interesen a él en la           misma búsqueda).

## 3. Diseño
Añadir aquí lo relacionado con el diseño y técnicas descriptivas que fuimos creando

[Técnicas descriptivas.pdf](https://github.com/user-attachments/files/22946476/Tecnicas.descriptivas.pdf)

Pseudocódigo: Quiero que mi usuarios puedan iniciar sesion se metan en una clase y puedan elegir o gratis o de pago y despues de hacer una clase puedan volver o no coger otra clase.

## 4. Implementación
Añade aquí aunque no tenga que ver con el proyecto, los ejercicios donde tuviste que corregir el código "feo"

    Ejercicio1:

/**
 * Representa una clase hola 
 * @author Julio
 *@version 1.0
 */
public class hola{
	
	/**
	 * Suma un plus a hola para comprobar una condicion
	 * @param void main
	 */
	 
	public static void main(String args[]){
	
		System.out.println("Hola mundo");
		
		if(true){
		
			System.out.println("Condición verdadera");
			
		}
		else{ //E metido una tabulacion y un salto de linea a el mensaje por pantalla de el else
		
			System.out.println("Condición falsa");
			
		}
	}
}




	Comentario del codigo:
Lo que e cambiedo del codigo es que el codigo no e cambiado nada
E tabulado plimero entre la clase hola y e puesto el cierre de la llave en la punta abajo para que quede la clase bien tabulada
E metido una tabulacion a el voic main y e dejado la llave de cierre en la punta abajo bien tabulado 
E metido salto de lineas entre los if y el else para que se vea claro.
E metido una tabulacion y un salto de linea al plincipio y al final de el if y el else y su tabulacion correspondiente para que se quede claro


          Ejercicio2:


/**
 * Representa una clase area 
 * Representa el area de un circulo
 * @author Julio
 *@version 1.0
 */

public class area{
	
	/**
	 * Calcula el area de un circulo
	 * @param void main
	 */
	 
	public static void main(String[] args){
		
		/*
		*Radio del circulo
		*Numero pi
		*Area del circulo
		*/
		
		double r, pi, area;
		
		r=5;
		pi=3.14159;
		area=pi*r*r;
		
		System.out.println("el area es "+area);
	}
}

	Comentario del codigo:
E metido una tabulacion a todo el contenido de area y su comilla de cierre lo e puesto en una linea debajo sin tabulacion ya que es de la clase raiz
Le e metido una tabulacion al contenido de  static void y su comilla de cierre lo e puesto un abajo para que se vea bien donde esta el cierre
E creado los double aparte, en un linea antes para que se vea claro las funciones donde se crean y sea un poco mas legible el codigo
Meti un salto de linea para que los double y las ecuaciones se vean separado

Codigo original:

public class area{
public static void main(String[] args){
double r=5;
double Pi=3.14159;
double area=Pi*r*r;
System.out.println("el area es "+area);}}
	Codigo original:

public class hola{
public static void main(String args[]){
System.out.println("Hola mundo");
if(true){
System.out.println("Condición verdadera");}
else{
System.out.println("Condición falsa");}}}


    Ejercicio3:

/**
 * Representa una clase area 
 * Realiza operaciones matematicas
 * @author Julio
 *@version 1.0
 */

public class OperacionesMatematicas {

	/*Suma dos numero*/
	
	public static int SumarNumeros(int NumeroUno, int NumeroDos){
	
		return NumeroUno+NumeroDos;
		
	}
	
	/* Resta dos numeros*/
	
	public static int Restar(int A, int B){
	
		return A-B;
		
	}
	
	/*Multiplica dos numeros*/
	
	public static int Multiplicacion(int NUM1,int num2){
	
	return NUM1*num2;
	
	}
	
	/*Divide dos numeros enteros*/
	
	public static int DivisionDeEnteros(int dividendo, int divisor){
	
	return dividendo/divisor;
	
	}
	
	/*Envia mensajes por pantalla*/
	
	public static void main(String[] args){
	
		System.out.println(SumarNumeros(3,4));
		System.out.println(RESTAR(5,2));
		System.out.println(multiplicacion(2,6));
		System.out.println(DivisionDeEnteros(8,2));
	}
}

	Comentario del codigo:
Tabulo la clase OperacionesMatematicas	y sus respetillas comillas las pongo abajo
Tabulo Sumar Numeros y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Le cambio el nombre a RESTAR por Restar para que sea legible con los demas int.
Tabulo RESTAR y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Le cambio el nombre a multiplicacion por Multiplicacion para que sea legible con los demas int.
Tabulo Multiplicacion y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Tabulo DivisionDeEnteros y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Tabulo stactic void y meto un salto de linea al principio de la funcion



	Codigo original:

public class OperacionesMatematicas {
public static int SumarNumeros(int NumeroUno, int NumeroDos){
return NumeroUno+NumeroDos;}
public static int RESTAR(int A, int B){
return A-B;}
public static int multiplicacion(int NUM1,int num2){
return NUM1*num2;}
public static int DivisionDeEnteros(int dividendo, int divisor){
return dividendo/divisor;}
public static void main(String[] args){
System.out.println(SumarNumeros(3,4));
System.out.println(RESTAR(5,2));
System.out.println(multiplicacion(2,6));
System.out.println(DivisionDeEnteros(8,2));
}}

    Ejercicio4:
  
/**
 * Representa una clase area 
 * Realiza operaciones matematicas y los envia por pantalla
 * @author Julio
 *@version 1.0
 */

public class Calculadora {

	/*Suma dos numero*/

	public int sumar(int x, int y){
	
		return x+y;
		
	}
	
	/*Resta dos numero*/
	
	public int restar(int x, int y){
	
		return x-y;
	
	}
	
	/*Multiplica dos numero*/
	
	public int multiplicar(int x, int y){
	
		return x*y;
	
	}
	
	/*Divide dos numero*/
	
	public int dividir(int x, int y){
	
	return x/y;
	
	}
	
	/*Envia los resultudos por pantalla*/
	
	public static void main(String[] args){
	
		Calculadora c=new Calculadora();System.out.println("resultado:"+c.sumar(5,3));
	}
}


	Comentario del codigo:
Elimino los comentarios ya que estan mal comentados y no sirven ya que no tienen sentido	
Tabulo la clase Calculadora y le meto salto de linea al principio de la clase y le cambio sus comillas al final
Tabulo sumar y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Tabulo restar y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte
Tabulo multiplicar y meto un salto de linea entre el principio y el fin y pongo su comilla de cierra en una linea aparte


	Codigo original:
// Esta clase hace cosas
public class Calculadora {
// Este método suma dos números
public int sumar(int x, int y){
return x+y;}
// Este método resta dos números
public int restar(int x, int y){
return x-y;}
// Este método multiplica dos números
public int multiplicar(int x, int y){
return x*y;}
// Este método divide dos números
public int dividir(int x, int y){
return x/y;}
public static void main(String[] args){
Calculadora c=new Calculadora();System.out.println("resultado:"+c.sumar(5,3));}}

  Ejercicio5:

/**
 * Representa una clase alumno
 * Representa una clase curso
 * gestionar una lista de alumnos
 * @author Julio
 *@version 1.0
 */

public class alumno{

	private String NOMBRE;
	private int edad;
	private double NotaFinal;
		
			/* Recoge datos de la clase alumno*/
		
		public alumno(String n,int e,double nf){NOMBRE=n;edad=e;NotaFinal=nf;}
	
			public void Mostrardatos(){System.out.println("Alumno: "+NOMBRE+", Edad:"+edad+", Nota Final:"+NotaFinal);}
			
			/*Hace una cptura de datos sobre si esta aprobado o no*/
			
			public boolean aprobado(){
			
			if(NotaFinal>=5.0){
			
			return true;
			
			}else{return false;}
			}
			
			/*Hace un mensaje dependiendo de tu nota*/
			
			public void mensajeFinal(){if(aprobado()){
			
			System.out.println("felicidades "+NOMBRE+" aprobaste!");
			
			}else{
			
			System.out.println("Lo siento "+NOMBRE+" no aprobaste");
		}
}

class curso{

	private String NOMBRE_CURSO;
	private alumno[] lista;
	
	/*Recoge los datos de curso*/
	
	public curso(String n, alumno[] l){NOMBRE_CURSO=n;lista=l;}
	
		public void mostrarTodo(){
			
			System.out.println("curso: "+NOMBRE_CURSO);for(alumno a:lista){
			
				a.MostrarDatos();
				a.MensajeFinal();
			}
		}
		
	/*Añade contenido a la clase alumnos*/
		
	public static void main(String[] args){
			
		alumno a1=new alumno("ana",18,6.5);
		alumno a2=new alumno("PEDRO",19,4.3);
		alumno a3=new alumno("Lucia",17,8.7);
		alumno[] lista={a1,a2,a3};
		curso c1=new curso("programacion",lista);
		c1.mostrarTodo();
	}
}




	Comentario del codigo:
Elimino el primer comentario ya que no especifica nada
Tabulo la clase alumno y todo su contenido y pongo la comilla de cierre 
En la linea de (private int edad;private double NotaFinal;) meto un salto de linea en el ;
Tabulo correstamente la clase publica alumno metiendo sus if y sus elses y sus saltos de lineas correstos
Y poniendo sus cierres de comillas en sus lugares correspondientes
En la clase curso meto un salto de linea al principio de la clase
Separo con saltos de linea entre los private y los public
Tabulo curso y sus comillas de cierre los pongo abajo de curso bien tabulado
Tabulo mostrarTodo y pongo sus comillas al final
Corrigo y pongo en dos lineas el mostrar datos y mensajeFinal
Y le cambio el nombre por uno mas legible
Separa y tabulo el viod man 



	Codigo original:
//clase de alumno
public class alumno{
private String NOMBRE;
private int edad;private double NotaFinal;
public alumno(String n,int e,double nf){NOMBRE=n;edad=e;NotaFinal=nf;}
public void Mostrardatos(){System.out.println("Alumno: "+NOMBRE+", Edad:"+edad+", Nota Final:"+NotaFinal);}
public boolean aprobado(){if(NotaFinal>=5.0){return true;}else{return false;}}
public void mensajeFinal(){if(aprobado()){System.out.println("felicidades "+NOMBRE+" aprobaste!");}
else{System.out.println("Lo siento "+NOMBRE+" no aprobaste");}}
}

class curso{
private String NOMBRE_CURSO;
private alumno[] lista;
public curso(String n, alumno[] l){NOMBRE_CURSO=n;lista=l;}
public void mostrarTodo(){System.out.println("curso: "+NOMBRE_CURSO);for(alumno a:lista){a.Mostrardatos();a.mensajeFinal();}}
public static void main(String[] args){
alumno a1=new alumno("ana",18,6.5);
alumno a2=new alumno("PEDRO",19,4.3);
alumno a3=new alumno("Lucia",17,8.7);
alumno[] lista={a1,a2,a3};
curso c1=new curso("programacion",lista);
c1.mostrarTodo();}}

## 5. Plan de pruebas del sistema

Requisito funcional: El sistema debe permitir a un nuevo usuario crear una cuenta,
validando que el correo no exista y enviando un correo de verificación para activar el perfil.

				Pruebas propuestas:

| Tipo de prueba   | Entrada / acción | Resultado |
| ------------- | ------------- | ---------------|
| Funcional | Usuario introduce un correo de verificación al perfil |El sistema recibe el correo de verificación |
| Funcional / Negativa  | Usuario introduce un correo de verificación con datos erróneos  | El sistema muestra un mensaje de error indicando que los datos son erróneos |





### 5.1. Pruebas de aceptación
Nada por aquí 

## 7. Los diccionarios de datos

No hagas nada por aquí
