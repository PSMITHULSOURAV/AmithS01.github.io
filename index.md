<html>
 <head>
  
 </head>
 <body>
<h1 class="header" align="center">Enter The Numbers Below</h1>
<input id="in1" placeholder="Enter The First Number"> <input id="in2" placeholder="Enter The Second Number">
<br/><br/>
<button class="but1" onclick="sup()">Find The HCF</button>
<br/><br/>
<div class="one" align="center"><span id="clas"></span></div>
<p id="par1" align="center">Thank you for using this calculator, this is one of my projects , hope you like it.</p>
<br/>
<br/>
<div id="sub1">
<p id="intro">Now that you've used the calculator, let me tell you about me.</p>
<ul id="about">
<h3>This is how I spend most of my time</h3>
<br/>
<li>School <br/>
<progress id="bar1" max="24" min="0" value="5"></progress>
</li>
<li>Extra Classes <br/>
<progress id="bar2" max="24" min="0" value="6">
</li>
<li>Hacking<br/>
<progress id="bar3" max="24" min="0" value="4">
</li>
<li>Eating(Breakfast, Lunch, Snacks & Dinner) <br/>
<progress id="bar4" max="24" min="0" value="4">
</li>
<li>Daydreaming <br/>
<progress id="bar5" max="24" min="0" value="10">
</li>
<li>Sleeping <br/>
<progress id="bar6" max="24" min="0" value="14">
</li>
<li>Youtube<br/>
<progress max="24" min="0" value="5">
  </li>
 </ul>
 </body>
  </html>

<script>
var ans1=0;
var swt1=0;


sup();

function sup(){
var testno1=document.getElementById("in1").value;
var testno2=document.getElementById("in2").value;
if(testno1/testno2 < 1){
var no1=testno2;
var no2=testno1;
} else{
var no1=testno1;
var no2=testno2;
}
var rem1=no1%no2;
var rem2=no2%rem1;
var rem3=rem1%rem2;
var rem4=rem2%rem3;
var rem5=rem3%rem4;
var rem6=rem4%rem5;
var rem7=rem5%rem6;
var rem8=rem6%rem7;
var rem9=rem7%rem8;
var rem10=rem8%rem9;
var rem11=rem9%rem10;
var rem12=rem10%rem11;
var rem13=rem11%rem12;
var rem14=rem12%rem13;
var rem15=rem13%rem14;
var rem16=rem14%rem15;
var rem17=rem15%rem16;
var rem18=rem16%rem17;
var rem19=rem17%rem18;
var rem20=rem18%rem19;

if(rem1==0){
ans1=no2;
}
if(rem2==0){
ans1=rem1;
}
if(rem3==0){
ans1=rem2;
}
if(rem4==0){
ans1=rem3;
}
if(rem5==0){
ans1=rem4;
}
if(rem6==0){
ans1=rem5;
}
if(rem7==0){
ans1=rem6;
}
if(rem8==0){
ans1=rem7;
}
if(rem9==0){
ans1=rem8;
}
if(rem10==0){
ans1=rem9;
}
if(rem11==0){
ans1=rem10;
}
if(rem12==0){
ans1=rem11;
}
if(rem13==0){
ans1=rem12;
}
if(rem14==0){
ans1=rem13;
}
if(rem15==0){
ans1=rem14;
}
if(rem16==0){
ans1=rem15;
}
if(rem17==0){
ans1=rem16;
}
if(rem18==0){
ans1=rem17;
}
if(rem19==0){
ans1=rem18;
}
if(rem20==0){
ans1=rem19;
}


var display1= document.getElementById("clas");
display1.innerHTML= "The HCF of "+testno1+" and "+ testno2 +" "+ "is = "+ans1;
}

 
</script> 
<style>
div.one{
 font-weight:bolder;
 font-size:30px;
}

body{
background-color:#efefef

}

h1.header{
font-color:"black";
padding:10px;
border-radius:12px


}

#par1{
font-weight:bold;
font-size:large;
font-style:italic;
padding:8px;
border-radius:12px;
background-color:#fff;
}

intro{
text-indenting:13px;
font-weight:bold;
font-size:large;
}

.clas{
font-weight:bolder;
}

.one{
padding:7px;
border-radius:12px;
background-color:#fff;
background-image:url("")

}

div#sub1{
padding:80px;
background-color:#ffffff;
border-radius:25px;
}
#in2{
width:300px;
height:30px;
align:"right";
}

#in1{
width:300px;
height:30px;
align:"right";
}
button{
width:200px;
height:30px;
font-weight:bolder;
background-color:#ff9c52;
border-radius:14px;

}

</style>



 
