function reverseString(str) { 
  var lin = '';
  for(var i=str.length;i>-1;i--) {
  lin=lin.concat(str.charAt(i));
  console.log(lin);
  }
 
  return lin;
