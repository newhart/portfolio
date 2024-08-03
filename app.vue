<template>
  <div class="bg-[url('~/assets/image/main.jpg')] bg-cover bg-center relative min-h-screen w-full h-full">
    <div class="flex flex-col items-center justify-center h-full text-white absolute left-[35%] leading-tight">
      <h1 class="text-8xl font-bold font-oswald leading-tight">
        <span id="heading1"></span><span id="cursor" class="cursor">|</span>
      </h1>
      <h2 class="text-6xl font-oswald leading-tight">
        <span id="heading2"></span>
      </h2>
      <h2 class="text-6xl font-oswald leading-tight">
        <span id="heading3"></span>
      </h2>
      <p class="text-xl mt-4 text-[#6c305e] italic">Développeur Full-Stack</p>
    </div>
    <div class="absolute bottom-10 right-28">
      <div class="flex">
        <a href="" class="text-xl font-bold text-white">Apprendre plus <br> a mon sujet ? </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      currentTextIndex: 0,
      currentCharIndex: 0,
    };
  },
  mounted() {
    this.typeWriterEffect();
  },
  methods: {
    typeWriterEffect() {
      const texts = ["PORTFOLIO", "Haritiana", "RANDRIA"];
      const speed = 200; // typing speed in milliseconds

      const type = () => {
        if (this.currentCharIndex < texts[this.currentTextIndex].length) {
          document.getElementById(`heading${this.currentTextIndex + 1}`).innerHTML += texts[this.currentTextIndex].charAt(this.currentCharIndex);
          this.currentCharIndex++;
          this.moveCursor();
          setTimeout(type, speed);
        } else {
          this.currentTextIndex++;
          this.currentCharIndex = 0;
          if (this.currentTextIndex < texts.length) {
            setTimeout(type, speed);
          }
        }
      };

      type();
    },
    moveCursor() {
      const cursor = document.getElementById('cursor');
      const currentHeading = document.getElementById(`heading${this.currentTextIndex + 1}`);
      if (currentHeading) {
        currentHeading.appendChild(cursor);
      }
    }
  }
};
</script>

<style scoped>
.cursor {
  display: inline-block;
  margin-left: 5px;
  animation: blink 1s step-end infinite;
  position: relative;
  top: 0;
}

@keyframes blink {

  from,
  to {
    opacity: 1;
  }

  50% {
    opacity: 0;
  }
}
</style>