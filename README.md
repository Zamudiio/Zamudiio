<style>
   .card {
      width: 65%;
      height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background-color: rgb(245, 245, 245);
      border-radius: 12px;
      border:none;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2); /* sombra */
      animation: shadow 1s infinite alternate; /* animación con movimiento */
      color:#505050;
      transition: transform 0.s ease-out;
   }
   .card:hover {
      transform: translateY(-5px); /* desplazamiento hacia arriba */
   }
   @keyframes shadow {
     from {
       box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
     }
     to {
       box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
     }
   }
</style>

   <img src='https://avatars.githubusercontent.com/u/108287197?v=4'
      style="display: block; margin: 0 auto; border-radius:50%; border:8px solid #B7A38A; margin-bottom:15px">

   <div style="width: 100%; display: flex; flex-direction: column; justify-content: center; align-items: center;">
      <div class="card">
         <h1>- Desarrollador de Software Jr -</h1>
         <hr/>
         <h3>- FullStack Developer 🦅 -</h3>
         <h4>- Mobile Developer 🤳🏻 -</h4>
         <h5>- Multiplataforma 📺 -</h5>
      </div>
   </div>
