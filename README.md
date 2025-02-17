<h1> Programs that I have completed <img src="https://user-images.githubusercontent.com/72338271/119033984-2c15b400-b9ae-11eb-86db-f82c071bd491.gif" width="50"> </h1>
<p> Pergolas/Awnings/Screens Configurator. Repository private on gitlab. </p>
<p> Plants manager. Mobile application made in 5 people team. My task was to create frontend. We were using React native.
<br> Link to the repository: https://github.com/StartupZmitac/OnlyPlants </p> 
<p> Cinema Management. Web application made in 5 people team. My task was to create frontend of our web application. We were using Angular+Bootstrap 14, .NET Core 6 and Entity Framework. <br> Link to the repository: https://github.com/StartupZmitac/ZMiTACinema</p>
<p> Climb Together. Program created for commercial usage. The point of this program is to track users' progress in climbing and to provide crucial analytical data to gym owners. This data can help to adjust gym's amenities based on clients.</p>
<p> Firm management. Program that can be used to manage a firm. Everything is based on a project pattern called composite - every branch can have other branches below in hierarchy. As administrator You can add branches, alter salaries, add new workers, give promotions etc.  </p>
<p> <img src="https://user-images.githubusercontent.com/72338271/119033660-c32e3c00-b9ad-11eb-9f05-c28a6e213e4b.gif" width="25"> "Darwin". Simple genetic algorithm implementation. Basically this program simulates living cycles of individuals in which they reproduce and in which they also die. Everything depends on the given data by user.</p> 
<p> <img src="https://user-images.githubusercontent.com/72338271/119031640-96792500-b9ab-11eb-8468-c9b593963f02.gif" width="25"> Tic Tac Toe with board's size determined by user and game mode in which user competes with the algorithm </p>
<p> <img src="https://user-images.githubusercontent.com/72338271/119032662-ba893600-b9ac-11eb-90b7-65f585a73ff4.gif" width="25"> Minesweeper with the board size chosen by user. In this project I have implemented the flood fill algorithm.
<p> <img src="https://user-images.githubusercontent.com/72338271/119032169-2b7c1e00-b9ac-11eb-9816-2942dd3f4b9a.gif" width="25"> Shaking Christmas Tree that's size is determined by the user. </p>
<p> Bellman-Ford algorithm. Program that finds the optimal route to chosen vertex and displays the cost with the route in form of a text file. </p>


<h1> <img src="https://user-images.githubusercontent.com/72338271/119033660-c32e3c00-b9ad-11eb-9f05-c28a6e213e4b.gif" width="25"> Program "Darwin" </h1>

<p> Darwin is a program in which genetic algorithm was implemented. The process of this program can be listed as below: <br>
<ul> 
  <li> User provides the program with data, like: 
    <ul>
     <li> Number of k-pairs chosen to reproduce </li>
     <li> Number of p-generations </li>
     <li> Extinction factor that belongs to the interval <0,1> </li>
     <li> Reproduction factor that belongs to the interval <0,1> </li>
     <li> Name of the input file</li>
     <li> Name of the output file</li>
    </ul>
  </li>
  <li> Every inputted parameter is being checked whether it is in correct format or not. If something is wrong a simple instruction pops up. </li>
  <li> Program saves the data from the file in order to operate on it </li>
    <ul>
      <li> The data is stored in this format: <br> <img src="https://user-images.githubusercontent.com/72338271/119059676-1665b600-b9d1-11eb-9021-e213859cab2b.png"> <br> Every sequence of numbers is just a genetic code of a specific individual. 
      </li>
    </ul>
  <li> 2 individuals are chosen from the population and the outcome of their reproduction are two another individuals. <br> More or less it means that the process of crossing-   over is happening. 
  <ul>
    <li> It can be depicted as below: <br> <img src ="https://user-images.githubusercontent.com/72338271/119060582-c2f46780-b9d2-11eb-9c4d-c0341766a3cb.png"> </li>
    <li> This process is repeated k-times </li> 
  </ul>
  </li>
  <li> Every individual is getting assigned a factor of survival. It is calculated using the value of it's genetic code elements. </li>
  <ul>
      <li>This factor determines whether an individual will be extinct, or will it continue to reproduce in further generations, or will it just exist. </li>
  </ul>
  <li> Previous steps (excluding those before reading data from files) are repeated p-times </li>
  <li> Whole population is being saved on a text file that is the final outcome of this program </li>
</ul>





<!--
**mNiedbalski/mNiedbalski** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
