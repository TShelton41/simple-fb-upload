# Simple Firebase Upload Example
 
This is a Firebase project showing you how to upload an image to the Firebase Storage. You must have a Firebase project already set up in Firebase and you will need to run a few commands to make this project work. 

1. Download this code and open it in your favorite editor. 
2. Then open this project up in a terminal or if you are using VSC you can use the integrated terminal. 
3. You will need to associate this project with your Firebase project. 
4. Run <pre>firebase login</pre>this will log you into Firebase. 
5. Next you will need to add your project to this code. <pre>firebase use --add</pre>You should now have your project connected to this project. 
6. Make sure the file .firebaserc has your project name listed. <pre>{
  "projects": {
    "default": "your-project-name"
  }
}</pre>

Now you are ready to start the project. 

If you look in the package.json there are a couple scripts that will be of use. the 'serve-local' is for testing locally and the 'deploy' is for deploying to Firebase. When you deploy to Firebase it will give you the URL for your site. 

Properties that you can access in snapshot. 
PROPERTY	         TYPE	         WRITABLE
bucket	          string	          NO
generation	      string	          NO
metageneration	  string	          NO
fullPath	        string	          NO
name	            string	          NO
size	            number	          NO
timeCreated	      string	          NO
updated	          string	          NO
md5Hash	          string	          YES
on upload	          -	              NO
on updateMetadata	  -	              NO
cacheControl	    string	          YES
contentDisposition string	          YES
contentEncoding	   string	          YES
contentLanguage	   string	          YES
contentType	       string	          YES
downloadURLs	     Array	          NO
customMetadata	   Object	          YES



