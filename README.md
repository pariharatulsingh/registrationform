<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enrollment Form</title>
    <link rel="stylesheet" href="main.css">
    <link href="https://fonts.googleapis.com/css2?family=Staatliches&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Gruppo&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Forum&family=Gruppo&display=swap" rel="stylesheet">

</head>

<body>
    <h1>Student Enrollment System</h1>
    <div class="container centre">
        <table>
            <tr>
                <td>
                    <form class="input-part" autocomplete="off" onsubmit="onFormSubmit()">
                        <div>
                            <label for="studentName">Student Name</label>
                            <input type="text" placeholder="Enter Student Name" name="studentName" id="studentName">
                        </div>
                        <div>
                            <label for="collegeName">College Name</label>
                            <input placeholder="Enter College Name" type="text" name="collegeName" id="collegeName">
                        </div>
                        <div>
                            <label for="Email">Email</label>
                            <input placeholder="Enter The Email" type="text" name="Email" id="Email">
                        </div>
                        <div>
                            <label for="Gender">Gender</label>
                            <input placeholder="Enter the Gender" type="text" name="Gender" id="Gender">
                        </div>
                        <div>
                            <label for="DOB">DOB</label>
                            <input placeholder="DOB" type="text" name="DOB" id="DOB">
                        </div>
                        <div class="form-btns">
                            <input type="submit" value="SUBMIT">
                            <input type="reset" value="CLEAR">
                        </div>
                    </form>

                    <td>
                        <table class="list" id="storeList">
                            <thead>
                                <tr>
                                    <th></th>
                                    <th></th>
                                    <th></th>
                                    <th></th>
                                    <th></th>
                                    <th></th>
                                </tr>
                            </thead>
                            <tbody>

                            </tbody>
                        </table>
                    </td>
                </td>
            </tr>
        </table>
        <script src="file.js" defer>
        </script>
    </div>
</body>

</html
