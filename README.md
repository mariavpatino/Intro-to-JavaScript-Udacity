# Intro to JavaScript: Udacity

### Quiz: First Expression (2-1):
console.log((1 / 1) *1 + 41);
<br>
<br>

### Quiz: Converting Temperatures (2-2):
var celsius = 12;
var fahrenheit = celsius * 1.8 + 32

console.log(fahrenheit);
<br>
<br>

### Quiz: Favorite Food (2-3):
console.log("Korean Food");
<br>
<br>

### Quiz: String Equality for All (2-4):
var answer = "ALL Strings are CrEaTeD equal" == "ALL Strings are CrEaTeD equal";
console.log(answer);
<br>
<br>

### Quiz: All Tied Up (2-5):
var joke = "Why couldn't the shoes go out and play? \nThey were all \"tied\" up!"
console.log(joke);
<br>
<br>

### Quiz: Yosa Buson (2-6):
var haiku1 = "Blowing from the west"
var haiku2 = "\nFallen leaves gather"
var haiku3 = "\nIn the east."
var haiku = haiku1 + haiku2 + haiku3
console.log(haiku);
<br>
<br>

### Quiz: Semicolons! (2-8):
var thingOne = "red";
var thingTwo = "blue";
console.log(thingOne + " " + thingTwo);
<br>
<br>

### Quiz: What's my Name? (2-9):
var fullName = "Maria";
var fullName1 = "Patino";
console.log (fullName + " " + fullName1);
<br>
<br>

### Quiz: Out to Dinner (2-10):
var bill = 10.25 + 3.99 + 7.15;
var tip = bill * 0.15;
var total = bill + tip;
console.log(total);
<br>
<br>

### Quiz: Mad Libs (2-11):
var adjective1 = 'amazing';
var adjective2 = 'fun';
var adjective3 = 'entertaining';

var madLib =`\'The Intro to JavaScript course is ${adjective1}. James and Julia are so ${adjective2}. I cannot wait to work through the rest of this ${adjective3} content!\'`;

console.log(madLib);
<br>
<br>

### Quiz: One Awesome Message (2-12):
var firstName = "Julia";
var interest = "Cats";
var hobby = "play video games";
var awesomeMessage = "Hi, my name is " + firstName + "." + " I love" + interest + ". " + "In my spare time, I like to " + hobby + ".";

console.log(awesomeMessage);
<br>
<br>

### Quiz: Even or Odd (3-2):
var number = 2;

if (number % 2 === 0) {
    console.log("even");
} else {
    console.log("odd");
}

<br>
<br>

### Quiz: Musical Groups (3-3):
var musicians = 10;

if (musicians === 0) {
    console.log("not a group");
}
    else if (musicians === 1) {
    console.log("solo");
}
    else if (musicians === 2) {
    console.log("duet");
}
    else if (musicians === 3) {
    console.log("trio");
}
    else if (musicians === 4) {
    console.log("quartet");
}
    else {
    console.log("this is a large group");
}

<br>
<br>

### Quiz: Murder Mystery (3-4):
var room = "dining room";
var suspect = "Mr. Parkes";

var weapon = "";
var solved = false;

if (room === "ballroom" && suspect === "Mr. Kalehoff") {
    weapon = "poison";
    solved = true;
    
} else if (room === "gallery" && suspect === "Ms. Van Cleve") {
    weapon = "trophy";
    solved = true;
    
} else if (room === "billiards room" && suspect === "Mrs. Sparr") {
    weapon = "pool stick";
    solved = true;
    
} else if (room === "dining room" && suspect === "Mr. Parkes") {
    weapon = "knife";
    solved = true;
    
}

if (solved) {
	console.log(suspect + " did it in the " + room + " with the " + weapon + "!");
}

<br>
<br>

### Quiz: Checking your Balance (3-5):
var balance = 325.00;
var checkBalance = true;
var isActive = true;

if (checkBalance === true){
    if(isActive === true && balance > 0){
    console.log("Your balance is $"+ balance);
    }
    if(isActive === false){
    console.log("Your account is no longer active");
    }
    if (balance === 0){
    console.log("Your account is empty");
    }
    if (balance < 0){
    console.log("Please contact your bank");
    }
}
else {
    console.log("Your account is no longer active")
}

<br>
<br>

### Quiz: Ice Cream (3-6):
var flavor = "abc";
var vessel = "cone";
var toppings = "peanuts";

if ((flavor === "vanilla" || flavor === "chocolate" ) && (vessel === "cone" || vessel === "bowl") && (toppings === "sprinkles" || toppings === "peanuts")){ 
    console.log("I'd like two scoops of " + flavor + " ice cream in a " + vessel + " with " + toppings + ".");
}
else 
console.log("Pick other flavor");

<br>
<br>

### Quiz: What do I Wear? (3-7):
var shirtWidth = 19.99;
var shirtLength = 30;
var shirtSleeve = 8.71;

if ((shirtWidth >= 18 && shirtWidth < 20 ) && (shirtLength >= 28 && shirtLength <29) && (shirtSleeve >= 8.13 && shirtSleeve < 8.38)){
    console.log("S");
}
else if ((shirtWidth >= 20 && shirtWidth < 22 ) && (shirtLength >= 29 && shirtLength <30) && (shirtSleeve >= 8.38 && shirtSleeve < 8.63)) {
    console.log("M");
}
else if ((shirtWidth >= 22 && shirtWidth < 24 ) && (shirtLength >= 30 && shirtLength <31) && (shirtSleeve >= 8.63 && shirtSleeve < 8.88)) {
    console.log("L");
}
else if ((shirtWidth >= 24 && shirtWidth < 26 ) && (shirtLength >= 31 && shirtLength < 33) && (shirtSleeve >= 8.88 && shirtSleeve < 9.63)) {
    console.log("XL");
}
else if ((shirtWidth >= 26 && shirtWidth < 28 ) && (shirtLength >= 33 && shirtLength <34) && (shirtSleeve >= 9.63 && shirtSleeve <10.13)) {
    console.log("2XL");
}
else if ((shirtWidth >= 28) && (shirtLength === 34 ) && (shirtSleeve >= 10.13)) {
    console.log("3XL");
}
else {
    console.log("N/A")
}
 
<br>
<br>

### Quiz: Navigating the Food Chain (3-8):
var eatsPlants = false;
var eatsAnimals = true;

var category = ((eatsPlants && eatsAnimals) ?  "omnivore" : (eatsPlants) ?  "herbivore" : (eatsAnimals) ?  "carnivore" : "undefined")

console.log(category);

<br>
<br>

### Quiz: Back to School (3-9):
var salary = 0;


switch (education) {
    case 'no high school diploma':
        salary = salary.toLocaleString("en-US") + 25,636;
        break;
    case 'high school diploma':
        salary = salary.toLocaleString("en-US") + 35,256;    
        break;
    case 'an Associate\'s degree':
        salary = salary.toLocaleString("en-US") + 41,496;
        break;
    case 'a Bachelor\'s degree':
        salary = salary.toLocaleString("en-US") + 59,124;      
        break;
    case 'a Master\'s degree':
        salary = salary.toLocaleString("en-US") + 69,732;  
        break;
    case 'a Professional degree':
        salary = salary.toLocaleString("en-US") + 89,960;  
        break;
    case 'a Doctoral degree':
        salary = salary.toLocaleString("en-US") + 84,396;   
        break;
}

console.log("In 2015, a person with " +  education + " earned an average of " + salary+ "/year.");

<br>
<br>

### Quiz: JuliaJames (4-1):
var x = 1;

while (x <= 20) {
    
    if (x%3 === 0){
        console.log("Julia");
    }
    else if (x%5 === 0) {
        console.log("James");
    }
    else if ((x%3 === 0) && (x%5 === 0)) {
        console.log("JuliaJames");
    }
    else {
        console.log(x)
    }
    
    x = x+ 1;
}

<br>
<br>

### Quiz: 99 Bottles of Juice (4-2):
var x = 99;
while(x >= 1) {
    console.log(`${x} bottles of juice on the wall! 99 bottles of juice! Take one down, pass it around... 98 bottles of juice on the wall!`);
    x=x-1;
}

<br>
<br>

### Quiz: Countdown, Liftoff! (4-3):
var x = 60;
while(x >= 0) {
    if (x === 50) {
        console.log("Orbiter transfers from ground to internal power");
    }
    else if (x ===31) {
        console.log("Ground launch sequencer is go for auto sequence start");
    }
    else if (x===16) {
        console.log("Activate launch pad sound suppression system")
    }
    else if (x===10) {
    console.log("Activate main engine hydrogen burnoff system")
    }
    else if (x===6) {
    console.log("Main engine start")
    }
    else if (x===0) {
    console.log("Solid rocket booster ignition and liftoff! ")
    }
    else
    console.log(`T-${x} seconds`);
x = x-1;
}

<br>
<br>

### Quiz: Changing the Loop (4-4):

for (var x = 9; x >= 1 ; x--) {
    console.log("hello " + x);
}

<br>
<br>

### Quiz: Fix the Error 1 (4-5):
for (var x = 5; x < 10; x++) {
  console.log(x);
}

<br>
<br>

### Quiz: Fix the Error 2 (4-6):
for (var k = 0; k < 200; k++) {
  console.log(k);
}

<br>
<br>

### Quiz: Find my Seat (4-8):
for (x = 0; x < 26; x++) {
    for (y = 0; y < 100; y++) {
        console.log(`${x}-${y}`);
    }
}

<br>
<br>

### Quiz: Laugh it Off 1 (5-1):
function laugh () {
   var message = "hahahahahahahahahaha!"; 
   return message;
}

console.log(laugh());

<br>
<br>

### Quiz: Laugh it Off 2 (5-2):

function laugh(num) {
    var ha = "";
    for (var i=0; i<num; i++) {
        ha = ha + "ha";
    }
    return ha + "!";

}
console.log(laugh(4));

<br>
<br>

### Quiz: Laugh (5-4)

var laugh = function(x) {
    var ha = "";
    for (i = 0; i<x; i++){
    ha = ha+ "ha"}
    return ha + "!";
};

console.log(laugh(3));

<br>
<br>

### Quiz: Cry (5-5):
var cry =  function boo(){
    var message = "boohoo!";

    return message;
};

console.log(cry());

<br>
<br>

### Quiz: Colors of the Rainbow (6-4):

var rainbow = ['Red', 'Orange', 'Blackberry', 'Blue'];

rainbow.splice(2,1,"Yellow", "Green");

rainbow.splice(5,0,"Purple");
console.log(rainbow);

<br>
<br>

### Quiz: Quidditch Cup (6-5):
var team = ["Oliver Wood", "Angelina Johnson", "Katie Bell", "Alicia Spinnet", "George Weasley", "Fred Weasley", "Harry Potter"];

function hasEnoughPlayers (team) {
   
    if (team.length >= 7) {
        return true;
    }
    else
    return false;
}
console.log(hasEnoughPlayers(team));

<br>
<br>

### Quiz: Joining the Crew (6-6):

var captain = "Mal";
var second = "Zoe";
var pilot = "Wash";
var companion = "Inara";
var mercenary = "Jayne";
var mechanic = "Kaylee";

var crew = [captain, second, pilot, companion, mercenary, mechanic];

var doctor = "Simon";
var sister = "River";
var shepherd = "Book";

crew.push("Simon","River","Book");

console.log(crew);

<br>
<br>

### Quiz: I Got Bills (6-9):

var bills = [50.23, 19.12, 34.01,
    100.11, 12.15, 9.90, 29.11, 12.99,
    10.00, 99.22, 102.20, 100.10, 6.77, 2.22
];

var totals = bills.map(function(elem) {
    var tipadd =elem * 0.15;
    elem += tipadd;
    return Number(elem.toFixed(2));
  
} 
);
console.log(totals);

<br>
<br>

### Quiz: Nested Numbers (6-10):

var numbers = [
    [243, 12, 23, 12, 45, 45, 78, 66, 223, 3],
    [34, 2, 1, 553, 23, 4, 66, 23, 4, 55],
    [67, 56, 45, 553, 44, 55, 5, 428, 452, 3],
    [12, 31, 55, 445, 79, 44, 674, 224, 4, 21],
    [4, 2, 3, 52, 13, 51, 44, 1, 67, 5],
    [5, 65, 4, 5, 5, 6, 5, 43, 23, 4424],
    [74, 532, 6, 7, 35, 17, 89, 43, 43, 66],
    [53, 6, 89, 10, 23, 52, 111, 44, 109, 80],
    [67, 6, 53, 537, 2, 168, 16, 2, 1, 8],
    [76, 7, 9, 6, 3, 73, 77, 100, 56, 100]
];

for (row = 0; row < numbers.length; row++) {
    for (column = 0; column < numbers[row].length;column++){
        if (numbers[row][column] % 2 ===0) {
            numbers[row][column] = "even"

        }
        else
            numbers[row][column] ="odd";
    }
    
}

console.log(numbers);

<br>
<br>

### Quiz: Umbrella (7-1):

var umbrella = {
    color: "pink",
    isOpen: true,
    open: function() {
        if (umbrella.isOpen === true) {
            return "The umbrella is already opened!";
        } else {
            umbrella.isOpen = true;
            return "Julia opens the umbrella!";
        }
    },
    close: function(){
        if (umbrella.isOpen === false) {
            return "The umbrella is already closed!";
        }
        else{
            umbrella.isOpen === false;
            return "Julia closes the umbrella!";
        }
    }
};

console.log(umbrella);

<br>
<br>

### Quiz: Menu Items (7-2)

breakfast = {
    name : "The Lumberjack",
    price: 9.95,
    ingredients: ["eggs", "sausage", "toast", "hashbrowns", "pancakes"]
}

console.log(breakfast);

<br>
<br>

### Quiz: Bank Accounts 1 (7-3):

var savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    },
    printAccountSummary: function() {
        var message = "Welcome! \nYour balance is currently $1000 and your interest rate is 1%.";
        return message;
    }
};

console.log(savingsAccount.printAccountSummary());

<br>
<br>
