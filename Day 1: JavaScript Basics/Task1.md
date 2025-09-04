## Mini task: Print student details from an object 


```javascript

// Define a student object
const student = {
  name: "Param Malviya",
  age: 22,
  course: "Computer Science",

  printDetails: function () {
    console.log("Student Details:");
    console.log("Name   :", this.name);
    console.log("Age    :", this.age);
    console.log("Course :", this.course);
  }
};

// Call the function
student.printDetails();

```
