<style global lang="postcss">
  @import 'tailwindcss/base';
  @import 'tailwindcss/components';
  @import 'tailwindcss/utilities';

  html,
  body {
    @apply bg-black;
    margin: 0;
  }

  .font-noto {
    font-family: 'Noto Sans', sans-serif;
  }
  .font-jetbrains-mono {
    font-family: 'JetBrains Mono', monospace;

  }
  /* width */
::-webkit-scrollbar {
  width: 8px;
}

/* Track */
::-webkit-scrollbar-track {
  background: rgba(0, 0, 0, 0);
}

/* Handle */
::-webkit-scrollbar-thumb {
  border: 1px solid #3C3C3C;
border-radius: 999px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  border: 1px solid #595959;
border-radius: 999px;
}


 

.chatbox-skewY-v1 {
  -webkit-animation: chatbox-skewY-v1 4s linear infinite both;

}
.chatbox-skewY-v2 {
  -webkit-animation: chatbox-skewY-v2 4s linear infinite both;

}
.chatbox-skewY-v3 {
  -webkit-animation: chatbox-skewY-v3 4s linear infinite both;

}

@-webkit-keyframes chatbox-skewY-v1 {
  0% {
    -webkit-transform: skewY(-3deg);
            transform: skewY(-3deg);
  }
  50% {
    -webkit-transform: skewY(-1deg);
            transform: skewY(-1deg);
  }
  100% {
    -webkit-transform: skewY(-3deg);
            transform: skewY(-3deg);
  }
}

@-webkit-keyframes chatbox-skewY-v2 {
  0% {
    -webkit-transform: skewY(3deg);
            transform: skewY(3deg);
  }
  50% {
    -webkit-transform: skewY(2deg);
            transform: skewY(2deg);
  }
  100% {
    -webkit-transform: skewY(3deg);
            transform: skewY(3deg);
  }
}
@-webkit-keyframes chatbox-skewY-v3 {
  0% {
            
    -webkit-transform: skewY(-4deg);
            transform: skewY(-4deg);
           
  }
  50% {
         
    -webkit-transform: skewY(-2deg);
            transform: skewY(-2deg);
  }
  100% {
           
    -webkit-transform: skewY(-4deg);
            transform: skewY(-4deg);
  }
}

.focus-in-expand-fwd{-webkit-animation:focus-in-expand-fwd .8s cubic-bezier(.25,.46,.45,.94);animation:focus-in-expand-fwd .8s cubic-bezier(.25,.46,.45,.94)}
 @-webkit-keyframes focus-in-expand-fwd{0%{letter-spacing:-.5em;-webkit-transform:translateZ(-800px);transform:translateZ(-800px);-webkit-filter:blur(12px);filter:blur(12px);opacity:0}100%{-webkit-transform:translateZ(0);transform:translateZ(0);-webkit-filter:blur(0);filter:blur(0);opacity:1}}@keyframes focus-in-expand-fwd{0%{letter-spacing:-.5em;-webkit-transform:translateZ(-800px);transform:translateZ(-800px);-webkit-filter:blur(12px);filter:blur(12px);opacity:0}100%{-webkit-transform:translateZ(0);transform:translateZ(0);-webkit-filter:blur(0);filter:blur(0);opacity:1}}

 .slide-in-elliptic-bottom-fwd{-webkit-animation:slide-in-elliptic-bottom-fwd .7s cubic-bezier(.25,.46,.45,.94);animation:slide-in-elliptic-bottom-fwd .7s cubic-bezier(.25,.46,.45,.94)}
 @-webkit-keyframes slide-in-elliptic-bottom-fwd{0%{-webkit-transform:translateY(600px) rotateX(30deg) scale(0);transform:translateY(600px) rotateX(30deg) scale(0);-webkit-transform-origin:50% 100%;transform-origin:50% 100%;opacity:0}100%{-webkit-transform:translateY(0) rotateX(0) scale(1);transform:translateY(0) rotateX(0) scale(1);-webkit-transform-origin:50% -1400px;transform-origin:50% -1400px;opacity:1}}@keyframes slide-in-elliptic-bottom-fwd{0%{-webkit-transform:translateY(600px) rotateX(30deg) scale(0);transform:translateY(600px) rotateX(30deg) scale(0);-webkit-transform-origin:50% 100%;transform-origin:50% 100%;opacity:0}100%{-webkit-transform:translateY(0) rotateX(0) scale(1);transform:translateY(0) rotateX(0) scale(1);-webkit-transform-origin:50% -1400px;transform-origin:50% -1400px;opacity:1}}
</style>
