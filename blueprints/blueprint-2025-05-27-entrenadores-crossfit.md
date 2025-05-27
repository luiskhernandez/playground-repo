# Product Blueprint: Plataforma para Entrenadores de CrossFit

## Objetivo del Producto
Ayudar a entrenadores de crossfit a crear los planes de entrenamiento y asignarlos a sus atletas.

# Tipos de Usuario

## Entrenadores
- Crear planes de entrenamiento.
- Asignar planes a atletas.
- Revisar el progreso de sus atletas.

## Atletas
- Ver los planes de entrenamiento asignados.
- Registrar resultados de los entrenamientos realizados.

## Administradores
- Agregar entrenadores y atletas para la plataforma.
- Activar y desactivar usuarios del sistema.

# Flujos Principales

## Creación y asignación de un plan de entrenamiento
1. El entrenador inicia sesión.
2. Accede a la sección de creación de planes.
3. Define los ejercicios, repeticiones, tiempos y otros parametros.
4. Guarda el plan en la plataforma.
5. Selecciona uno o mas atletas y les asigna el plan creado.

## Seguimiento del plan por parte del atleta
1. El atleta inicia sesión.
2. Consulta los planes asignados.
3. Visualiza los detalles de cada entrenamiento.
4. Registra los resultados despuós de completar sesión.

## Gestión de usuarios por parte del administrador
1. El administrador accede a la plataforma.
2. Agrega nuevos entrenadores or atletas proporcionando sus datos.
3. Activa o desactiva cuentas de usuarios segun sea necesario.

# Reglas de Negocio
- Solo los entrenadores pueden crear y asignar planes.
- Cada atleta puede tener multiples planes activos.
- Solo los administradores pueden modificar el estado de una cuenta.

# Restricciones
- La plataforma debe estar disponible en dispositivos múviles y web.
- Tados los datos deben almacenarse de forma segura y cumplir las regulaciones de privacidad.
- Accesos y funcionalidades deben estar limitados segun el rol del usuario.