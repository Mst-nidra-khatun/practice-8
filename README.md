# practice-8

At first, i create a basic HTML/CSS file.
On HTML file 
I create a div with the class name "eye".
Then, I create div with the class name "circle".
Then, I create 4 div with the class name "bar".
Then, I create 4 div with the class name "rectanguler".
On CSS file
I style the .eye {
    width: 190px;
    height: 190px;
    position: absolute;
    border-radius: 50%;
    background-color: #d5edfc;
    box-sizing: border-box;
    border: 30px solid #06487a;
    top: 230px;
    left: 200px;
  }
  
  
.circle {
    width: 60px;
    height: 60px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
    background-color: #06487a;
  }

  .bar {
    position: absolute;
    width: 30px;
    height: 300px;
    background-color: #06487a;
    transform: rotate(90deg);
    border-radius: 50px;
    left: 50px;
    top: -100px;
  }
  .rectanguler {
    position: absolute;
    width: 200px;
    height: 200px;
    background-color: white;
    top: -165px;
    left: -35px;
  }

