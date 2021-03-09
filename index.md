
<html>
 <body>

   <div id="accordion">
   <h3> What is Data Science? </h3>
     <div>Data science is ... </div>
     <h3>What to study for Data Science</h3>
     <div>Learning data science is... </div>
    <h3>Careers in Data Science</h3>
     <div>There are many careers in data science... </div>
  <h3> Links </h3>
  <ul>
 <li><a href="https://www.bls.gov/oes/current/oes152098.htm">U.S Bureau of Labor Statistics--Data Scientists</a>
   <li><a href="https://en.wikipedia.org/wiki/Data_science">Wikipedia-- Data Science</a>
  </ul>
   </div> 
   
   <script src="https://code.jquery.com/jquery-3.6.0.js" integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js" integrity="sha256-T0Vest3yCU7pafRw9r+settMBX6JkKN06dqBnpQ8d30=" crossorigin="anonymous"></script>
<script>
 $(document).ready( () => {
   $("#accordion").accordion( {
     event: "click",
     heightStyle:"content",
     collapsible: true
 
 } );
 
 });
 
 </script>
   
  </body>
</html>

