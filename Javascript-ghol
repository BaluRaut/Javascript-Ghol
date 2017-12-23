How do I get the second largest element from an array in javascript [closed]

var secondMax = function (){ 
    var arr = [20, 120, 111, 215, 54, 78]; // use int arrays
    var max = Math.max.apply(null, arr); // get the max of the array
    arr.splice(arr.indexOf(max), 1); // remove max from the array
    return Math.max.apply(null, arr); // get the 2nd max
};
var myArray = [799, -85, 8, -1, 6, 4, 3, -2, -15, 0, 207, 75, 785, 122, 17];
 
// This function returns 2nd largest Number from passed array
function findSecondLargeNumber(arr){
	
	var fLargeNum = 0;
	var sLargeNum = 0;
	
	for(var i=0; i<arr.length; i++){
		if(fLargeNum < arr[i]){
			sLargeNum = fLargeNum;
			fLargeNum = arr[i];			
		}else if(sLargeNum < arr[i]){
			sLargeNum = arr[i];
		}
	}
	
	return sLargeNum;
	
}
 
// Alert 2nd large number
function Show2ndLargeNumber(){
	alert(findSecondLargeNumber(myArray));
}
window.onload = Show2ndLargeNumber();
// ===============2=====

var myarray =['20','120','111','215','54','78','215'];
var secondLargest = myarray.sort(function(a,b){return a - b})[myArray.length-3];
alert(secondLargest); //120;

// ===============3=====

var arr = ['20','120','111','215','54','78'];

arr.sort(function(a,b){
    return b-a;
});

console.log(arr[1]);

// ==========Sort Arrsar By Name-=====
user = [{
bio: "<null>",
email: "user@domain.com",
firstname: 'Anna',
id: 318,
"last_avatar": "<null>",
"last_message": "<null>",
lastname: 'Nickson',
nickname: 'anny'
},
{
bio: "<null>",
email: "user@domain.com",
firstname: 'Senad',
id: 318,
"last_avatar": "<null>",
"last_message": "<null>",
lastname: 'Nickson',
nickname: 'anny'
},
{
bio: "<null>",
email: "user@domain.com",
firstname: 'Muhamed',
id: 318,
"last_avatar": "<null>",
"last_message": "<null>",
lastname: 'Nickson',
nickname: 'anny'
}];

var ar = user.sort(function(a, b)
{
  var nA = a.firstname.toLowerCase();
  var nB = b.firstname.toLowerCase();

  if(nA < nB)
    return -1;
  else if(nA > nB)
    return 1;
 return 0;
});


//Sort alphabetically and descending:
var myarray=["Bob", "Bully", "Amy"]
myarray.sort()
myarray.reverse() //Array now becomes ["Bully", "Bob", "Amy"]


//Sort numerically and ascending:
var myarray=[25, 8, 7, 41]
myarray.sort(function(a,b){ //Array now becomes [7, 8, 25, 41]
    return a - b
});
