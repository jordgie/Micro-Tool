<template>
  <div>
    <div id="app">
      <button id="toggleNoteButton" class="image-button">
        <img src="/assets/tapme.png" alt="Tap Me">
      </button>

      <div class="group-section hidden">
        <h3>About Us</h3>
        <p class="noteP">
          This activity is for the Advanced Web Applications subject. The goal of this project is to create a program that contains micro tools. The developers have created a Length and Mass converter, a flexbox tool, and a password generator.
        </p>
        <h4>Developers:</h4>
        <ul class="list-styling">
          <li>Jordan Gutlay</li>
          <li>Steven Gueta</li>
          <li>Elsa Macasinag</li>
          <li>Mark Gile</li>
          <!-- Add more members as needed -->
        </ul>
        <h4>Professor:</h4>
        <ul class="list-styling">
          <li>Anthony Gacis, MIT</li>
        </ul>
      </div>

      <div class="parent-container">
        <div class="tool-header">
          <div class="tool-title"><h1>Micro Tools</h1></div>
          <div class="tools-image">
            <img src="assets/clock1.png" alt="">
            <img src="assets/iron.png" alt="">
            <img src="assets/magnifier.png" alt="">
            <img src="assets/magnet.png" alt="">
            <img src="assets/color.png" alt="">
          </div>
        </div>

        <div class="container">
          <div class="left">
            <div class="button-container">
              <button id="converterButton">Length and Mass Converter</button>
            </div>
            <div class="button-container">
              <button id="flexboxButton">Flexbox Generator</button>
            </div>
            <div class="button-container">
              <button id="passwordButton">Password Generator</button>
            </div>
          </div>

          <div class="right" id="screen">
            <h2 class="tool-inst">Select a tool</h2>
            <img src="assets/tools1.png" alt="">
            <!-- Content will appear here -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<!-- <script>
export default {
  name: 'App',
};
</script>

<style scoped>
/* Add your CSS styles here */
</style> -->
