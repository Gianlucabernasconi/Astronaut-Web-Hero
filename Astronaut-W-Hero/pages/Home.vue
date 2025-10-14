<script setup>
console.log(window.innerWidth, window.devicePixelRatio)

</script>

<template>
  <section class="principalsection relative h-screen overflow-hidden flex">
    <!-- Contenedor del video con overlay -->
    <div class="video-wrapper absolute top-0 left-0 w-full h-full before:content-[''] before:absolute before:inset-0 before:bg-black/90 before:z-10">
      <video autoplay muted loop playsinline preload="auto" poster="/cover.webp" class="absolute top-0 left-0 w-full h-full object-cover z-0">
  <source src="https://herosweb.b-cdn.net/Fullhdhero-720p.mp4" type="video/mp4" media="(max-width: 768px)"/>
  <source src="https://herosweb.b-cdn.net/Fullhdhero-web.mp4" type="video/mp4" media="(min-width: 769px)"/>
</video>

    </div>

    <!-- Sección izquierda -->
    <div class="seccioni flex flex-col z-20 flex-none justify-center justify-items-center content-center items-center basis-[25%]">
      <p class="font-orbitron text-lg text-[var(--color-texto)] [writing-mode:vertical-rl] tracking-[0.2em] font-bold 4k:text-4xl">ASTRONAUT HERO</p>
    </div>

    <!-- Sección central -->
    <div class="central flex flex-col justify-center items-center z-20 flex-none basis-[50%]">
      <h1 class="animate-blink-once text-[var(--color-texto)] text-[6rem] 4k:text-[8rem] font-orbit font-bold mix-blend-screen">SOLARA</h1>
      <img src="/world.webp" alt="Mundo"class="world w-[150px] h-[150px] md:w-[300px] md:h-[300px] 2k:w-[500px] 2k:h-[500px] 4k:w-[700px] 4k:h-[700px] hover:scale-105 hover:opacity-60 hover:blur-sm transition-all duration-600"/>
        <p class="description text-[var(--color-texto)] text-sm text-center font-medium 4k:text-xl">Donde la ciencia y el arte se encuentran para imaginar futuros posibles</p>
     <span class="absolute bottom-6 left-1/2 -translate-x-1/2 flex justify-center items-center gap-6 z-20">


       <!-- Github -->
  <a href="https://github.com/Gianlucabernasconi" target="_blank" rel="noopener noreferrer"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"
       class="w-6 h-6 fill-[#FFB86F] hover:fill-white hover:scale-110 transition-all duration-600 opacity-30 hover:opacity-100">
    <path d="M237.9 461.4C237.9 463.4 235.6 465 232.7 465C229.4 465.3 227.1 463.7 227.1 461.4C227.1 459.4 229.4 457.8 232.3 457.8C235.3 457.5 237.9 459.1 237.9 461.4zM206.8 456.9C206.1 458.9 208.1 461.2 211.1 461.8C213.7 462.8 216.7 461.8 217.3 459.8C217.9 457.8 216 455.5 213 454.6C210.4 453.9 207.5 454.9 206.8 456.9zM251 455.2C248.1 455.9 246.1 457.8 246.4 460.1C246.7 462.1 249.3 463.4 252.3 462.7C255.2 462 257.2 460.1 256.9 458.1C256.6 456.2 253.9 454.9 251 455.2zM316.8 72C178.1 72 72 177.3 72 316C72 426.9 141.8 521.8 241.5 555.2C254.3 557.5 258.8 549.6 258.8 543.1C258.8 536.9 258.5 502.7 258.5 481.7C258.5 481.7 188.5 496.7 173.8 451.9C173.8 451.9 162.4 422.8 146 415.3C146 415.3 123.1 399.6 147.6 399.9C147.6 399.9 172.5 401.9 186.2 425.7C208.1 464.3 244.8 453.2 259.1 446.6C261.4 430.6 267.9 419.5 275.1 412.9C219.2 406.7 162.8 398.6 162.8 302.4C162.8 274.9 170.4 261.1 186.4 243.5C183.8 237 175.3 210.2 189 175.6C209.9 169.1 258 202.6 258 202.6C278 197 299.5 194.1 320.8 194.1C342.1 194.1 363.6 197 383.6 202.6C383.6 202.6 431.7 169 452.6 175.6C466.3 210.3 457.8 237 455.2 243.5C471.2 261.2 481 275 481 302.4C481 398.9 422.1 406.6 366.2 412.9C375.4 420.8 383.2 435.8 383.2 459.3C383.2 493 382.9 534.7 382.9 542.9C382.9 549.4 387.5 557.3 400.2 555C500.2 521.8 568 426.9 568 316C568 177.3 455.5 72 316.8 72z"/> </svg></a>


         <!-- Web -->
    <a href="https://gianlucabernasconi.cl" target="_blank" rel="noopener noreferrer"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"  class="w-6 h-6 fill-[#FFB86F] hover:fill-white hover:scale-110 transition-all duration-600 opacity-30 hover:opacity-100">

    <path d="M21.721 12.752a9.711 9.711 0 0 0-.945-5.003 12.754 12.754 0 0 1-4.339 2.708 18.991 18.991 0 0 1-.214 4.772 17.165 17.165 0 0 0 5.498-2.477ZM14.634 15.55a17.324 17.324 0 0 0 .332-4.647c-.952.227-1.945.347-2.966.347-1.021 0-2.014-.12-2.966-.347a17.515 17.515 0 0 0 .332 4.647 17.385 17.385 0 0 0 5.268 0ZM9.772 17.119a18.963 18.963 0 0 0 4.456 0A17.182 17.182 0 0 1 12 21.724a17.18 17.18 0 0 1-2.228-4.605ZM7.777 15.23a18.87 18.87 0 0 1-.214-4.774 12.753 12.753 0 0 1-4.34-2.708 9.711 9.711 0 0 0-.944 5.004 17.165 17.165 0 0 0 5.498 2.477ZM21.356 14.752a9.765 9.765 0 0 1-7.478 6.817 18.64 18.64 0 0 0 1.988-4.718 18.627 18.627 0 0 0 5.49-2.098ZM2.644 14.752c1.682.971 3.53 1.688 5.49 2.099a18.64 18.64 0 0 0 1.988 4.718 9.765 9.765 0 0 1-7.478-6.816ZM13.878 2.43a9.755 9.755 0 0 1 6.116 3.986 11.267 11.267 0 0 1-3.746 2.504 18.63 18.63 0 0 0-2.37-6.49ZM12 2.276a17.152 17.152 0 0 1 2.805 7.121c-.897.23-1.837.353-2.805.353-.968 0-1.908-.122-2.805-.353A17.151 17.151 0 0 1 12 2.276ZM10.122 2.43a18.629 18.629 0 0 0-2.37 6.49 11.266 11.266 0 0 1-3.746-2.504 9.754 9.754 0 0 1 6.116-3.985Z" /></svg></a>


    <!-- Instagram -->
   <a href="https://www.instagram.com/gianlucabernasconi_/" target="_blank" rel="noopener noreferrer"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640" class="w-7 h-7 fill-[#FFB86F] hover:fill-white hover:scale-110 transition-all duration-600 opacity-30 hover:opacity-100">
  <path d="M320.3 205C256.8 204.8 205.2 256.2 205 319.7C204.8 383.2 256.2 434.8 319.7 435C383.2 435.2 434.8 383.8 435 320.3C435.2 256.8 383.8 205.2 320.3 205zM319.7 245.4C360.9 245.2 394.4 278.5 394.6 319.7C394.8 360.9 361.5 394.4 320.3 394.6C279.1 394.8 245.6 361.5 245.4 320.3C245.2 279.1 278.5 245.6 319.7 245.4zM413.1 200.3C413.1 185.5 425.1 173.5 439.9 173.5C454.7 173.5 466.7 185.5 466.7 200.3C466.7 215.1 454.7 227.1 439.9 227.1C425.1 227.1 413.1 215.1 413.1 200.3zM542.8 227.5C541.1 191.6 532.9 159.8 506.6 133.6C480.4 107.4 448.6 99.2 412.7 97.4C375.7 95.3 264.8 95.3 227.8 97.4C192 99.1 160.2 107.3 133.9 133.5C107.6 159.7 99.5 191.5 97.7 227.4C95.6 264.4 95.6 375.3 97.7 412.3C99.4 448.2 107.6 480 133.9 506.2C160.2 532.4 191.9 540.6 227.8 542.4C264.8 544.5 375.7 544.5 412.7 542.4C448.6 540.7 480.4 532.5 506.6 506.2C532.8 480 541 448.2 542.8 412.3C544.9 375.3 544.9 264.5 542.8 227.5zM495 452C487.2 471.6 472.1 486.7 452.4 494.6C422.9 506.3 352.9 503.6 320.3 503.6C287.7 503.6 217.6 506.2 188.2 494.6C168.6 486.8 153.5 471.7 145.6 452C133.9 422.5 136.6 352.5 136.6 319.9C136.6 287.3 134 217.2 145.6 187.8C153.4 168.2 168.5 153.1 188.2 145.2C217.7 133.5 287.7 136.2 320.3 136.2C352.9 136.2 423 133.6 452.4 145.2C472 153 487.1 168.1 495 187.8C506.7 217.3 504 287.3 504 319.9C504 352.5 506.7 422.6 495 452z"/>
</svg></a>

</span>



    </div>

    <!-- Sección derecha -->
      <div class="secciond flex flex-col z-20 flex-none justify-center justify-items-center content-center items-center basis-[25%]">
      <p class="font-orbitron text-lg text-[var(--color-texto)] [writing-mode:vertical-rl] tracking-[0.2em] font-bold 4k:text-4xl">ASTRONAUT HERO</p>
    </div>
  </section>
</template>


<style scoped>

.world {
  animation: spinPlanet 60s linear infinite;
}

@keyframes spinPlanet {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}


@keyframes blink-once {
  0%, 20%, 40%, 60%, 80%, 100% {
    opacity: 1;
  }
  10%, 30%, 50%, 70%, 90% {
    opacity: 0;
  }
}



.animate-blink-once {
  animation: blink-once 2.8s ease-in-out 1;



}


@media (max-width: 768px) {
.seccioni{ display: none;}

.secciond{ display: none;}




.animate-blink-once {
  animation: blink-once 2.8s ease-in-out 1; 
  font-size: 4rem;


}
.description {
  font-size: 0.775rem;
  padding: 0 1rem;
  margin-top: 1rem;
}

.principalsection {
   
  flex-direction: column;
  justify-content: center; 
  align-items: center;     
  text-align: center;
  
}

.world {
  width: 300px;
  height: 300px;
  margin: 20px 0; 
}




}





</style>