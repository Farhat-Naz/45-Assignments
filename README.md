# 45-Assignments

// Name Case: Store a  personname in a variable then print person name in lower cas.
let personName: string="Farhat Naz";
// in lowercase
console.log("Lower Case", personName.toLowerCase());
// in upper case
console.log("upper case",personName.toUpperCase());
// titlecase
console.log("Titlecase",personName.replace(/\b\w/g,c=> c.toUpperCase()));


//Personal message store a person name in variable and print a message to that person.
//Your message should simple such as "Hello Eric, would you like to learn some python today?"
let personName:String="Eric";
console.log('Hello ${personName}, would you like to learn some python today');


// Print a famous quote of Alber Eintien
//Albert Einstien once said, "A person who never made mistake never tried everthing new"
let quote:String="A person who never made mistake never tried everthing new";
let auther:String="Albert Einstien";
console.log('${auther} once said, "${quote}"');
// repeat excercise 4 but repeat 
let famous_person:String="Albert Einstion";
let message:String=`${famous_person} once said, "${quote}"`;
console.log(message);





//Stripping a name store  a person name and include some whitespase characters 
// at the beginning and end of the name make sure you use each combination "\t" and "\n" at least once
//print the name first around the whitespace
//then print name after stripping whitespace
let personName:String = "\t\n Farhat naz \n\t";
console.log(personName);
console.log("Original:", personName);
console.log("stripped:",personName.trim());


//Number Eight:write addition,subtraction,multiplication and division operators each result in number8
//Be sure to your operation in print statement
//task 8 you should create four lines that looks looks like
//console.log(5+3)
console.log(5+3);
console.log(10-2);
console.log(4*2);
console.log(32/4);

// Favourite number store your favourite number in a variable using that variable create a message
//of your favourite number then print it
let myFavouritenumber:Number=4;
console.log(myFavouritenumber);
console.log('my favourite number is ${myFavouritenumber} ')




//Adding comments choose two of the programs written
// Auther: (Farhat Naz)
//Date: [Saturday 13 April 2024]

// printing a favourite number
let myFavouritnumber: number=4;

//printing number in sentence form
console.log('My favourite number is ${myFavouritenumber}');


//task 11
//Store persons name in an array
let names: string[]= ["Areeba","Ayesha","Mishal","Harim"];
console.log(names);
console.log(names[0]);
console.log(names[1]);
console.log(names[2]);
console.log(names[3]);




//task 12
let names: string[] =["Areeba","Ayesha","Mishal","Harim"];
let message: string="Do you like to play football";
console.log(names[0] + "  " + message);
console.log(names[1] + "  " + message);
console.log(names[2] + "  " + message);
console.log(names[3] + "  " + message);
console.log(names + "  " + message);


//task13

let transportation: string[]= ["Honda Motorcycle","Audi","Honda City","Collola"];
transportation.map((items) => console.log('I would like to Own, ${items}'));

// Task 14
let guestArr: string[]=["Share","Nashit","Saffan"];
guestArr.map((items)=>(console.log(`Dear ${items} ,You are invited to Dinner`)));

//Task 15
let guestArr : string[]=["Shareq","Nashit","Saffan"];
let cannotAttend : string ="Shareq";
//console.log(cannotAttend + "  "+  "cannot attend the party ");
let newGuest:string = "Zargham";
guestArr [guestArr.indexOf(cannotAttend)]=newGuest;
//console.log(guestArr);
guestArr.map((items)=>
    console.log(`Dear ${items}, You are invited to party`));


//task16
let guestArr: string[]=["Shariq","Nashit","Harim","Mishal"];
//let cannotAttend: string= "Nashit"
//let newGuest:string="Hiba"
//console.log(newGuest);
//guestArr[guestArr.indexOf(cannotAttend)]="newGuest"
//console.log(guestArr)
//guestArr.map((items)=>
   // console.log(`Dear ${items}, I found a bigger dinner table so I am inviting more people`));
//part 2 question

//let  arrNew:string="Ameena"
//guestArr.unshift(arrNew);
//console.log(guestArr);
//part 3 adding in middle of array
let middleguest:string="Fatima"
let middleIndex=guestArr.length/2;
guestArr.splice(middleIndex,2,middleguest);
console.log(guestArr);
// part 4 use append()
 guestArr.push("Zeeshan");
console.log(guestArr);

//part5
guestArr.map((items)=>
   console.log(`Dear ${items} , you are invited in the more category dinner party`));


//Task 17
//let guest: string[]=["Shareq","Mishal","Nashit","Saffan"];
//console.log("Due to limited space only two people are invited to party");
//while(guest.length>2) {
  //  const removedGuest = guest.pop();
    //console.log(`Sorry ${removedGuest}, you are no longer invited to dinner`);
//}
//part 3
let guest: string[]=["Nashit","Saffan","shareq"];
//guest.forEach((guest)=>
   // console.log(`Dear ${guest}, You are still invited to Dinner`));
guest.pop();
guest.pop();
console.log("Final guest list", guest);


//task18
//store locatins in Array
let placestovisit: string[]= ["Japan","Pakistan","UAE","Iran","Saudi Arab"];
//print the array in its original order
console.log("original order",placestovisit);
// print an array in alphabetical order
console.log("Alphabetical order", placestovisit.sort());
// show the array in its original form
console.log("Array in its orignal form", placestovisit);
//print array in its reverse alphabetical order
console.log("Array in reverse alphabetical order",placestovisit.reverse());
console.log("order",placestovisit.sort().reverse());
//print original order after reverse sorting
console.log("original order after reverse sorting", placestovisit);
//print reverse order
placestovisit.reverse()
console.log("reverse roder",placestovisit);
// sort array in reverse alphabetical order
placestovisit.sort((a, b) => b.localeCompare(a));
console.log("sort in reverse alphabetical order",placestovisit);


//task 19
// find out the length of invitation that are invited in taks14
let invitation: string[]= ["Shariq","Nashit"];
let count_invitation: Number= invitation.length
console.log(`${count_invitation}, People will come to dinner`);



// task 20
let country: string[] = ["pakistan","Afghanistan","Iran","China","Oman"];
console.log("List of Countries");
console.log(country);



//task 21
//create an object then print it.
let person: {name: string, fname: string, age: Number}= {name: "Farhat", fname: "female", age: 35};
console.log(person);


//task 22
//intention error
const days: string[] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Saturday","Friday"];
//console.log(days{6});
console.log(days[6]);



//task23
//conditional test
let car= "subaru";
//console.log("is car == 'subaru'? predicted true");
//console.log(car == 'subaru');
//onsole.log("is car!='honda city? predicted true");
//console.log(car != 'honda city');
//console.log("is carr == subaru? predicted false")
//console.log(car =='subaru');
//console.log("is carr == SUBARU? predicted false")
//console.log(car =='SUBARU');
//console.log("is carlength == 6? predicted 6");
//console.log(car.length == 6);
//console.log("is carlength == 10? predicted true);
//console.log(car.length == 10);
console.log("is carlength == 10? predicted true");
console.log(car.length == 6)
console.log("is 10>45 ? predicted false");
console.log(10>45);
console.log("is 10==10 predicted true");
console.log(10==10);
console.log("is 3>=2 then predicted false");
console.log(3>=2);
console.log("is car== sabaru && car.length==6 predicted true");
console.log(car=='subaru' && car.length==6);


// task 24
//let name_1: string = "farhat";
//let name_2: string = "farhat naz";
//let name_3: string = "farhat naz siddiqui";
//if(name_1 == name_3){
 //   console.log("condition is true");
//}
//else {
 //   console.log("condition is false");
//}
//if (name_1 != name_2){
    //console.log("condition is ture");
//}
let age_1: number = 18;
let age_2: number = 22;
//if ( age_1 == 18){
  //  console.log("Eligibal for vote");
//}
//if ( age_2 == 22)
  //  {   
    //     console.log("not Eligibal for vote");
//}
//if ( age_1<=age_2)
    //{
      //  console.log("younger");
    //}
    //if ( age_2>=age_1)
      //  {
       //     console.log("Older");
        //}
        //if(age_1==18 && age_2==22)
          //  {
            //    console.log("eligible for vote");
            //}
           // if(age_1==18 || age_2==22)
             //   {
               //     console.log("eligible for vote");
              //  }
              //  if(age_1==18 || age_2!=22)
                //    {
                  //      console.log("eligible for vote");
                   // }
let country:string[]=["Pakistan","Afghanistan","China"];
if (country.includes("Pakistan"))
{
    console.log("pakistan is in array list");
}
if (!country.includes("America"))
    {
    console.log("America is not in array list");
}



//task25
//let alien_color="green";
//if(alien_color=="green"){
  //  console.log("You earned five points");
//}
let alien_color: string="red";
if(alien_color =="yellow"){
    console.log("No output");
}

//task26
let alien_color: string="green";
//if(alien_color == "green")
  //  {
    //console.log("player earned 5 points for shooting");
//}
  //  else {

    
    //console.log("player earned 10 points");
//}
if(alien_color == "red")
    {
    console.log("player earned 5 points for shooting");
}
    else {

    
    console.log("player earned 10 points");
}


//task27
let alien_color: string="yellow";
if(alien_color=="green"){
    console.log("5 points");
}
else if(alien_color=="yellow")
    {
    console.log("10points");
}
else
{
    console.log("15 points");
}



//task28
let age: number= 100;
if(age<2){
    console.log("You are a baby");
}
else if(age<4){
    console.log("you are a toddler");
}
    
else if(age<13){
    console.log("you are a adult");
}
        
else if(age<20){
    console.log("you are a teeanager");
}


else
{ 
    console.log("Your are older");

}


//task 29
let favourite_fruit: string[]=["Kivi","Orange","apple","peach","grapes"];
if (favourite_fruit.includes("Kivi")){
    console.log("Kivi");
}
if (favourite_fruit.includes("peach")){
    console.log("you really like banana");
}
if (favourite_fruit.includes("Orange")){
    console.log("Orange");
}
if (favourite_fruit.includes("grapes")){
    console.log("you really like banana");

}
if(favourite_fruit.includes("apple"))
    {
        console.log("apple");
    }


//task30
let users: string[]=["admin","Eric","safan","Mishal","shariq"];
for(let user of users){
    if(user==="admin"){
        console.log("Hello admin,would you like to see status");
    }

else{
    console.log(`Hello ${user}, thank you for logging again`);
}
}



//task31
let users: string[] = ["admin","Eric","shariq","safan","Mishal"];

if (users.length === 0)
    {
        console.log("We need to find some users")
    }
    for(let user of users){

        if(user === "admin"){
            console.log("Hello would you like to see our report");
        }
        else{
            console.log(`Hello ${user} thank you for logging`);
        }
        }
    users=[]
    if(users.length === 0){
        console.log("we need some new users");
    }


//task32
let current_users: string[] = ["mishal","shareq","nashit","safan","hiba"];
let new_users: string[] =["mishal","Mohammad","Hassan","nashit","zaeem"];
let current_users_lower: string[]= current_users.map(user =>user.toLowerCase())
for(let new_user of new_users){
    if(current_users_lower.includes (new_user.toLowerCase())){
        console.log(`sorry ${new_user} that name is not taken`);
    
    }
    else{
        console.log(`yes ${new_user} is available`);

    }
}



//task33
let numbers: number[]=[1,2,3,4,5,6,7,8,9];
for(let number of numbers){
if(number === 1){
    console.log(`${number}st`);
}
else if(number === 2){
    console.log(`${number}nd`);
}
else if(number === 3){
    console.log(`${number}rd`);
}
else{
    console.log(`${number}th`);
}
}


//task34.ts
let favourite_pizza: string[]=["tikka","fajita","veg"];
for(let pizza of favourite_pizza)
    {
        console.log(pizza);
        
    }
    console.log("\n");
    for(let pizza of favourite_pizza){
        console.log(`I really love ${pizza} pizza`);
    }
    console.log("\n I really love pizza");


//task35
let animals: string[]=["cat","lion","dog"];
for(let animal of animals){
    console.log(animal);
}
console.log("\n");
for(let animal of animals){
    console.log(`A ${animal} has a long tail`);
}
console.log("\n All of these are greats pets");


// task 36
function makeshirt(size: string, text: string): void {
    console.log(`\n You orders a ${size} of shirt that says ${text}`);
}
makeshirt('large',"I required mdedium shirt");
makeshirt('medium',"I required medium shirt");


//task37
function makeshirt(size: string='large', text: string='I Love typescript'): void{
    console.log(`You have ordered a ${size}, shirt that says ${text}`);
}
makeshirt();
makeshirt('medium');
// different
makeshirt('small','I need large shirt');




//task 38
function describe_city(city: string ,country: string='Pakistan'):void{
    console.log(`${city} is in ${country}`);
}
describe_city('Karachi');
describe_city('Al-Ain','UAE');
describe_city('Lahore','Pakistan');



//task39
function cityCountry(city: string, country:string):string{
    return(`${city},${country}`);
}
let c1= cityCountry('Tokyo','Japan');
let c2= cityCountry('Paris','France');
let c3= cityCountry('Karachi','Pakistan');
console.log(c1);
console.log(c2);
console.log(c3);



//task40.ts
function makeAlbum(artist: string, title: string): {artist: string, title: string}{
    const dictionaries ={
        artist:artist.charAt(0).toUpperCase()+artist.slice(1),
        title:title.charAt(0).toUpperCase()+title.slice(1)
    };
    return dictionaries;
}
let album = makeAlbum("Ali","light")
console.log(album)
 album = makeAlbum("Bilal","red wave")
console.log(album)
 album = makeAlbum("Hamza","seenbreeze")
console.log(album)

//{"1","2","3"}
//{"0","1","2"}



//task41
function show_magicians(magicians: string[]):void{
    for(const magician of magicians){
    
        console.log(magician.charAt(0).toUpperCase() + magician.slice(1));
    
    }
    }
    const magician: string[] =["Ali","Hamza","Safan"];
    show_magicians(magician)



   //task42
function show_magicians(magicians) {
    for (var _i = 0, magicians_1 = magicians; _i < magicians_1.length; _i++) {
        var magician_1 = magicians_1[_i];
        console.log(magician_1.charAt(0).toUpperCase() + magician_1.slice(1));
    }
}
function make_great(magicians: string[]):void{
    for(let i=0; i<magicians.length; i++){
        magicians[i]=magicians[i]      +  'the great'
    }
}
const magicians2: string[]=["Ali","Hamza","Safan"];
make_great(magicians2)
show_magicians(magicians2)



//task43
function show_magicians(magicians: string[]):void{
    //for(const magician of magicians){
     
      //   console.log(magician.charAt(0).toUpperCase() + magician.slice(1));
     
     //}
     }
 function make_great(magicians: string[]):void{
    for(let i=0; i<magicians.length; i++){
         magicians[i]=magicians[i]      +  'the great'
     }
 }
     const magicians: string[] =["Ali","Hamza","Safan"];
     show_magicians(magician);
 function make_great2(magicians: string[]):void{
     const greatMagicians: string[]=[];
     for(let i=0; i<magicians.length; i++){
         greatMagicians.push(magicians[i] +  'the Great');
     }
 return greatMagicians;
 
     
 }
 const greatMagicians3: string[]=["Haseeb","Ali","Hamza"];
 const greatMagicians2: string[]=[make_great2(magicians3)];
 show_magicians(greatMagicians3);
 show_magicians(greatMagicians2);



//task44
function sandwich(...items: string[]):void{
    console.log("sandwich order:");
    for(let i=0; i<items.length; i++){
        console.log(`-${items[i]}`);
    }

}
console.log("enjoy you sandwich");
sandwich('capsicam','Tomato','Chicken')
sandwich('Cheese','beef')
sandwich('garlic chicken','Mayo')



//task45
type car={
    manufacture: string
    model: string
    [key: string]: any;
    }
    function creatCar(manufacture: string, model:string, optional: Record<string, any>):car{
    return{
        manufacture,
        model,
        ...optional
    }
    }
    const myCar:car= creatCar("Toyata","Corolla",{color:"silver",year: "2024"})
    console.log(myCar);










