# React assessment

Instructions to run the project:
1)	Download the zip react-assessment-narapa and unzip to a local folder
2)	Navigate to the folder: react-assessment-narapa and run command: ‘npm install’
3)	To see tests running, run: npm test -- -u
4)	Run ‘npm start’ after install is complete successfully
5)	Once npm start is successful and you see the line: ‘Compiled successfully.’, open the browser and run: http://localhost:8082/
6)	To see tests running, run: npm test -- -u

Points to note:
Task One:
1)	When using the filter to search for a username, the API request should be triggered after a 5 second debounce.
Narapa: This is fixed in UserList class component.
2)	Reduce the number of re-renders by converting the UserList React Class Component to a React functional component, exposing custom hooks where appropriate.
Narapa: I have created a new component called UserListFn for this work. To check this please follow below instructions:
a)	In TaskOne.jsx, comment line: 9 where we are importing UserList and uncomment line 10 where we are importing UserListFn. 
b)	Change line number 15 to <UserListFn />
c)	Start the app running: npm start if not running.
d)	The reason I have created this separate component is, I am not able to get debounce working unfortunately in this functional component (It is working as expected in class component). If I spend some time, I may be able to see what is missing. But moved on as I need to work on Task Two. 


Task Two:

Expected:
1.	No backdrop/page overlay is required for this exercise.
2.	All modals should expose a mechanism to allow them to be closed.
3.	There should be a way to consume button click events on modals with buttons.
4.	Create a demo page with three buttons that trigger each of the modals to show.
Narapa: I may not have got exact styles with pixels but tried my best to get this look more like samples.
I have tried to add some tests for all the components, but they are not complete due to my limited unit testing in react knowledge. I agree, I need to improve my skills around testing; for that matter may be in React as well 😊.

Thanks for assessment. I enjoyed every bit of this 😊


 

