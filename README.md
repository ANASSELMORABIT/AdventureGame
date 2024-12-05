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
