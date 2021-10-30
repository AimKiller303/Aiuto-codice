<script type="text/javascript"> 
document.addEventListener('DOMContentLoaded', () => { 
 document.querySelector(".dropbtn").addEventListener('click', (el) => document.querySelector('.myDropdown').classList.toggle('show')) 
 
 
window.onclick = function(event) { 
 if (!event.target.matches('.dropbtn')) { 
 var dropdowns = document.getElementsByClassName("dropdown-content"); 
 var i; 
 for (i = 0; i < dropdowns.length; i++) { 
 var openDropdown = dropdowns[i]; 
 if (openDropdown.classList.contains('show')) { 
 openDropdown.classList.remove('show'); 
 } 
 } 
 } 
} 
}); 
</script> 
  
  <div class="myDropdown">
 <button class="dropbtn">Dropdown</button>
 <div class="myDropdown">
 <a class="dropdown-content">Home</a>
 <a href="#about">About</a>
 <a href="#contact">Contact</a>
 </div>
 </div>
