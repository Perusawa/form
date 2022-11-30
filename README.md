<!DOCTYPE html>
<html lang="en">
  
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0">
    <title>
        feedback form
    </title>
 
    <style>
 
        /* Styling the Body element i.e. Color,
        Font, Alignment */
        body {
         background-image: url("PARLOUR BACKGROUND 2.jpg");
            font-family: Verdana;
            text-align: center;
        }
 
        /* Styling the Form (Color, Padding, Shadow) */
        form {
            background-color:#EE82EE;; 
            max-width: 500px;
            margin: 50px auto;
            padding: 30px 20px;
            box-shadow: 2px 5px 10px rgba(0, 0, 0, 0.5);
        }
 
        /* Styling form-control Class */
        .form-control {
            text-align: left;
            margin-bottom: 25px;
        }
 
        /* Styling form-control Label */
        .form-control label {
            display: block;
            margin-bottom: 10px;
        }
 
        /* Styling form-control input,
        select, textarea */
        .form-control input,
        .form-control select,
        .form-control textarea {
            border: 1px solid #777;
            border-radius: 2px;
            font-family: inherit;
            padding: 10px;
            display: block;
            width: 95%;
        }
 
        /* Styling form-control Radio
        button and Checkbox */
        .form-control input[type="radio"],
        .form-control input[type="checkbox"] {
            display: inline-block;
            width: auto;
        }
 
        /* Styling Button */
        button {
         background-image: url("PARLOUR BACKGROUND 2.jpg");
            border: 1px solid #777;
            border-radius: 2px;
            font-family: inherit;
            font-size: 21px;
            display: block;
            width: 100%;
            margin-top: 50px;
            margin-bottom: 20px;
        }
    </style>
</head>
  
<body>
    <h1>FEEDBACK FORM</h1>
  
    <!-- Create Form -->
    <form id="form">
 
        <!-- Details -->
        <b>
        <div class="form-control">
            <label for="name" id="label-name">
                FULL NAME
            </label>
 
            <!-- Input Type Text -->
            <input type="text"
                   id="name"
                   placeholder="Enter your name" />
        </div>
  
        <div class="form-control">
            <label for="email" id="label-email">
                EMAIL ID
            </label>
 
            <!-- Input Type Email-->
            <input type="email"
                   id="email"
                   placeholder="Enter your email" />
        </div>
  
        <div class="form-control">
            <label for="age" id="label-age">
                AGE
            </label>
 
            <!-- Input Type Text -->
            <input type="text"
                   id="age"
                   placeholder="Enter your age" />
        </div>
  
        <div class="form-control">
            <label for="role" id="label-role">
                WHICH OPTION YOU LIKE TO DESCRIBE ?
            </label>
             
            <!-- Dropdown options -->
            <select name="role" id="role">
                <option value="student">HYGINE</option>
                <option value="intern">SERVICE RATES</option>
                <option value="professional">
                    PRODUCTS WITHOUT CHEMICAL
                </option>
                <option value="other">OTHER</option>
            </select>
        </div>
  
        <div class="form-control">
            <label>
                WOULD YOU LIKE TO RECOMMEND OUR SERVICE TO A FRIEND?
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="recommed-1">
                <input type="radio"
                       id="recommed-1"
                       name="recommed">Yes</input>
            </label>
            <label for="recommed-2">
                <input type="radio"
                       id="recommed-2"
                       name="recommed">No</input>
            </label>
            <label for="recommed-3">
                <input type="radio"
                       id="recommed-3"
                       name="recommed">Maybe</input>
            </label>
        </div>
  
        <div class="form-control">
            <label>TELL US WHICH PRODUCT WOULD YOU LIKE TO USE IN OUR NEXT SERVICE.
                <small>(Check all that apply)</small>
            </label>
            <!-- Input Type Checkbox -->
            <label for="inp-1">
                <input type="checkbox"
                       name="inp">DIOR</input></label>
            <label for="inp-2">
                <input type="checkbox"
                       name="inp">L'OREAL</input></label>
            <label for="inp-3">
                <input type="checkbox"
                       name="inp">THE BODY SHOP</input></label>
            <label for="inp-4">
                <input type="checkbox"
                       name="inp">ESTEE LAUDER</input></label>
            <label for="inp-5">
                <input type="checkbox"
                       name="inp">REVLON</input></label>
            <label for="inp-6">
                <input type="checkbox"
                       name="inp">GARNIOR</input></label>
            <label for="inp-7">
                <input type="checkbox"
                       name="inp">CLARINS</input></label>
            <label for="inp-7">
                <input type="checkbox"
                       name="inp">URBAN DECAY</input></label>
            <label for="inp-7">
                <input type="checkbox"
                       name="inp">BIOTIQUE</input></label>
            <label for="inp-7">
                <input type="checkbox"
                       name="inp">GLOSSIER</input></label>
        </div>
  
        <div class="form-control">
            <label for="comment">
                ANY COMMENTS AND SUGGESTIONS
            </label>
 
            <!-- multi-line text input control -->
            <textarea name="comment" id="comment"
                placeholder="Enter your comment here">
            </textarea>
        </div>
  
        <!-- Multi-line Text Input Control -->
        <button type="submit" value="submit">
            SUBMIT
        </button></b>
    </form>
</body>
  
</html>
