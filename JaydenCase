String.prototype.toJadenCase = function (sentence) {
  var space = ' ';
  var final = '';
  for (j = 0; j < sentence.length; j ++) {
  	var l = j - 1;
  if (sentence[l] === space) {
  	caps = sentence[j].toUpperCase();
  	final += caps;
  }
  else {
  	final += sentence[j];
  }
  }
	return(final);
};
String.prototype.toJadenCase("How can mirrors be real if our eyes aren't real");
