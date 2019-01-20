# Can-you-recOgniZe-me-
An AI  application that does object detection on images.
Inspiration
We are machine learning enthusiasts who are really passionate about artificial intelligence. We have worked on training neural networks from scratch to build image classifiers and predict supervised learning models previously. So we wanted to try something new and google cloud API's presented us with tremendous opportunities.

What it does
Our application does real-time object detection with Google Cloud Vision API.

Part A: Web front-end

The user provides a URL link of an image of his/her own choice to the client side.
The back-end server written in nodeJS then processes the image.
It then outputs relevant information including various correct forms of identification to what is seen in the image.
Part B IOS

The user turns on the camera
The app recognizes objects in real time and outputs the name of the things it sees on the go, and also provides the accuracy with which it predicts the object.
How we built it
We used Google's Cloud Vision API in our application. We first figured out how to set up a google cloud services account and run object detection on the google cloud server.
We then integrated the vision API into nodeJS application respectively. We wrote code in nodeJS &expres s to connect the backend to the client side and display the objection detection results on the web browser.
We then wrote an html and css file on the front-end and wrote code connecting the front end to the express back end, thus enabling the back end to process and output the results of the user submitted image url.

We also built the back end with a flask application as well and learned to integrate the cloud vision API in python.

Finally, we build real-time object detection on IOS device.

Challenges we ran into

Integrating API into the back end applications is not straightforward. One of the challenges we ran into was to figure how to parse data from the back end server side( nodeJS and flask) to the front-end side.

Accomplishments that we're proud of
We are proud of the effort put in by the entire team. When we started none of us had any prior experience of using google cloud API into our applications.

What we learned
We learned to use node JS , express and integrate cloud Vision API into our application. We learned how to process data coming from the server side , parse it and display the output on the browser. We learned verious little functional details/features to enhance our application and lastly, we learned designing by using HTML/CSS.

What's next for Can you recOgniZe me?
The next step for us will be to use other cloud API's such as natural language processing and Video intelligence and make an application which applies the techniques learned to some real world problems
