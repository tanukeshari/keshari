<this.table= 'window table';

console.log(window table);



const cleanTable=function(){

console.log(cleaning ${this.table}`)



this.garage={

table:'garage table'

cleanTable(){

console.log(cleaning ${this.table}`)

}

};

this.garage.table;

let johnsRoom={

table: ' johns table'

cleanTable(){

console.log(cleaning${ this.table})

};

console.log(this.johnsRoom.table);

table: 'johns table'

};





class student{

     static count=0; //static variable to call

     

    constructor(name,age,ph_no,marks){

        this.name=name;

        this.age=age;

        this.ph_no=ph_no;

        this.marks=marks;

        student.countStudent();

    }

    static countStudent(){

        

        return(student.count++); //this is how u access static variable

    }

    eligible(){

        if(this.marks >=40){

            console.log(`${this.name} age ${age} is eligible`);

        }

        else if(this.marks<40){

            console.log(`${this.name} age ${age} is not eligible`);

        }

    }







    

}

const Riya=new student('Riya',18,1234,34);

const Hiya=new student('Hiya',15,2345,35);

const Diya=new student('Diya',16,4567,60);

const Siya=new student('Siya',17,7891,70);

const Rooh=new student('Rooh',19,3456,80);

console.log(student.countStudent());

Riya.eligible();

Hiya.eligible();

Diya.eligible();

Siya.eligible();

Rooh.eligible();







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

      <h1 id="header-title">Item Lister <span style="display:none">123</span></h1>

    </div>

  </header>

  <div class="container">

   <div id="main" class="card card-body">

    <h2 class="title">Add Items</h2>

    <form class="form-inline mb-3">

      <input type="text" class="form-control mr-2">

      <input type="submit" class="btn btn-dark" value="Submit">

    </form>

    <h2 class="title">Items</h2>

    <ul id="items" class="list-group">

      <li style="color:green" class="list-group-item">

        Item 1</li>

      <li  style =background-color:green  class="list-group-item">Item 2</li>

      <li style="color:green"  class="list-group-item"></li>

      <li style="color:green"  class="list-group-item">Item 4</li>

    </ul>

   </div>

  </div>

  <script>

  class Student{



    constructor(name,age,marks){

    this.name=name;

    this.age=age;

    this.marks= marks;

    }

    setplacementAge(minPlacementAge){

    console.log(this);

  return(minMarks)=>{

   console.log('inside eligibleforCurrentCompany', this)

    

    if(this.marks>minMarks && this.age>minPlacementAge){

      console.log(this.name+"is ready for placement")

    }

        else{

          console.log(this.name+"is not ready for placements")

        }

        }

      }

  }

    const  Abc= new Student('abc', 25 , 75);

    const  Xyz= new Student('xyz', 13, 35);

    Rekha.setPlacementAge(18)(40);

</script>

</body>
