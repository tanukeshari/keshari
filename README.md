<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
  <title>Item Lister</title>
</head>
<body>
  <header id="main-header" class="bg-success text-white p-4 mb-3">
    <div class="container">
      <div class="row">
      <h1 id="header-title">Item Lister</h1>
      </div>
       <div class="col-md-6 align-self-center"><input type="text" class ="form-control" id="filter" placeholder="search item......"></div>
    </div> 
  </div>
  </header>
  <div class="container">
   <div id="main" class="card card-body">
    <h2 class="title">Add Items</h2>
    <form  id="addForm" class="form-inline mb-3">
      <input type="text" class="form-control mr-2"
      id="items">
      <input type="submit" class="form-control mr-1" value="Submit">
    </form>
    <h2 class="title">Items</h2>
    <ul id="items" class="list-group">
      <li class="list-group-item">Item 1 </li>
      <li class="list-group-item">Item 2 </li>
      <li class="list-group-item">Item 3 </li>
      <li class="list-group-item">Item 4 </li>
    </ul>
   </div>
  </div>
<script>
// TRAVWESING THE DOM//
var itemList = document.querySelector('#items');
// parentNode
console.log(itemList.parentNode);
itemList.parentNode.style.backgroundColor='#f4f4f4';
console.log(itemList.parentNode.parentNode.parentNode);


// parentElement
console.log(itemList.parentElement);
itemList.parentElement.style.backgroundColor='#f4f4f4';
console.log(itemList.parentElement.parentElement.parentElement);

// childNodes
console.log(itemList.childNodes);

console.log(itemList.children);
console.log(itemList.children[1]);
itemList.children.style.backgroundColor='#f4f4f4';

//firstChild
console.log(itemList.firstChild);

//firstElementChild
console.log(itemList.firstElementChild);
itemsList.firstElementChild.textContent ="hello 1";

//lastChild
console.log(itemList.lastChild);

//lastElementChild
console.log(itemList.lastElementChild);
itemsList.lastElementChild.textContent ='hello 4';
   

// nextsibiling
console.log(itemList.nextSibling);

//nextElementsibiling
console.log(itemList. nextElementsibiling);
itemsList.nextElementsibiling.textContent ='hello 4';


// previoussibiling
console.log(itemList.previousSibling);

//previousElementsibiling
console.log(itemList. previousElementsibiling);
itemsList.previousElementsibiling.style.color='green';

// create a DIV
 
  var newDiv= document.createElement('div');
  // add class
  newDiv.className=' hello';

   // add id

    newDiv.id =' hello1';

     // add attribute

     newDiv.setAttribute('title', ' hello div');

     // create text Node

     var newDivText=document.createTextNode('hello world');

     // add text to div

      newDiv.appendChild(newDivText);

      var content= document.querySelector('header .container');
      var h1=document.querySelector('header h1');
      console.log(newDiv);

       newDiv.style.fontsize='30px';
       container.insertBefore(newDiv, h1);
</script>
</body>
</html>
