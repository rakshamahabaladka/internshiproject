function calculate()
{
var input1=Number(document.getElementById('number1').value);
var input2=Number(document.getElementById('number2').value);
var input3=Number(document.getElementById('number3').value);
var input4=Number(document.getElementById('number4').value);
var input5=Number(document.getElementById('number5').value);
var input6=Number(document.getElementById('number6').value);
var input7=Number(document.getElementById('number7').value);
var input8=Number(document.getElementById('number8').value);

var c1=Number(document.getElementById('credit1').value);
var c2=Number(document.getElementById('credit2').value);
var c3=Number(document.getElementById('credit3').value);
var c4=Number(document.getElementById('credit4').value);
var c5=Number(document.getElementById('credit5').value);
var c6=Number(document.getElementById('credit6').value);
var c7=Number(document.getElementById('credit7').value);
var c8=Number(document.getElementById('credit8').value);
var result=(input1*c1+input2*c2+input3*c3+input4*c4+input5*c5+input6*c6+input7*c7+input8*c8)/(c1+c2+c3+c4+c5+c6+c7+c8);
document.getElementById("result").innerHTML=result;
}