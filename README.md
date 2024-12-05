# AdventureGame

## Diagrama UML de la Clase `Personajes`

```plantuml
@startuml
class Personajes {
    + string nombre
    + int puntosVida
    + int nivel
    + bool esVivo
    + int puntosDeHabilidad
    + string descripcion

    + Personajes(string Nombre, int PuntosVida, int Nivel, bool EsVivo, int PuntosDeHabilidad, string Descripcion = "Descripción no especificada")
    + int Atacar()
    + int RecibirDano(int puntos)
    + void SubirNivel()
    + bool EstaVivo()
}
@enduml



### Cómo funciona
- Si algún usuario del proyecto desea renderizar el diagrama, puede copiar este código y pegarlo en un editor de PlantUML como el [PlantUML Online Editor](https://plantuml.com/plantuml).
- Esto asegura que el diagrama está accesible en texto y sin necesidad de imágenes pre-generadas.
