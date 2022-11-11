# JavaScript Array
JavaScript array is an object that represents a collection of similar type of elements.

There are 3 ways to construct array in JavaScript

1. By array literal
2. By creating instance of Array directly (using new keyword)
3. By using an Array constructor (using new keyword)

## 1) JavaScript array literal
The syntax of creating array using array literal is given below:

var arrayname=[value1,value2.....valueN];  

As you can see, values are contained inside [ ] and separated by , (comma).

Let's see the simple example of creating and using array in JavaScript.

<script>  

var emp=["Sonoo","Vimal","Ratan"];  

for (i=0;i<emp.length;i++){  

document.write(emp[i] + "<br/>");  

}  

</script>  

  
 The .length property returns the length of an array.

Output of the above example

Sonoo
Vimal
Ratan
  
## 2) JavaScript Array directly (new keyword)
The syntax of creating array directly is given below:

var arrayname=new Array();  

Here, new keyword is used to create instance of array.

<script>  

var i;  

var emp = new Array();  

emp[0] = "Arun";  

emp[1] = "Varun";  

emp[2] = "John";  
  
for (i=0;i<emp.length;i++){  

document.write(emp[i] + "<br>");  

}  

</script>

## 3) JavaScript array constructor (new keyword)
Here, you need to create instance of array by passing arguments in constructor so that we don't have to provide value explicitly.

The example of creating object by array constructor is given below.

<script>  

var emp=new Array("Jai","Vijay","Smith");  

for (i=0;i<emp.length;i++){  

document.write(emp[i] + "<br>");  

}  

</script>  
  
  Output of the above example

Jai
Vijay
Smith
  
  
