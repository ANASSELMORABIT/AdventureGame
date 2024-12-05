# AdventureGame

<!-- Diagrama UML en HTML -->
<div style="display: inline-block; border: 1px solid black; font-family: Arial, sans-serif; width: 400px; text-align: center;">
  <!-- Clase -->
  <div style="background-color: #f2f2f2; font-weight: bold; padding: 10px; border-bottom: 1px solid black;">
    Personajes
  </div>
  <!-- Atributos -->
  <div style="padding: 10px; border-bottom: 1px solid black; text-align: left;">
    <u><b>Atributos</b></u><br>
    + nombre : string<br>
    + puntosVida : int<br>
    + nivel : int<br>
    + esVivo : bool<br>
    + puntosDeHabilidad : int<br>
    + descripcion : string
  </div>
  <!-- Métodos -->
  <div style="padding: 10px; text-align: left;">
    <u><b>Métodos</b></u><br>
    + Personajes(Nombre : string, PuntosVida : int, Nivel : int, EsVivo : bool, PuntosDeHabilidad : int, Descripcion : string = "Descripción no especificada")<br>
    + Atacar() : int<br>
    + RecibirDano(puntos : int) : int<br>
    + SubirNivel() : void<br>
    + EstaVivo() : bool
  </div>
</div>


