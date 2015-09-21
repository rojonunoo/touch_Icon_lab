
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title> Bubble Factory Test Lab</title>
<script>

var scores = [ 60, 50, 60, 58, 54, 54,
			   58, 50, 52, 54, 48, 69,
			   34, 55, 51, 52, 44, 51,
			   69, 64, 66, 55, 52, 61,
			   46, 31, 57, 52, 44, 18,
			   41, 53, 55, 61, 51, 44];


var heighScore=0;
var output;
var Test;
var sum=0;
var Total=0;

for( var i= 0; i < scores.length; i++)
{

	output = "Bubble solution #" +[i] + " : " + scores[i]; 
	console.log(output);

	if (scores[i] > heighScore){
		heighScore = scores[i];
	}	

	for (counter =0;   counter < scores.length, counter++) {
		sum[scores] += Total;
	};
}
	console.log("Bubbles Tests :" + scores.length);
	console.log("Heighest Bubble score " + heighScore );
	console.log("Total number " + sum );



</script>
</head>
</body></body>
</html>
