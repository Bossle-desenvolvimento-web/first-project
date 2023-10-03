<template>
  <main>
    <header>
        <h1>Site title</h1>
        <figure>
            <img src="" alt="logoSite">
        </figure>
        <ul class="nav nav-pills nav-fill gap-2 p-1 small bg-primary rounded-5 shadow-sm" id="pillNav2" role="tablist" style="--bs-nav-link-color: var(--bs-white); --bs-nav-pills-link-active-color: var(--bs-primary); --bs-nav-pills-link-active-bg: var(--bs-white);">
  <li class="nav-item" role="presentation">
    <button class="nav-link active rounded-5" id="home-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="true">Home</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link rounded-5" id="profile-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="false">Profile</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link rounded-5" id="contact-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="false">Contact</button>
  </li>
</ul>
    </header>
    <div class="container text-center">
  <div class="row align-items-start">
    <div class="col">
      <h3>One of three columns</h3>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>


    </div>
    <div class="col">
      <h3>One of three columns</h3>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>
    </div>
    <div class="col">
      <h3>One of three columns</h3>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>
      <div class="p-5">Custom column padding</div>
    </div>
  </div>
</div>
  </main>
</template>

<script>

export default{

name: 'primeiroComponente'

}

</script>

<style>
main{width: 90%;
     height: auto;
     margin-bottom: 5px;
     margin: auto;
    background-color: burlywood;}

    

 .col{background-color: cornflowerblue;}   

.p-5{background-color:#f6f6;
       width: 100%;
       margin: auto;
       border: solid 3px #000;
           margin-bottom:5px;
            background-color: #7a4040;}

       


      
     

/*@media (min-width: 576px) {  }


@media (min-width: 768px) {  }


@media (min-width: 992px) { }


@media (min-width: 1200px) { }


@media (min-width: 1400px) {  }*/

            
 </style>