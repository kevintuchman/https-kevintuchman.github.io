//  Three parts of every function!

//  Inputs
//  work
//  output

//  What do I want this function to do?
//  Inputs: name, flightNumber, seatNumber
//  Work: based on that, make a "confirmation statement" with their name, flight number, seat, and that 6 digit code
// Output: the "confirmation statement"

//  Build an example
//  Assumption: code external to the function will prompt the user for their name, flightNumber, and seatNumber.
var passengerName = 'Corey':
var flight = '555';
var seat = '28B';

//  Inputs: name - Corey  flightNumber  - 555 seatNumber  - 27B
//  Work
//  Randomly generate a string containing numbers and letters
//  Take the inputs and remember them
//  Glue together the senctence with the name, flightNumber and seatNumber we're given

//  Outputs:  "Corey, you have booked flight 555, seat 27B. Confirmation code: XY67DF".

//  When we run it: assign Corey to name, assign 555 to filghtNumber, and assign 27B to seatNumber

//                      paramemters!
function makeFlightConfirmation(name, flightNumber, seatNumber) {
  var ticket = name + ", you have booked flight " + flightNumber + ", seat " + seatNumber + "."
  return
}

var coreysConfirmation = makeFlightConfirmation("Corey", "555", "27B");

var passengerName = "Ewa";
var passengerFlight = 662'
var passengerSeat = "28A";

var passengerName = prompt("What is your name?");
var passengerFlight = prompt(What is your flight number?");
var passengerSeat = prompt("What seat do you want?");

var usersConfirmation = makeFlightConfirmation(pasengerName, passengerFlight, passengerSeat);

console.log(usersConfirmation);
document.write('<p>here is your tcket:</p>')
document.write('<p>' + usersConfirmation + '</p>');
alert(usersConfirmatio)n;