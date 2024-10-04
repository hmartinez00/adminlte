# Instalacion

## 1. Creamos el proyecto

```bash
compser create-project laravel/laravel adminlte
```

o

```bash
laravel new adminlte
```
## 2. Descargar breeze

```bash
composer require laravel/breeze --dev
```

## 3. Instalar breeze

```bash
php artisan breez:install
```

Elegir las opciones

## 4. Migrar:

```bash
php artisan migrate:fresh
```

## 5. Instalar node_module

```bash
npm install
```

## 6. Instalar AdminLTE

```bash
composer require jeroennoten/laravel-adminlte
php artisan adminlte:install
```

## 7. Actualizar la vista del dashboard

Vamos a la siguiente direccion: ['https://github.com/jeroennoten/Laravel-AdminLTE/wiki/Usage'](https://github.com/jeroennoten/Laravel-AdminLTE/wiki/Usage)

Copiamos alguna de las vistas propuestas. En este caso elegiremos:

```php
@extends('adminlte::page')

@section('title', 'Dashboard')

@section('content_header')
    <h1>Dashboard</h1>
@stop

@section('content')
    <p>Welcome to this beautiful admin panel.</p>
@stop

@section('css')
    {{-- Add here extra stylesheets --}}
    {{-- <link rel="stylesheet" href="/css/admin_custom.css"> --}}
@stop

@section('js')
    <script> console.log("Hi, I'm using the Laravel-AdminLTE package!"); </script>
@stop
```

## Opciones y configuraciones

## 1. Configurar opciones

Ir al archivo adminlte\config\adminlte.php

## 2. Iconos

Provienen de [fontawesome](https://fontawesome.com/)

