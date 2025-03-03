# Lisp Lexer - Analizador Léxico de Expresiones LISP

## 📌 Descripción
Este proyecto es un **analizador léxico (Lexer)** desarrollado en **Java** para analizar expresiones en **LISP**. 
Permite descomponer una expresión en tokens y verificar si los paréntesis están balanceados.

## 🚀 Características
- 🔍 **Verificación de balanceo de paréntesis**
- 🔠 **Tokenización de operadores, números y variables**
- 🎨 **Salida en colores para mejor visualización**
- 🎮 **Menú interactivo con opción de salida**

## 🛠️ Requisitos
- **Java 8 o superior**

## 📥 Instalación y Uso
1. **Clona el repositorio**
   ```sh
   git clone https://github.com/tuusuario/LispLexer.git
   cd LispLexer
   ```

2. **Compila el código**
   ```sh
   javac LispLexer.java
   ```

3. **Ejecuta el programa**
   ```sh
   java LispLexer
   ```

4. **Ejemplo de uso**
   ```sh
   Ingrese una expresión LISP o escriba 'salir' para terminar:
   (+ 2 (* 3 4))
   ✅ Expresión correcta: los paréntesis están balanceados.
   🟡 Tokens: [(, +, 2, (, *, 3, 4, ), )]
   ```

## 📝 Expresiones de Prueba
Prueba el analizador con estas expresiones:

### ✅ **Expresiones Correctas**
```lisp
(+ 2 (* 3 4))
(- (/ 10 (+ 2 3)) (* 4 5))
(define x 10)
((lambda (x) (* x x)) 5)
(begin (set! x 5) (set! y (+ x 2)) (* x y))
```

### ❌ **Expresiones Incorrectas**
```lisp
(+ 2 (* 3 4)
(* (+ 1 2)) 3)
) (+ 2 3) (
```

## ✨ Autores
- **Denil José Parada Cabrera - 24761**
- **Joel
- Arodi Josué Chávez Ramírez - 241112


## 📜 Licencia
Este proyecto es de código abierto y puedes usarlo con fines educativos.

