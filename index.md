You can generate a Unique IDentifier using this Javascript Bookmarklet. 
Drag the link to your bookmark bar to save it: <a href="javascript:
var today=new Date();
var epoch=Math.floor( today.getTime() / 1000 );
var epoch36=(epoch).toString(36);
function myFunction() {
  alert('Your UID is: ' + epoch36 + '\nGenerated on ' + today );
};
myFunction();">UID Generator</a>
