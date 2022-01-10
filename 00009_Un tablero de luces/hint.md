Apagar una celda implica dos cosas: sacar una bolita verde y agregar una negra; lo mismo para prender pero en sentido inverso.

Para saber si está prendida o no, basta con fijarse si hay bolitas del color que querramos.

* Por ejemplo, acá la luz está prendida y al invocar `PrenderOApagarLuz()` se apaga:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Verde 1
        cell 1 0 Verde 1
        cell 0 1 Verde 1
        cell 1 1 Verde 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Negro 1
        cell 1 0 Verde 1
        cell 0 1 Verde 1
        cell 1 1 Verde 1
        head 0 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

* En cambio, acá está apagada y con tu procedimiento se prende:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Negro 1
        cell 1 0 Negro 1
        cell 0 1 Verde 1
        cell 1 1 Verde 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Verde 1
        cell 1 0 Negro 1
        cell 0 1 Verde 1
        cell 1 1 Verde 1
        head 0 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
