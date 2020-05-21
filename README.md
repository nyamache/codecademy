/* # codecademy
codecademy projects */
const howOld = (age,year) =>{
  const theCurrentYear = 2020;
  const yearDifference = year -theCurrentYear;
  const newAge=age + yearDifference;
if(newAge > age){
  return (`'You will be ${newAge} in the year ${year}'`);
}else if(newAge < 0) {
  return (`'The year ${year} was ${-newAge} years before you were born'`);
}else {
  return (`'You were ${newAge} in the year ${year}'`);
}
};
console.log(howOld(20, 1995));
