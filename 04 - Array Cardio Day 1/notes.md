**Arrays and Functional Programming**
*Filter*
const fifteen = inventors.filter(function(inventor));

const created an object that can be accessed
fifteen defines object
inventors is an object with an array
filter is the method
- filter requires a function to work
- the function will loop over each item in object
function is the requirement of the filter method
inventor is the arbitrary name given to the object created by the filter method


const fifteen = inventors.filter(function(inventor));

if(inventor.year >= 1500 && inventor.year < 1600) {
  return true;
};
if- sets up block of code
inventor- name of anonymous object
year- property of inventor
>= -condition

return true- stores anonymous object /keeps anonymous object

else if not required since you only want to keep what meets conditions


const fifteen = inventors.filter(function(inventor));

option
const fifteen = inventors.filter(inventor =>{

  });

function replaced with =>



console.table(const_object)
