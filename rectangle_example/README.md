## Rectangle App

To fetch a response from the server, follow these steps:

1. Generate a Webhook URL
	Visit https://webhook.site/.
	A unique URL endpoint will be generated for you automatically.
	
2. Configure the Webhook
	Click on the Edit option in the top-right menu.
	Update the following settings:
		Content Type: Change to application/json.
		Content: Replace with the JSON data below:
	[
    		{"id": "1", "dir": "vertical", "width": "87px", "height": "43px", "score": 52, "left": 50, "top": 180, "color": "blue"},
    		{"id": "2", "dir": "horizontal", "width": "112px", "height": "48px", "score": 2, "left": 140, "top": 250, "color": "red"},
    		{"id": "3", "dir": "vertical", "width": "47px", "height": "97px", "score": 37, "left": 560, "top": 380, "color": "green"},
   		{"id": "4", "dir": "vertical", "width": "71px", "height": "71px", "score": 150, "left": 450, "top": 350, "color": "pink"},
    		{"id": "5", "dir": "horizontal", "width": "76px", "height": "95px", "score": 24, "left": 650, "top": 15, "color": "orange"},
    		{"id": "6", "dir": "vertical", "width": "100px", "height": "132px", "score": 73, "left": 200, "top": 70, "color": "yellow"}
	]
	CORS Headers: Check the box to enable Add CORS headers.

3. Use the Generated URL
	Copy the URL from the Your unique URL section at the top of the page.
	Use this URL as the endpoint in your fetch request.
	You can modify the JSON content in the Edit section to customize the server response.
	
Good luck! 😊
