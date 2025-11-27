<div style="display: flex; justify-content: center; gap: 40px; margin-top: 40px; flex-wrap: wrap;">

  <!-- OPCIÓN 1: SUBIR FOTO -->
  <div style="
    width: 320px;
    padding: 25px;
    border-radius: 16px;
    background: #f7f7f7;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    text-align: center;
  ">
    <h2 style="margin-top: 0;">Proyectos</h2>
    <p>Envía tu proyecto a travez de este formulario</p>

    <form action="#" method="post">

      <select name="objeto" 
              style="width: 100%; padding: 12px; border-radius: 8px; border: 1px solid #ccc; font-size: 16px; margin-top: 10px;">
        <option value="op1">Esponja Tawashi</option>
        <option value="op2">Alfombra</option>
        <option value="op3">Tote bag</option>
      </select>

      <input type="file" name="foto" accept="image/*"
             style="margin-top: 10px;">

      <br><br>

      <button type="submit" 
              style="background:#4CAF50; color:white; padding:10px 20px; border:none; border-radius:8px; cursor:pointer; font-size:16px;">
        Enviar foto
      </button>

    </form>
  </div>


  <!-- OPCIÓN 2: SELECCIÓN DE OBJETO -->
  <div style="
    width: 320px;
    padding: 25px;
    border-radius: 16px;
    background: #f7f7f7;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    text-align: center;
  ">
    <h2 style="margin-top: 0;">Objetos</h2>
    <p>Elige una opción de la lista.</p>

    <form action="#" method="post">

      <select name="objeto" 
              style="width: 100%; padding: 12px; border-radius: 8px; border: 1px solid #ccc; font-size: 16px; margin-top: 10px;">
        <option value="op1">latas</option>
        <option value="op2">vidrios</option>
        <option value="op3">carton</option>
        <option value="op4">plasticos</option>
        <option value="op5">electronica</option>
      </select>

      <br><br>

      <button type="submit" 
              style="background:#2196F3; color:white; padding:10px 20px; border:none; border-radius:8px; cursor:pointer; font-size:16px;">
        Enviar selección
      </button>

    </form>
  </div>

</div>
