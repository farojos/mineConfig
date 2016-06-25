# mineConfig

# Tres-Cafés

## Tabla de contenidos
* [Equipo](#equipo)
    * [Integrantes](#integrantes)
    * [Ayudante](#ayudante)
* [Proyecto](#proyecto)
    * [Instrucciones](#instrucciones)
    * [Notas](#notas)



# Proyecto
Asignación de Salas

## Notas

### Algoritmo


### Testing

#### Rspec
  
  Se desarrolló testing Rspec en 4 modelos:
  1. User: Es fundamental que la aplicación cuente con una base de datos completa e integral. Más aún, la información del usuario es importante que sea testeada para asegurarse de que tengan datos de autentificación, contacto, y autenticidad.
  2. Test: La información de los tests es importante que esté completa, ya que determina cuándo y cuánto tiempo estará usada una sala y puede repercutir si puede estar disponible para los demás usuarios.
  3. Courses: Para entergar información de calidad a los usuarios y poder cumplir con la integridad de la aplicación, es necesario que las salas -un recurso fundamental para el algoritmo y entregarle valor al usuario- tenga todos los requerimientos ingresados correctamente. Sin esto, se podrían dar errores de consistencia en los resultados.
  4. Classroom: Este recurso es básico en la aplicación. Por lo tanto, su integridad y completitud debe ser resguardada. Se aseguró de que no existieran duplicaciones y que las capacidades fuesen lógicas.

#### Capybara

   1. User_makes_a_exchange_request: En la aplicación web se aseguró de que el usuario pudiese realizar sus solicitudes de intercambio de salas. Esta revisión es importante porque es un feature que puede entregar gran valor al cliente.
  
## Ejecutar proyecto
El proyecto fue desarrollado sobre ruby 2.3 y rails 4.2.6 y postgresql 9.5, además se utilizaron las gemas:
* devise
* httparty
* kickchart
* uglifier
* less-rails
* twitter-bootstrap
* gmaps4rails
* underscore-rails
* therubyracer
