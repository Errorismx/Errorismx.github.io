<script>
    import {onMount, onDestroy} from 'svelte'
  import TailwindCSS from './style/TailwindCSS.svelte';
  // import { fetchNui } from './utils/fetchNui';
  // import { debugData } from './utils/debugData';
  const onDevBrowser = () => !window.invokeNative; // is running from fivem
  let nuiVisible = true
  function openInNewTab(url) {
    window.open(url, '_blank').focus();
  }
  onDestroy(() =>  window.removeEventListener('message', window.listener));
  onMount(() => {
    window.listener = window.addEventListener('message', (e) => {
      const nuiMsg = e.data;
      const action = event.action;
      switch (action) {
        case 'show':
          nuiVisible = nuiMsg.data
      }

       
    }); 
  });
</script>

<TailwindCSS />

<div class="absolute w-full overflow-hidden " >
  <div class="mt-[15rem] flex justify-center items-center font-noto font-black text-[20rem] md:text-[23rem]" style="
  text-align: center;
  text-transform: uppercase;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.04) 25.5%, rgba(255, 255, 255, 0) 93.65%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  ">PORTFOLIO</div>
</div>

<div class="absolute w-full overflow-hidden mt-[110.875rem] md:mt-[221.875rem] xl:mt-[106.25rem] " >
  <div class="mt-[15rem] flex justify-center items-center font-noto font-black text-[35.081875rem]" style="
  text-align: center;
  text-transform: uppercase;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.04) 25.5%, rgba(255, 255, 255, 0) 93.65%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  ">D*CODE</div>
</div>
<main class="container mx-auto scroll-smooth ">
  <div class="grid justify-center grid-cols-1 2xl:grid-cols-2 ">
    
    <div class=" md:h-[80.6875rem] h-[50.6875rem] relative order-2	xl:order-1  md:scale-100 scale-50 md:mt-0 mt-[-14rem]">

      <div class="absolute left-[6rem]">
      <div class="absolute w-[52.755rem] mt-[8rem] left-[-31.5rem] h-[52.755rem] ">
        <div class="flex items-center justify-center w-full h-full">
          <img src="./img/logo-colourful.png" style="transform: rotate(17.28deg)" alt="">

        </div>
      </div>

   
      <div class="absolute w-[21.8125rem] h-[15.4375rem] mt-[-0.625rem] flex justify-center items-center ">
      <svg  width="349" height="247" viewBox="0 0 349 247" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M10.9468 238.908C51.17 250.93 137.298 244.43 160.024 122.26C182.75 0.0899038 294.723 -6.19951 347.869 5.92704" stroke="#353B4B" stroke-width="3"/>
        <circle cx="9.77493" cy="237.686" r="9" transform="rotate(26.7248 9.77493 237.686)" fill="#32498C"/>
        <circle cx="9.78361" cy="237.583" r="6" transform="rotate(88.0519 9.78361 237.583)" fill="#15181E"/>
        <circle cx="162.066" cy="111.49" r="6.5" transform="rotate(72.7813 162.066 111.49)" fill="#353B4B"/>
        <circle cx="172.503" cy="183.522" r="2" transform="rotate(88.0519 172.503 183.522)" fill="#353B4B"/>
        <line x1="151.949" y1="45.0849" x2="172.393" y2="183.584" stroke="#353B4B"/>
        </svg>
      </div>
      <div class="w-[7.5rem] h-[29.125rem] absolute mt-[37rem] left-[-2rem] z-10">
        <svg  width="120" height="466" viewBox="0 0 120 466" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M83.57 455.277C115.088 423.025 153.909 336.914 57.043 250.489C-39.8231 164.064 12.5681 53.2556 50.872 8.65439" stroke="#353B4B" stroke-width="2.68958"/>
          <circle cx="50.086" cy="9.08594" r="9" transform="rotate(26.7248 50.086 9.08594)" fill="#744188"/>
          <circle cx="50.0943" cy="8.98315" r="6" transform="rotate(88.0519 50.0943 8.98315)" fill="#15181E"/>
          <circle cx="82.086" cy="456.086" r="9" transform="rotate(26.7248 82.086 456.086)" fill="#744188"/>
          <circle cx="82.0943" cy="455.983" r="6" transform="rotate(88.0519 82.0943 455.983)" fill="#15181E"/>
        </svg>
      </div>
    </div>

    <div class=" absolute w-[14.5rem] h-[4.3rem] mt-[38.5rem] left-[8.8rem]">
      <div class="relative w-full h-full ">
        <div class="absolute w-[1.75rem] h-[1.75rem] ">
          <svg style="box-shadow: 0px 1.25638px 2.51277px rgba(0, 0, 0, 0.28);" width="21" height="23" viewBox="0 0 21 23" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1.11008 1.11744L20.1042 11.8671L10.8805 14.669C10.5985 14.7547 10.3561 14.9354 10.1955 15.1798L5.57787 22.204L1.11008 1.11744Z" fill="black" stroke="white" stroke-width="1.25638"/>
          </svg>
            
            
        </div>
        <div class=" absolute w-[13.5rem] h-[2.625rem] bg-[#FFCD29] bottom-1 right-0" style="border: 2px solid #CCA421;
        border-radius: 0px 2.71875rem 2.71875rem 2.5rem;box-shadow: 0.25rem 0.3125rem 0.5rem rgba(255, 205, 41, 0.25);">
          <div class="w-full h-full flex justify-center items-center text-[#A08119] font-medium text-[0.9375rem] ">
         
              i love design and coding.
        
          </div>

        </div>
        
      </div>
    </div>
      
        <div class="absolute xl:w-[50rem] text-2xl w-[24rem] md:w-[40rem] md:text-4xl xl:text-5xl font-bold text-white font-jetbrains-mono mt-[45.3rem] left-[10rem] 2xl:w-[50rem] ">
          Hi I’m Nitipoom Aumpitak -
        </div>
        <div class="absolute xl:pt-[0px]   w-[15rem] md:w-[30rem] md:pt-[20px]  text-2xl md:text-4xl xl:text-5xl font-bold text-white font-noto mt-[47.3rem] md:mt-[49.3rem] left-[10rem] " style="
        background: linear-gradient(90deg, rgba(50, 73, 140, 0.76) 0%, rgba(189, 57, 132, 0.76) 103.68%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        text-fill-color: transparent;

        ">
        
          Fullstack Developer
        </div>
        
        <div class=" absolute h-[5.38375rem] mt-[65.8rem]">
          <div class=" flex justify-center items-center text-[2.5rem] font-bold text-white">
            <div class="pr-[10px]  h-[5.38375rem]">My,</div>
            <div class="w-[14.125rem] h-[5.38375rem] bg-[#794188] flex justify-center items-center" style="
            transform: rotate(4.03deg);
            "><p style="transform: rotate(-1.03deg);"> Myself & I</p></div>
          </div>
        
        </div>
        <div class="absolute mt-[70.8rem] left-[-11rem]">
          <svg width="387" height="266" viewBox="0 0 387 266" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M-171.456 265.441C-148.812 211.557 -65.8843 115.453 84.6768 162.104C235.238 208.755 340.742 82.5188 374.674 13.5696" stroke="#353B4B" stroke-width="2.68958"/>
            <circle cx="377.086" cy="9.08594" r="9" transform="rotate(26.7248 377.086 9.08594)" fill="#744188"/>
            <circle cx="377.094" cy="8.98321" r="6" transform="rotate(88.0519 377.094 8.98321)" fill="#15181E"/>
            </svg>
            

        </div>
        
      
    </div>
    
    <div class=" xl:h-[80.6875rem] h-[49.6875rem] md:h-[60.6875rem]  relative order-1 xl:order-2">
      <div class="absolute w-full h-full">
        <div class="flex items-center justify-center w-full h-full">

          <div class="w-0 h-full xl:h-2/3 !border-[1px] md:!border-[2px] " style="border: 2px dashed #272525;"></div>
        </div>
        
      </div>

      <div class="absolute w-full h-full">
        <div class="flex justify-center w-full h-full">
          <div class="flex justify-center items-center w-[17.1875rem] md:w-[22.1875rem] h-[18.5rem] md:h-[23.5rem] mt-[8.125rem]">
            <img src="./img/my-img.png" alt="">
          </div>
        </div>
      </div>
       <!-- CHATBOX SECTION -->
      <div class="absolute w-full h-full">
     
        <div class="slide-in-elliptic-bottom-fwd flex flex-col items-center justify-center w-full h-[23.5rem] mt-[8.125rem] scale-[0.55] md:scale-[0.70] xl:scale-100">
             <!-- 1 -->
          <div class="w-[14.125rem]  h-[5.125rem] ml-[-25.1rem] relative chatbox-skewY-v1 " >
            <div class="absolute bg-[#44444445] w-full h-full "
        
            style="backdrop-filter: blur(5px) !important;clip-path : path('M0 5.94234C0 2.72183 2.61074 0.111084 5.83125 0.111084H219.741C222.962 0.111084 225.572 2.72183 225.572 5.94234V51.6638C225.572 54.5257 223.252 56.8458 220.39 56.8458V56.8458C217.528 56.8458 215.208 59.1659 215.208 62.0279V77.0107L198.654 58.7595C197.549 57.5408 195.98 56.8458 194.335 56.8458H5.83126C2.61075 56.8458 0 54.2351 0 51.0146V5.94234Z')" 
            >
            <div class="flex items-center justify-center w-full h-[4rem]  text-white font-noto">
              You can call me Bus  🙌
            </div>
            </div>
            <div class=" absolute mt-[-25px] w-[3.125rem] h-[3.125rem] ">
    
              <img src="./img/moji_1.png" alt="">
            </div>
          </div>
             <!-- 2 -->
          <div class="w-[14.6875rem]  h-[5.0625rem] mr-[-25.8rem] relative chatbox-skewY-v2" >
            <div class="absolute bg-[#44444445] w-full h-full "
        
            style="backdrop-filter: blur(5px) !important;clip-path : path('M235.093 6.73207C235.093 3.51156 232.482 0.900818 229.262 0.900818H5.8312C2.61069 0.900818 -5.28239e-05 3.51156 -5.28239e-05 6.73207V52.2348C-5.28239e-05 55.2176 2.41796 57.6356 5.40072 57.6356V57.6356C8.38349 57.6356 10.8015 60.0536 10.8015 63.0363V77.8005L28.1375 59.4611C29.239 58.2958 30.7717 57.6356 32.3751 57.6356H229.262C232.482 57.6356 235.093 55.0248 235.093 51.8043V6.73207Z')" 
            >
            <div class="flex items-center justify-center w-full h-[4rem]  text-white font-noto">
              That was really awesome!
            </div>
            </div>
            <div class=" absolute mt-[-25px] w-[3.125rem] h-[3.125rem] ">
    
              <img src="./img/moji_3.png" alt="">
            </div>
            
          </div>
          <!-- 3 -->
          <div class="w-[16.890625rem]  h-[5.125rem]  ml-[-21.1rem] mt-[4rem] relative chatbox-skewY-v3" >

            <div class="absolute bg-[#44444445] w-full h-full "
            style="backdrop-filter: blur(5px) !important;
            clip-path : path('M0.182861 75.5546C0.182861 78.7751 2.7936 81.3859 6.01411 81.3859H264.599C267.819 81.3859 270.43 78.7751 270.43 75.5546V26.7539C270.43 24.1005 268.279 21.9495 265.626 21.9495V21.9495C262.972 21.9495 260.821 19.7984 260.821 17.145V0.824333L245.615 19.7684C244.508 21.1473 242.836 21.9495 241.067 21.9495H6.0141C2.79359 21.9495 0.182861 24.5602 0.182861 27.7807V55.6394V75.5546Z')" 
            >
            <div class="flex items-center justify-center w-full h-[7rem]  text-white font-noto">
              Different is better than better
            </div>
            </div>
            <div class=" absolute  w-[3.125rem] h-[3.125rem] ">
    
              <img src="./img/moji_2.png" alt="">
            </div>
          </div>
        </div>
      </div>

      <div class="absolute w-full h-full scale-75 md:scale-100 ">
        <div class="flex flex-col justify-center items-center w-full h-[19.5625rem] mt-[34.1875rem] gap-y-[2.5rem]">
          <div class="relative w-full h-12">
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12">
                <div class="text-white hover:text-white font-medium text-base uppercase ml-[14.5rem] md:ml-[16.5rem] transition-all duration-1000 w-[12rem] text-left focus-in-expand-fwd">errorism#0001</div>
              </div>
            </div>
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12 ">
                <button  on:click="{()=> {openInNewTab("https://discord.gg/XN5Z9ZJ6q8")}}"  class="relative w-12 h-full transition-all duration-700 hover:-translate-y-2 hover:scale-125 focus:opacity-25">
                  <img src="./img/media-logo-discord.png" class="absolute top-0 right-0 w-12 h-12 hover:animate-ping hover:blur-[1px] " alt="">
                  <img src="./img/media-logo-discord.png" class="w-12 h-12 " alt="">
                </button>
               
              </div>
            </div>
          </div>

          <div class="relative w-full h-12">
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12">
                <div class="text-white hover:text-white font-medium  text-base uppercase mr-[14.5rem] md:mr-[16.5rem] transition-all duration-1000 w-[12rem] text-right focus-in-expand-fwd">hex.bsry</div>
              </div>
            </div>
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12 ">
                <button on:click="{()=> {openInNewTab("https://www.instagram.com/hex.bsry/")}}" class="relative w-12 h-full transition-all duration-700 hover:-translate-y-2 hover:scale-125 focus:opacity-25">
                  <img src="./img/media-logo-instragram.png" class="absolute top-0 right-0 w-12 h-12 hover:animate-ping hover:blur-[1px] " alt="">
                  <img src="./img/media-logo-instragram.png" class="w-12 h-12 " alt="">
                </button>
               
              </div>
            </div>
          </div>

          <div class="relative w-full h-12">
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12">
                <div class="text-white hover:text-white font-medium text-base uppercase ml-[14.5rem] md:ml-[16.5rem] transition-all duration-1000 w-[12rem] text-left focus-in-expand-fwd">error.bus</div>
              </div>
            </div>
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12 ">
                <button on:click="{()=> {openInNewTab("https://www.facebook.com/error.bus")}}" class="relative w-12 h-full transition-all duration-700 hover:-translate-y-2 hover:scale-125 focus:opacity-25">
                  <img src="./img/media-logo-facebook.png" class="absolute top-0 right-0 w-12 h-12 hover:animate-ping hover:blur-[1px] " alt="">
                  <img src="./img/media-logo-facebook.png" class="w-12 h-12 " alt="">
                </button>
               
              </div>
            </div>
          </div>

          <div class="relative w-full h-12">
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12">
                <div class="text-white hover:text-white font-medium text-base uppercase mr-[14.5rem] md:mr-[16.5rem] transition-all duration-1000 w-[12rem] text-right focus-in-expand-fwd">errorismx</div>
              </div>
            </div>
            <div class="absolute w-full h-full ">
              <div class="flex items-center justify-center w-full h-12 ">
                <button on:click="{()=> {openInNewTab("https://github.com/Errorismx")}}" class="relative w-12 h-full transition-all duration-700 hover:-translate-y-2 hover:scale-125 focus:opacity-25">
                  <img src="./img/media-logo-github.png" class="absolute top-0 right-0 w-12 h-12 hover:animate-ping hover:blur-[1px] " alt="">
                  <img src="./img/media-logo-github.png" class="w-12 h-12 " alt="">
                </button>
               
              </div>
            </div>
          </div>

          

          
         

        </div>
      </div>

    </div>
    <div class="relative order-3 xl:col-span-2 h-[12.1875rem] mt-[-9.5rem] md:mt-[-17.5rem] md:left-[20rem] sm:left-[20rem] lg:w-[60vw] sm:w-[45vw] left-[17rem] w-[25vw] md:w-[40vw] overflow-hidden xl:w-[70vw] ">
      <div class="absolute  w-[89.3125rem] h-[12.1875rem] ">
        <svg  viewBox="0 0 1429 195" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M16 100.804C78.8333 38.304 242 -49.196 392 100.804C579.5 288.304 812 125.304 841.5 100.804C871 76.304 1044.5 -104.196 1249.5 100.804C1413.5 264.804 1538.83 169.137 1581 100.804" stroke="#794188" stroke-width="7"/>
          <path d="M16 100.804C78.8333 38.304 242 -49.196 392 100.804C579.5 288.304 812 125.304 841.5 100.804C871 76.304 1044.5 -104.196 1249.5 100.804C1413.5 264.804 1538.83 169.137 1581 100.804" stroke="#353B4B"/>
          <rect x="1.41374" y="102.937" width="19.6417" height="19.6417" transform="rotate(-43.5098 1.41374 102.937)" fill="#15171E" stroke="#353B4B" stroke-width="2"/>
          <g clip-path="url(#clip0_61_68)">
          <g filter="url(#filter0_d_61_68)">
          <path d="M33.8027 131.925L42.9632 126.687L46.6103 133.038L50.6563 118.046L35.6787 113.947L39.3338 120.339L30.191 125.582L26.995 127.41L23.3447 121L19.2537 136.018L34.2537 140.104L30.6292 133.739L33.8027 131.925Z" fill="white"/>
          <path d="M33.6944 129.881L43.6474 124.175L46.0027 128.294L48.4055 119.333L39.4775 116.882L41.8456 121.024L31.8925 126.73L26.3155 129.904L23.9474 125.763L21.5044 134.731L30.4726 137.174L28.1174 133.055L33.6944 129.881Z" fill="black"/>
          </g>
          </g>
          <defs>
          <filter id="filter0_d_61_68" x="15.9537" y="112.481" width="38.0026" height="32.7568" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"/>
          <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
          <feOffset dy="1.83333"/>
          <feGaussianBlur stdDeviation="1.65"/>
          <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.65 0"/>
          <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_61_68"/>
          <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_61_68" result="shape"/>
          </filter>
          <clipPath id="clip0_61_68">
          <rect width="44" height="44" fill="white" transform="translate(8 142.453) rotate(-74.7618)"/>
          </clipPath>
          </defs>
          </svg>
          
      </div>

    </div>
    <div class=" relative h-[12rem] md:h-[45rem]  xl:h-[50rem] order-last mt-0">
      <img src="./img/my-skill.png" class="scale-75 xl:scale-100 " alt="">
    </div>
    <div class=" relative h-[50rem]  order-last sm:mt-[15rem] mt-[5rem] xl:mt-0">
      <div class="flex justify-center h-full scale-50 md:scale-100">
        <div class="relative  w-[1rem] h-full rotate-90 mt-[-2rem]">
          <div class="flex items-center justify-end text-[#C8C8C8] mt-[24rem]  ">
            <p class="  text-[1.25rem] rotate-180  pl-4 ">CONTRACT&nbsp;ME</p>
            <div class="px-[6.625rem] h-[1px] bg-[#C8C8C8]"></div>
          </div>
        </div>
        
        <div class="ml-[1.875rem] w-[30.375rem]">
          <div class="text-[2.5rem] text-white font-noto font-bold">Who I Am?</div>
          <div class="w-full text-[#B0B0B0] text-[1.25rem] font-noto font-light" style="
          letter-spacing: 1px;
          line-height: 25px;

          ">
            <p>I’m a Fullstack Developer who lived in Thailand but actually I need to learn more about this. I have a serious passion for UI effects, UI design and game mechanic. 
              <br><br>
              Well-organised person, problem solver, im just a college student who like do some coding hobbies to make money. Fan of video games and Netflix series.
              <br><br>
              Interested in the entire frontend and game spectrum and working on ambitious projects with <span class="underline decoration-slate-50 ">positive people</span> .
              </p>
          </div>6.25

          <!-- Timeline Section -->
          <!-- 1 -->
          <div class=" w-[30.375rem] h-[6.25rem] rounded-[0.34375rem] flex  items-center " style="
          background-image: url(../img/timeline-bg-1.png); background-size: cover;
          ">
          <div class="h-full w-[17.1875rem] ">
            <div class="w-full h-[4.9375rem] flex  items-center "style="
            backdrop-filter: blur(22.3087px);
            border-radius: 5.36865px 24.3455px 24.3455px 24.3455px;
            ">
            <div class="w-[13rem] ">
              <div class="text-[0.875rem] text-white font-bold pl-6 font-noto">I was a student at</div>
          <div class="text-[0.625rem] text-white font-light pl-6 font-noto">Santichon Islamic School</div>
            </div>
          
          <div class="w-12 h-12"><img src="./img/timeline-icon-1.png" alt=""></div>
          </div>
          </div>
          <div class="w-[12.125rem] text-right text-white text-base font-bold font-noto">2016-2019</div>
        </div>
        <!-- 2 -->
        <div class="w-[30.375rem] h-[6.25rem] rounded-[0.34375rem] flex  items-center mt-[20px]" style="
        background-image: url(../img/timeline-bg-2.png); background-size: cover;
        ">
        <div class="h-full w-[17.1875rem] ">
          <div class="w-full h-[4.9375rem] flex  items-center "style="
          backdrop-filter: blur(22.3087px);
          border-radius: 5.36865px 24.3455px 24.3455px 24.3455px;
          ">
          <div class="w-[13rem] ">
            <div class="text-[0.875rem] text-white font-bold pl-6 font-noto">I was a student at</div>
        <div class="text-[0.625rem] text-white font-light pl-6 font-noto">International Islamic School Malaysia</div>
          </div>
        
        <div class="w-12 h-12"><img src="./img/timeline-icon-2.png" alt=""></div>
        </div>
        </div>
        <div class="w-[12.125rem] text-right text-white text-base font-bold font-noto">2019-2020</div>
      </div>
        <!-- 3 -->
        <div class="w-[30.375rem] h-[6.25rem] rounded-[0.34375rem] flex  items-center mt-[20px]" style="
        background-image: url(../img/timeline-bg-3.png); background-size: cover;
        ">
        <div class="h-full w-[17.1875rem] ">
          <div class="w-full h-[4.9375rem] flex  items-center "style="
          backdrop-filter: blur(22.3087px);
          border-radius: 5.36865px 24.3455px 24.3455px 24.3455px;
          ">
          <div class="w-[13rem] ">
            <div class="text-[0.875rem] text-white font-bold pl-6 font-noto">I'm currently studying at</div>
        <div class="text-[0.625rem] text-white font-light pl-6 font-noto">Assumption university</div>
          </div>
        
        <div class="w-12 h-12"><img src="./img/timeline-icon-3.png" alt=""></div>
        </div>
        </div>
        <div class="w-[12.125rem] text-right text-white text-base font-bold font-noto">2021- now</div>
      </div>





        </div>

       


      </div>
   
    </div>
        <!-- D*CODE SECTION -->
        <div class="h-[23.0625rem] 2xl:h-[11.0625rem] xl:h-[13.0625rem]     xl:col-span-2 order-last grid grid-cols-1 xl:grid-cols-4 gap-x-0 gap-y-1  md:gap-y-10 mt-[-13rem] md:mt-[5rem] z-10">
          <div class="flex items-center justify-center xl:justify-end xl:col-span-1 xl:pr-8">
            <img src="./img/dcode-logo.png" class="md:scale-100 scale-75 w-[11.0625rem] h-[11.0625rem]" alt="">
          </div> 
          <div class="xl:col-span-3 ">
            <div class="px-10 text-base font-bold text-center text-white md:px-20 md:text-2xl xl:pt-4 xl:text-3xl xl:px-0 xl:text-left font-noto">Why I want to be a part of the <span style="background: linear-gradient(90.01deg, #CCCB5D 0.01%, #75BD9D 50%, #20B0DB 99.99%);
              -webkit-background-clip: text;
              -webkit-text-fill-color: transparent;
              background-clip: text;
              text-fill-color: transparent;">D*CODE research laboratory</span>  member</div>
              <div class="text-[#B7B7B7] xl:text-xl  text-xs  md:text-sm font-noto pt-4  text-center px-10 xl:px-0  xl:text-left">
                Because I believe that it will bring me to alot of oppurtunity and it is my dream for a long time that I want to work with
    people who know about computer stuff since I am a self-taught so I have no friend to write code or doing project with and I know at the first place that this lab can fullfill my dream.
              </div>
        </div>
      
      </div>
      
      <div class="flex items-center justify-center order-last w-full h-24 sm:h-44 md:mt-0 xl:col-span-2 xl:h-56">
        <img src="./img/moji_4.png" class="w-[8.75rem] md:w-[15.75rem] h-[8.75rem] md:h-[15.75rem]" alt="">
      </div>

      <div class="flex items-center justify-center order-last w-full h-48 py-24 md:pt-24 md:mt-0 xl:col-span-2">
        <div class="text-3xl text-white sm:text-6xl md:text-6xl font-noto">PROJECT GALLERY</div>
        
      </div>
      <div class="grid justify-center order-last w-full grid-cols-1 xl:col-span-2 ">
       
          <div class="grid grid-cols-1 pb-24 2xl:grid-cols-2 gap-y-8">
              <div class="flex items-center justify-center w-full h-full 2xl:justify-start ">
                <img src="./img/vtr-launcher.gif" alt="">
              </div>
              <div class="flex flex-col justify-center h-full text-center 2xl:text-left font-noto">
                <div class="text-base font-bold text-white md:text-2xl ">VTR-LAUNCHER</div>
                <div class="text-xs  md:text-sm  text-[#AFAFAF] mt-2 px-10 2xl:px-0 ">Game launcher for fivem which require discord Login and provide some basic anticheat using SOCKET to check the realtime heartbeat.</div>
                <div class="mt-4 text-sm font-bold text-white md:text-xl">TECH STACK</div>
                <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#32498C] text-sm md:text-base font-medium">CLIENTSIDE :</span> Nodejs, Electronjs, Passportjs for discord-Auth0, Socketio-client, Express, Sveltejs, Tailwindcss.</div>
                <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#BD3984] text-sm md:text-base font-medium">SERVERSIDE :</span> Nodejs, Passportjs for discord-Auth0, Socketio-server, Axios, Express.</div>
              </div>
          </div>

          <div class="grid grid-cols-1 pb-24 2xl:grid-cols-2 gap-y-8">
           <div class="h-[2px] bg-[#222222] w-full col-span-2"></div>
          </div>

          <div class="grid grid-cols-1 pb-24 2xl:grid-cols-2 gap-y-8">
           
            <div class="flex flex-col justify-center order-2 h-full text-center 2xl:text-left font-noto 2xl:order-1">
              <div class="text-base font-bold text-white md:text-2xl ">GACHAPONG</div>
              <div class="text-xs  md:text-sm  text-[#AFAFAF] mt-2 px-10 2xl:px-0 ">Gachapong script for fivem which players can donate the point and open loot boxes. inpiration from pubg. Moreover, it provide anticheat for hacking point which check every purchase in serverside.</div>
              <div class="mt-4 text-sm font-bold text-white md:text-xl">TECH STACK</div>
              <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#32498C] text-sm md:text-base font-medium">CLIENTSIDE :</span> Lua, Sveltejs, Postcss, Typescript, Tailwindcss, Axiosjs.</div>
              <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#BD3984] text-sm md:text-base font-medium">SERVERSIDE :</span> Lua, Mongodb.</div>
            </div>
            <div class="flex items-center justify-center order-1 w-full h-full 2xl:justify-end 2xl:order-2">
              <img src="./img/open-loot-box.gif" alt="">
            </div>
        </div>

        <div class="grid grid-cols-1 pb-24 2xl:grid-cols-2 gap-y-8">
          <div class="h-[2px] bg-[#222222] w-full col-span-2"></div>
         </div>


         <div class="grid grid-cols-1 pb-24 2xl:grid-cols-2 gap-y-8">
          <div class="flex items-center justify-center w-full h-full ">
            <img src="./img/skincreator.gif" alt="">
          </div>
          <div class="flex flex-col justify-center h-full text-center 2xl:text-left font-noto">
            <div class="text-base font-bold text-white md:text-2xl ">SKINCREATOR</div>
            <div class="mt-2 text-sm font-light text-white font-not">This is my first project that I’m start using Nodejs</div>
            <div class="text-xs  md:text-sm  text-[#AFAFAF] mt-2 px-10 2xl:px-0 ">Skin creator script that link in-Game mouse Event so players can
              rotate their character model via hold their mouse and move to the direction that they want. For fivem only.</div>
              <div class="mt-4 text-sm font-bold text-white md:text-xl">Problem</div>
              <div class="text-xs  md:text-sm  text-[#AFAFAF] mt-2 px-10 2xl:px-0 ">I just start using nodejs for web so as you can see when it select the skin it will show the check icon but the problem is the whole
                element drop down.</div>
              <div class="mt-4 text-sm font-bold text-white md:text-xl">TECH STACK</div>
            <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#32498C] text-sm md:text-base font-medium">CLIENTSIDE :</span> Lua, Sveltejs, Javascript, Axiosjs.</div>
            <div class="mt-2 text-xs text-[#B7B7B7] px-10 xl:px-0"><span class="text-[#BD3984] text-sm md:text-base font-medium">SERVERSIDE :</span> Lua, Mongodb.</div>
          </div>
      </div>
      
      <div class="grid grid-cols-1 2xl:grid-cols-2 gap-y-8">
        <div class="h-[2px] bg-[#222222] w-full col-span-2">
          
        </div>
       </div>
     
       <div class=" relative h-[3rem] ">
        <div class="w-full h-full flex items-center justify-center text-[#FFFFFF80] ">
          <div class="flex items-center justify-start text-xs font-noto ">PORTFOLIO BY NITIPOOM A. - LATEST UPDATED 17/9/2022</div>
      
        </div>
       </div>

     
          
      </div>

  </div>
</main>

<style lang="postcss">
   
  


</style>
