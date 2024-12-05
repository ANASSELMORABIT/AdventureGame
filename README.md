# AdventureGame

<!-- Diagrama UML en HTML -->
<h2>Clase <code>Personajes</code></h2>

<table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th colspan="3">Personajes</th>
    </tr>
  </thead>
  <tbody>
    <!-- Atributos -->
    <tr>
      <td colspan="3" style="font-weight: bold;">Atributos</td>
    </tr>
    <tr>
      <td><b>Modificador</b></td>
      <td><b>Tipo</b></td>
      <td><b>Nombre</b></td>
    </tr>
    <tr>
      <td>public</td>
      <td>string</td>
      <td>nombre</td>
    </tr>
    <tr>
      <td>public</td>
      <td>int</td>
      <td>puntosVida</td>
    </tr>
    <tr>
      <td>public</td>
      <td>int</td>
      <td>nivel</td>
    </tr>
    <tr>
      <td>public</td>
      <td>bool</td>
      <td>esVivo</td>
    </tr>
    <tr>
      <td>public</td>
      <td>int</td>
      <td>puntosDeHabilidad</td>
    </tr>
    <tr>
      <td>public</td>
      <td>string</td>
      <td>descripcion</td>
    </tr>

    <!-- Métodos -->
    <tr>
      <td colspan="3" style="font-weight: bold;">Métodos</td>
    </tr>
    <tr>
      <td><b>Modificador</b></td>
      <td><b>Retorno</b></td>
      <td><b>Nombre</b></td>
    </tr>
    <tr>
      <td>public</td>
      <td>int</td>
      <td>Atacar()</td>
    </tr>
    <tr>
      <td>public</td>
      <td>int</td>
      <td>RecibirDano(int)</td>
    </tr>
    <tr>
      <td>public</td>
      <td>void</td>
      <td>SubirNivel()</td>
    </tr>
    <tr>
      <td>public</td>
      <td>bool</td>
      <td>EstaVivo()</td>
    </tr>

    <!-- Constructor -->
    <tr>
      <td colspan="3" style="font-weight: bold;">Constructor</td>
    </tr>
    <tr>
      <td><b>Modificador</b></td>
      <td><b>Nombre</b></td>
      <td><b>Parámetros</b></td>
    </tr>
    <tr>
      <td>public</td>
      <td>Personajes</td>
      <td>string Nombre, int PuntosVida, int Nivel, bool EsVivo, int PuntosDeHabilidad, string Descripcion = "Descripción no especificada"</td>
    </tr>
  </tbody>
</table>

