# Condicionales y bucles

Los condicionales permiten ejecutar instrucciones según se cumpla una condición. Los bucles repiten instrucciones.

## Condicional `if`

```java
int nota = 7;

if (nota >= 5) {
    System.out.println("Aprobado");
} else {
    System.out.println("Suspendido");
}
```

## Bucle `for`

```java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

!!! warning "Atención"
    Comprueba la condición de los bucles para evitar repeticiones que no terminan.
