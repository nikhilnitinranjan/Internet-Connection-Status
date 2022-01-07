# Internet-Connection-Status
Hey friends,
we create a Toast Notification to Detect Internet Connection Status using HTML CSS & JavaScript.

In this program [Detect Internet Connection], 
there is a webpage with a minimal toast notification 
and it changes its icon, color, text according to the internet connection status as you can see in the preview image.
 It has a pretty cool animation that means when your internet status changed,
 it’ll show from the left top side with a sliding animation.

The concepts/codes behind creating this program are so simple.
 At first, using JavaScript Ajax I send a GET request to a particular passed URL and check,
 that URL is sending any data as a response or not and the response status of that request URL is equal to 200 and less than 300 or not.
 
If the passed URL is sending data as a response and the response status of that
 URL is also equal to 200 then the user is connected to the Internet so he/she is getting data as a response
 but if it isn’t then the user is disconnected from the Internet.
