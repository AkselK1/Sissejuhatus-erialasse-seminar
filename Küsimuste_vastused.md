# küsimused

1) Enamus viisid, mis leidsin nõudsid nii html faili kui ka css faili sisu muutmist, näiteks: HTML sisu tuli muuta nii:
   <div class="row">
  <div class="column"></div>
  <div class="column"></div>
  </div> 
  
  ja CSS sisu tuli muuta nii: .column {
  float: left;
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
(ise ma selle ülesandega just kõige paremini hakkama ei saanud kahjuks.

2) fail võib kergelt muutuda liiga segaseks + võib seda olla raske hooldata (ehk muuta jne). vastikult peab hakkama teksti kordama, kui tahad mitmele elemendile samat stiili rakendada. Nii on kergem muuta terve veebilehe kujundust ja nii ei pea ka muutma otseselt veebilehe sisu.
