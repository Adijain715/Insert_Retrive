# Insert_Retrive
import java.util.*; 

// class to represent the required data structure 
class MyDS 
{ 
ArrayList<Integer> arr; // A resizable array 

// A hash where keys are array elements and vlaues are 
// indexes in arr[] 
HashMap<Integer, Integer> hash; 

// Constructor
public MyDS() 
{ 
	arr = new ArrayList<Integer>(); 
	hash = new HashMap<Integer, Integer>(); 
} 

// data structure 
void add(int x) 
{ 
	if (hash.get(x) != null) 
		return; 

	// Else put element at the end of arr[] 
	
  int s = arr.size(); 
	arr.add(x); 

	// And put in hash also 
	
  hash.put(x, s); 
} 

	// Returns a random element from MyDS 
	
  int getRandom() 
	{ 
	// Find a random index from 0 to size - 1 
	Random rand = new Random(); // Choose a different seed 
	int index = rand.nextInt(arr.size()); 

	// Return element at randomly picked index 

   return arr.get(index); 
	} 

	// Returns index of element if element is present, otherwise null 
	
  Integer search(int x) 
	{ 
	return hash.get(x); 
	} 
} 

// Driver class 
class Main 
{ 
	public static void main (String[] args) 
	{ 
		MyDS ds = new MyDS(); 
		ds.add(10); 
		ds.add(20); 
		ds.add(30); 
		ds.add(40); 
		System.out.println(ds.search(30)); 
		ds.add(50); 
		System.out.println(ds.search(50)); 
		System.out.println(ds.getRandom()); 
	} 
} 


<!DOCTYPE html>
<html>

<head>

<script> 

var customerName = prompt("Please enter your name", "");
if (customerName!= null) {
    document.getElementById("welcome").innerHTML =
    "Hello " + customerName + "! How are you today?";
}
</script>

</head>

<body>

<div id="welcome">My First JavaScript code.</div>

</body>
</html>

<html>
    <head>
    <script type="text/javascript" src="jquery.js"></script>
    <script type="text/javascript">
        $(document).ready(function() {
            //$(".box:contains(latin)").wrap("<div></div>");
            // $("div:contains('roots')").css("text-decoration", "underline");
            //$("div:contains('John')").css("text-decoration", "underline");
            $("div:contains('John')").addClass('test');

        });
    </script>
<style type="text/css">
  .test{color:red;}
  .list{float:left; width:80px;}
  .list li{list-style-type:none;}
  input{text-transform:uppercase;}
</style>
    </head>
<body>
<div>
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in John a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard John John John John John McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over John 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance.
 </div>
</body>
</html>
