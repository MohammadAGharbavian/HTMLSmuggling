# HTMLSmuggling
HTML Smuggling Attack Simulation :

What is HTML Smuggling Attack :   

HTML smuggling employs HTML5 attributes that can work offline by storing a binary in an immutable blob of data within JavaScript code.    The data blob, or the embedded payload, gets decoded into a file object when opened via a web browser.
 In this examlpe you will see how this attack work on your computer as target 
 
 Configuration :
 
 	Open The File Named "index.html" with your favorite editor like Notepad++ or ........
	and edit the href of a tag with address of your malware on your pc.
	That all your are ready for start the attack.
 	
	
	
More Explanation :
In the index.html file we up a function named download() , what this function does is that when some one 
open our web site or the link we send to them , it will automatically download the file that we put on the 
a tag .

	<script>
	    (function download() {
		document.getElementById('dl').click();
	    })()
	</script>
