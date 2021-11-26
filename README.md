# technojam-task-Web-Development
# my approach for this contact form:
first of all just made the overall skeleton of the form i.e html, them i used css for styling and i thought that orange colour would be nice.
# Difficulty that i faced during this task:
aligning, padding, margin confuses me a lot that why this still have some issuses . i cannot able to align properly the Heading and the form layout propely.
# About Myself :
My name is Gaurav Kumar Thakur, i am from muzaffarpur, Bihar.
Making something by myself always gives me a good feeling.
I love Making Music, Playing Guitar.
# code for My Contact Form
<!DOCTYPE html>
<html>
    <head>
        <title>
            Contact Form
        </title>
    </head>
    <body>
        <h2><i>CONTACT FORM</i></h2>
        <form class="form">
            <div class="contact">
                <input type="text" id="input-name" placeholder="Enter Your Name">
                <input type="email" id="input-email" placeholder="Email Addres">
                <input type="text" id ="phone-number" placeholder="Phone Number">
            </div>
            <input type="submit" value="submit" id="input-submit">
        </form>
    </body>
    <style>
        html,body{
            background:#dfe9ed ;
            font-family:sans-serif;
            padding: 1em;
            
        }
        h2 {
            text-align: center;
            color: orange;
            box-shadow: opx opx 5px 3px whitesmoke;
            font-weight: 1000px;
            font-size: 50px;
            

        }
        .form {
            max-width: 100px;
            text-align: center;
            margin: 5% auto;

        }
        
        #input-name{
            border: 0;
            padding: 1em;
            border-radius: 10px;
            width: 160%;
            margin-top: 1em;
            box-shadow: orange;
            font-weight: 500;
            font-size: 15px;
            box-shadow: 0px 0px 5px 3px wheat;
        }
        
        #input-email{
            border: 0;
            padding: 1em;
            border-radius: 10px;
            display: block;
            width: 160%;
            margin-top: 1em;
            float: left;
            box-shadow: orange;
            font-weight: 500;
            font-size: 15px;
            box-shadow: 0px 0px 5px 3px wheat;
        }
        #phone-number{
            border: 0;
            padding: 1em;
            border-radius: 10px;
            width: 160%;
            margin-top: 1em;
            box-shadow: 0px 0px 5px 3px wheat;
            font-weight: 500;
            font-size: 15px;

        }
        #input-submit {
            display: inline-block;
            border: 0;
            padding: 12px 16px;
            color: white;
            background: orange;
            cursor: pointer;
            width: 185%;
            border-radius: 30px;
            margin-top: 1em;
            font-weight: 500;
            font-size: 20px;
            box-shadow: 0px 0px 5px 3px rgb(170, 135, 135);
        }
        #input-submit:hover{
            background-color: black;

        }
    </style>
</html>

