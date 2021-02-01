<template>
  <div class="about">
   <div class="container">
   <div class="row">
     <div class="col-9">
       <h2> Modelo 1</h2>
       <img src="https://hips.hearstapps.com/es.h-cdn.co/cades/contenidos/56958/mini-cooper-s-delaney-edition-1.jpg" alt="Lamp" width=500 px>
     </div>
     <div class="col-3">
       <h4>PRECIO</h4>
       <p> $X.XXX</p>
<div>
  <b-button v-b-modal.modal-1>RESERVA</b-button>

  <b-modal id="modal-1" title="INGRESO DE RESERVA">
    <p class="my-4"> Ingresa los datos</p>
    
    <form>
  <div class="form-group">
    <label for="formGroupExampleInput">Nombre</label>
    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Example input">
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2">Rut</label>
    <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
  </div>
 <div class="form-group">
    <label for="formGroupExampleInput2">Correo</label>
    <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
  </div>
 <div class="form-group">
    <label for="formGroupExampleInput2">Telefono</label>
    <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
  </div>
  <fieldset class="form-group">
    <div class="row">
      <legend class="col-form-label col-sm-2 pt-0">SUCURSAL</legend>
      <div class="col-sm-10">
        <div class="form-check">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios1" value="option1" checked>
          <label class="form-check-label" for="gridRadios1">
           SUCURSAL 1
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios2" value="option2">
          <label class="form-check-label" for="gridRadios2">
           SUCURSAL 2
          </label>
        </div>
        <div class="form-check disabled">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios3" value="option3" disabled>
          <label class="form-check-label" for="gridRadios3">
            SUCURSAL 3
          </label>
        </div>
      </div>
    </div>
  </fieldset>

    <fieldset class="form-group">
    <div class="row">
      <legend class="col-form-label col-sm-2 pt-0">COLOR</legend>
      <div class="col-sm-10">
        <div class="form-check">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios1" value="option1" checked>
          <label class="form-check-label" for="gridRadios1">
           1
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios2" value="option2">
          <label class="form-check-label" for="gridRadios2">
     2
          </label>
        </div>
        <div class="form-check disabled">
          <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios3" value="option3" disabled>
          <label class="form-check-label" for="gridRadios3">
    3
          </label>
        </div>
      </div>
    </div>
  </fieldset>

</form>
  </b-modal>
</div>
     </div>
   </div>
   </div>
<p>
  Lorem ipsum dolor sit amet consectetur adipiscing elit taciti elementum, volutpat ad eleifend venenatis aptent nisi ante quis, habitant commodo litora sociis cum turpis aenean penatibus. Turpis nec justo mus ridiculus odio ultrices suspendisse at, eget nisl fames vitae purus diam per volutpat, phasellus platea nibh vivamus sagittis sociosqu ultricies. Aliquet dis malesuada nisi justo molestie congue conubia eget mollis suspendisse iaculis nisl, maecenas hac facilisi lacinia ornare nunc cursus mus habitant ac.
</p>
<p>
Erat commodo fermentum nullam penatibus venenatis natoque pretium cubilia, aptent ridiculus pellentesque sed sollicitudin ante ullamcorper hendrerit, vulputate urna fusce diam cursus lectus aenean. Tristique nascetur iaculis maecenas torquent aptent viverra dictumst consequat sapien, vulputate luctus mattis fringilla cras augue sagittis dui, taciti tempor lectus interdum proin cursus inceptos vitae. Netus magna ornare sociis auctor pretium pellentesque purus suscipit convallis porttitor, elementum torquent maecenas facilisis habitasse volutpat fames vehicula ullamcorper laoreet vitae, proin ac nascetur a sodales condimentum dignissim natoque parturient.
</p>



  </div>
  
</template>

<script>
export default {
  name:"ejemplo"
}
</script>


<style>
p{
  margin: 5%;
}


</style>
