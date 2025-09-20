# Community Safe App 
> Implementación de aplicaciones web y móvil para gestionar emergencias comunitarias en la provincia de Santo Domingo de los Tsáchilas

## Tabla de contenido

1. Preview
2. Configuración del entorno 
3. Plataformas
4. Instalación
5. Responsables

## 1. Preview

Pendiente.

## 2. Configuración del entorno: Desarrollo

### 2.1 Windows

#### 2.1.1 Instalación IDE

Descarga Android studio [aquí](https://developer.android.com/studio?hl=es-419).

#### 2.1.2 Abrir powershell como administrador

#### 2.1.3 Instalar flutter dart-sdk

```powershell
git clone https://github.com/flutter/flutter.git -b stable C:\src\flutter
```

#### 2.1.4 Agregar variable de Entorno

```powershell
setx PATH "C:\src\flutter\bin;$env:PATH" /M
```

#### 2.1.5 Verificar instalación

```powershell
flutter --version
```

```powershell
flutter doctor -v
```

#### 2.1.6 Instalar dependencias

Desde la carpeta raíz del proyecto, ejecutar:

```powershell
flutter pub get
```

#### 2.1.7 Configurar dart-sdk

Seleccionar alerta en parte superior derecha de configurar SDK, colocar ruta en:

```powershell
C:\src\flutter\bin\cache\dart-sdk
```

#### 2.1.8 Verficar dispositivos

```powershell
flutter devices
```

#### 2.1.9 Ejecución en modo debug

```powershell
flutter run
```

#### 2.1.10 Para bajo consumo de recursos, usar chrome

```powershell
flutter run -d web-server
```

url:  http://localhost:37757/

## 3. Arquitectura Base de Datos 

Pendiente.

## 4. Instalación

Pendiente autorización para subir Google Play Store.

## 5. Enlaces de ayuda

[Blog](https://sites.google.com/espe.edu.ec/emergencias-comunitarias-espe): Guía de instalación y capacitaciones de Community Safe

## 5. Autores

### 5.1 Periodo 202551

| No | Responsable       | Rol                             |
|----|-------------------|---------------------------------|
| 1  | Edwin Camino      | Director de proyecto            |
| 2  | Paulo Galarza     | Desarrollador Frontend, Backend |
| 3  | Jefferson Mejía   | Desarrollador Front, Backend    |
| 4  | Andrés Ushiña     | Documentación                   |
| 5  | Shadia Reyes      | Gestión de Moodle               |
| 6  | Dayanara Bautista | Diseño                          |

### 5.2 Periodo 202550

Colocar autores de periodos anteriores si lo requiere.
