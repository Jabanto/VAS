# VAS
Es una aplicación utilizando WPF, el framework Entity Framework, y una base de datos SQLite para la gestión de herramientas

# Aplicación de Gestión de Herramientas

## Descripción
Esta es una aplicación de escritorio desarrollada con **WPF** (Windows Presentation Foundation) utilizando **.NET Framework 8**. El proyecto implementa el patrón **MVVM** (Model-View-ViewModel) y utiliza **Entity Framework** para la gestión de datos con **SQLite** como base de datos.

La solución contiene tres proyectos:
1. **EFDataAccess**: Contiene los modelos, repositorios, migraciones y la configuración de la base de datos, así como los servicios para la lógica de negocio.
2. **EFDataAccessTest**: Proyecto dedicado a las pruebas de los servicios y repositorios más importantes.
3. **VAS_UI**: Interfaz de usuario (UI) desarrollada con WPF siguiendo el patrón MVVM. Está conectada al proyecto `EFDataAccess`. Se ha creado una sesión inicial donde se cargan valores por defecto para permitir el uso inmediato de la aplicación.

## Características
- Aplicación de escritorio con WPF y MVVM.
- Gestión de datos utilizando Entity Framework y SQLite.
- Sistema modular con separación de la lógica de negocio y la UI.
- Proyecto de pruebas para asegurar la calidad del código.

## Instalación
1. Clona el repositorio:
    ```bash
    git clone https://github.com/Jabanto/vas.git
    ```
2. Restaura los paquetes NuGet:
    ```bash
    dotnet restore
    ```
3. Aplica las migraciones a la base de datos:
    ```bash
    dotnet ef database update
    ```
4. Ejecuta el proyecto `VAS_UI`.

## Ejecución
Una versión ejecutable está disponible para su descarga en la sección de **Releases** de este repositorio.

### README in English

# Tool Management Application

## Description
This is a desktop application developed with **WPF** (Windows Presentation Foundation) using **.NET Framework 8**. The project follows the **MVVM** (Model-View-ViewModel) pattern and uses **Entity Framework** for data management with **SQLite** as the database.

The solution contains three projects:
1. **EFDataAccess**: Contains models, repositories, migrations, and database configuration, as well as services for business logic.
2. **EFDataAccessTest**: Project dedicated to testing the most important services and repositories.
3. **VAS_UI**: User Interface (UI) built with WPF following the MVVM pattern. It connects to the `EFDataAccess` project. An initial session is created where default values are loaded to allow immediate use of the application.

## Features
- Desktop application with WPF and MVVM.
- Data management using Entity Framework and SQLite.
- Modular system with separation of business logic and UI.
- Test project to ensure code quality.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Jabanto/vas.git
    ```
2. Restore NuGet packages:
    ```bash
    dotnet restore
    ```
3. Apply migrations to the database:
    ```bash
    dotnet ef database update
    ```
4. Run the `VAS_UI` project.

## Execution
An executable version is available for download in the **Releases** section of this repository.

### README auf Deutsch

# VAS: Werkzeugverwaltungsanwendung

## Beschreibung
Dies ist eine Desktop-Anwendung, die mit **WPF** (Windows Presentation Foundation) und **.NET Framework 8** entwickelt wurde. Das Projekt verwendet das **MVVM** (Model-View-ViewModel) Muster und **Entity Framework** für die Datenverwaltung mit **SQLite** als Datenbank.

Die Lösung enthält drei Projekte:
1. **EFDataAccess**: Enthält Modelle, Repositories, Migrationen und Datenbankkonfiguration sowie Dienste für die Geschäftslogik.
2. **EFDataAccessTest**: Projekt für Tests der wichtigsten Dienste und Repositories.
3. **VAS_UI**: Benutzeroberfläche (UI) entwickelt mit WPF nach dem MVVM-Muster. Es ist mit dem Projekt `EFDataAccess` verbunden. Eine initiale Sitzung lädt Standardwerte, um die sofortige Nutzung der Anwendung zu ermöglichen.

## Funktionen
- Desktop-Anwendung mit WPF und MVVM.
- Datenverwaltung mit Entity Framework und SQLite.
- Modulares System mit Trennung von Geschäftslogik und UI.
- Testprojekt zur Sicherstellung der Codequalität.

## Installation
1. Klone das Repository:
    ```bash
    git clone https://github.com/Jabanto/vas.git
    ```
2. Wiederherstellen der NuGet-Pakete:
    ```bash
    dotnet restore
    ```
3. Migrationen auf die Datenbank anwenden:
    ```bash
    dotnet ef database update
    ```
4. Starte das Projekt `VAS_UI`.

## Ausführung
Eine ausführbare Version steht im **Releases** Bereich dieses Repositories zum Download bereit.

### README en Français
# Application de Gestion des Outils

## Description
C'est une application de bureau développée avec **WPF** (Windows Presentation Foundation) en utilisant **.NET Framework 8**. Le projet suit le modèle **MVVM** (Model-View-ViewModel) et utilise **Entity Framework** pour la gestion des données avec **SQLite** comme base de données.

La solution contient trois projets :
1. **EFDataAccess** : Contient les modèles, référentiels, migrations et configuration de la base de données, ainsi que des services pour la logique métier.
2. **EFDataAccessTest** : Projet dédié aux tests des services et référentiels les plus importants.
3. **VAS_UI** : Interface utilisateur (UI) développée avec WPF suivant le modèle MVVM. Elle est connectée au projet `EFDataAccess`. Une session initiale est créée où des valeurs par défaut sont chargées pour permettre une utilisation immédiate de l'application.

## Caractéristiques
- Application de bureau avec WPF et MVVM.
- Gestion des données utilisant Entity Framework et SQLite.
- Système modulaire avec séparation de la logique métier et de l'interface utilisateur.
- Projet de test pour assurer la qualité du code.

## Installation
1. Clonez le dépôt :
    ```bash
    git clone https://github.com/Jabanto/vas.git
    ```
2. Restaurez les paquets NuGet :
    ```bash
    dotnet restore
    ```
3. Appliquez les migrations à la base de données :
    ```bash
    dotnet ef database update
    ```
4. Exécutez le projet `VAS_UI`.

## Exécution
Une version exécutable est disponible pour téléchargement dans la section **Releases** de ce dépôt.

