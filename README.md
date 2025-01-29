<!DOCTYPE html>
<html>
<head>
<title>Navya Registration Form</title>
</head>
 <body>
<h1 style="color: green">User Registration Form</h1>
<form onsubmit="showAlert(); return false;">
<label for="name">Name</label>
<input type="text" id="name" name="name"><br><br>
<label for="phone">Phone</label>
<input type="tel" id="phone" name="phone"><br><br>
<label for="address">Address</label>
<input type="text" id="address" name="address"><br><br>
<label for="email">Email</label>
<input type="email" id="email" name="email"><br><br>
<button type="submit">Submit</button>
</form>
<script>
        function showAlert() {
            alert("Form submitted successfully!");
        }
</script>
</body>
</html>
