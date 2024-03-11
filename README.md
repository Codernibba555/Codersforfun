# Innodev 2k24
Workout Tracker
 # Team Name : Codersforfun
    Members:
    Rishabh Saxena <https://github.com/Codernibba555/>
    Nishant Tiwari
    Salony Dash
    Vrinda Dhingra
# Proposed Features:
      Allow users to create accounts and set up profiles with
      personal information such as age, weight, height, fitness
      goals, etc.
      Enable users to log their workouts by recording exercises,
     sets, reps, and weights.
     Provide a comprehensive database of exercises with
       descriptions and demonstration videos.
      Allow users to track their progress over time, including
      weight lifted, repetitions performed, and workout
       duration.
      Offer a calendar view for users to schedule and plan their
       workouts in advance.
         Send reminders to users to complete their scheduled
         workouts.
         Enable users to track body measurements like weight,
       body fat percentage, waist circumference, etc
# Your Innovations
     N/A
# Tech Stack
     Abstract:

    The TRACK-FAST Registration system is a web application designed to facilitate user registration for the TRACK-FLEX platform. The system employs HTML, 
    CSS, and JavaScript to create an intuitive and visually appealing registration form. The design choices and implementation details are elaborated as 
    follows:

        1. HTML Structure:
           The HTML document defines the structure of the registration form using semantic elements. The `<form>` element encapsulates input fields for username and password. Each input field is associated with a `<label>` element, enhancing accessibility and user experience. The form is organized within a `<div>` with the class "main" for styling and layout purposes.
        
      
        2. CSS Styling:
           The CSS stylesheet defines the visual presentation of the registration form and its elements. Selectors target specific HTML elements to apply styles for layout, typography, and color scheme. The styling enhances the form's aesthetics and readability, ensuring a pleasant user experience.
        
        
        In summary, the TRACK-FAST Registration system implements a well-structured and visually appealing user registration form using HTML, CSS, and JavaScript. The system prioritizes usability, accessibility, and design aesthetics to deliver an optimal user experience for registering on the TRACK-FLEX platform.


             We are using VSCode for HTML CSS and Javascript.



            like code for login page
            <!DOCTYPE html>
          <html>
          
          <head>
          	<title>TRACK-FAST Registration</title>
          	<link rel="stylesheet"
          		href="style.css">
          </head>
          
          <body>
          	<div class="main">
          		<h1>TRACK-FLEX</h1>
          		<h3>Enter your login credentials</h3>
          		<form action="">
          			<label for="first">
          				Username:
          			</label>
          			<input type="text"
          				id="first"
          				name="first"
          				placeholder="Enter your Username" required>
          
          			<label for="password">
          				Password:
          			</label>
          			<input type="password"
          				id="password"
          				name="password"
          				placeholder="Enter your Password" required>
          
          			<div class="wrap">
          				<button type="submit"
          						onclick="solve()">
          					Submit
          				</button>
          			</div>
          		</form>
          		<p>Not registered? 
          			<a href="#"
          			style="text-decoration: none;">
          				Create an account
          			</a>
          		</p>
          	</div>
             </body>
          
             </html>





            and style:


            /*style.css*/


                body {
                	display: flex;
                	align-items: center;
                	justify-content: center;
                	font-family: sans-serif;
                	line-height: 1.5;
                	min-height: 100vh;
                	background: #f3f3f3;
                	flex-direction: column;
                	margin: 0;
                }
                
                .main {
                	background-color: #fff;
                	border-radius: 15px;
                	box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
                	padding: 10px 20px;
                	transition: transform 0.2s;
                	width: 500px;
                	text-align: center;
                }
                
                h1 {
                	color: #000000;
                	background-color: #ADD8E6;
                	display:inline;
                	display: inline-block;
                }
                
                label {
                	display: block;
                	width: 100%;
                	margin-top: 10px;
                	margin-bottom: 5px;
                	text-align: left;
                	color: #555;
                	font-weight: bold;
                }
                
                
                input {
                	display: block;
                	width: 100%;
                	margin-bottom: 15px;
                	padding: 10px;
                	box-sizing: border-box;
                	border: 1px solid #ddd;
                	border-radius: 5px;
                }
                
                button {
                	padding: 15px;
                	border-radius: 10px;
                	margin-top: 15px;
                	margin-bottom: 15px;
                	border: none;
                	color: white;
                	cursor: pointer;
                	background-color: #ADD8E6;
                	width: 100%;
                	font-size: 16px;
                }
                
                .wrap {
                	display: flex;
                	justify-content: center;
                	align-items: center;
                }
