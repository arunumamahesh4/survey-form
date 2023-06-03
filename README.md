<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <style type="text/css">
        body{
            background-color: lightgreen;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        .form-control{
            text-align:left;
            margin: 25px;
        }
        form{
            margin: 50px auto;
            padding: 30px 30px;
            max-width:350px;
        }
        .form-control input,
        .form-control select,
        .form-control textarea{
            display: block;
            padding: 10px;
            width:95%;
        }
        .form-control input[type="radio"],
        .form-control input[type="checkbox"]{
            display:inline-block;
            width:auto;
        }
        button{
            display: block;
            width: 100%;
            padding: 10px 10px;
            background-color:lightgreen ;
        }
    </style>
</head>
<body>
    <h1 style="text-align:center;">SURVEY FORM</h1>
    <form>
        <fieldset>
        <div class="form-control">
        <label style="display:block;margin-bottom:10px">Name</label>
        <input type="text" name="Name" placeholder="Enter your name">
        </div>

        <div class="form-control">
            <label style="display:block;margin-bottom:10px">Email</label>
            <input type="text" name="Name" placeholder="Enter your Email">
            </div>

            <div class="form-control">
                <label style="display:block;margin-bottom:10px">Age</label>
                <input type="text" name="Name" placeholder="Enter your age">
                </div>

                <div class="form-control">
                    <label style="display:block;margin-bottom:10px">phone number</label>
                    <input type="text" name="Name" placeholder="Enter your PhNo">
                    </div>

                <div class="form-control">
                        <label style="display:block;margin-bottom:10px">which option best describes you</label>
                        <select>
                            <option>Student</option>
                            <option>Intern</option>
                            <option>Employee</option>
                            <option>Others</option>
                        </select>
                        </div>   

                        <div class="form-control">
                            <label style="display:block;margin-bottom:10px">Would you recommand these</label>
                            <input type="radio" name="choice">Yes
                            <input type="radio" name="choice">No
                            <input type="radio" name="choice">May be
                        </div>

                        <div class="form-control">
                            <label style="display:block;margin-bottom:10px">Would you recommand these</label>
                            <input type="radio" name="choice">C
                            <input type="radio" name="choice">C++
                            <input type="radio" name="choice">python
                            <input type="radio" name="choice">Java 
                        </div>
                        <div class="form-control">
                            <label style="display:block;margin-bottom:10px">Any comments or suggestions</label>
                            <input type="text" name="Name" placeholder="Enter your suggestions here">
                            </div>
                            <button type="submit">submit</button>
        </fieldset>
    </form>
</body>
</html>
