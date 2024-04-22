# EDA_P1
Primera práctica del laboratorio de EDA.
Se trata de desarrollar la implementación genérica del TAD pila usando tanto memoria 
estática como memoria dinámica. El desarrollo se ajustará a la especificación descrita en 
clase de teoría para el TAD pila. En concreto, tanto la especificación estática como la 
dinámica deberán responder a la siguiente especificación sintáctica:
Interface Stack
 method push(element: T): void 
 method pop(): T 
 method top(): T
 method isEmpty(): boolean 
 method size(): int 
 method toString(): String
end_Stack_Interface
El desarrollo deberá realizarse en Java, ateniéndose a los siguientes requisitos:
• Será necesario implementar todas las excepciones necesarias para tener en cuenta 
los posibles problemas vinculados tanto a la definición como, en su caso, a la 
implementación.
• Tanto la especificación estática como la dinámica deberán estar documentadas 
internamente de forma adecuada usando notación javadoc.
• Se valorará que en la implementación estática se puedan introducir tantos 
elementos en la pila como sean necesarios de forma transparente al usuario.
• Todas las interfaces y clases desarrolladas deberán integrarse en un paquete 
llamado pilasPackage.
• Deberá generarse un fichero .jar conteniendo la implementación del paquete 
desarrollado
