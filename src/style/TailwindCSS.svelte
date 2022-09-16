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


</style>
