<!-- Get input from user and type it out -->
<!-- <input type="text" [(ngModel)]="name" />
<p>{{ name }}</p> -->


setTimeout() delays when the function will be run in milliseconds. 
setTimeout(() => {function to be run}, 2000)



DONT MIX THESE TWO
<!-- String interpolation -->
<p>{{ allowNewServer }}</p>

<!-- Property binding -->
<p [innerText]="allowNewServer"></p>