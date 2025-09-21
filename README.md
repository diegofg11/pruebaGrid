# 📦 PruebaGrid

Proyecto de ejemplo en **Java** utilizando **JavaFX** para crear una interfaz gráfica sencilla con `GridPane`.  
Sirve como base para experimentar con layouts en JavaFX y probar el funcionamiento de Maven en un proyecto modular.

## 🚀 Requisitos

- **Java 17** o superior  
- **Maven 3.6+**  
- Un IDE recomendado: **IntelliJ IDEA** o **NetBeans**

## 🛠 Instalación y ejecución

1. Clona este repositorio o descomprime el ZIP:  
   ```bash
   git clone https://github.com/tu-usuario/pruebaGrid.git
   ```
2. Entra en el directorio del proyecto:  
   ```bash
   cd pruebaGrid
   ```
3. Compila y ejecuta con Maven:  
   ```bash
   mvn clean javafx:run
   ```

> 💡 También puedes abrirlo directamente en tu IDE y ejecutar la clase `MainApp`.

## 📂 Estructura del proyecto

```
pruebaGrid/
 ├── src/main/java/
 │   └── org/example/
 │       ├── MainApp.java       # Clase principal
 │       └── Controlador.java   # Controlador de la interfaz
 ├── src/main/resources/
 │   ├── fxml/primary.fxml      # Layout principal en FXML
 │   └── styles/Styles.css      # Estilos de la interfaz
 ├── pom.xml                    # Configuración de Maven
```

## 🎯 Objetivo

Mostrar cómo funciona un `GridPane` en JavaFX y servir de punto de partida para proyectos con interfaz gráfica.
