# FTTH
<!DOCTYPE html>
<html>
<head>
  <title>FTTH Verification Form</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>

<h2>FTTH Verification Form</h2>

<form id="ftthForm">

<label>Verification Date</label>
<input type="date" name="verification_date" required>

<label>Verifier Name</label>
<input type="text" name="verifier_name">

<label>Designation</label>
<input type="text" name="designation">

<label>GP Name</label>
<input type="text" name="gp_name">

<label>FTTH Address</label>
<textarea name="address"></textarea>

<label>FTTH Phone No</label>
<input type="text" name="phone">

<label>Distance from Origin (in meter)</label>
<input type="number" name="distance">

<label>Connection Shift?</label><br>
<input type="radio" name="shift" value="Yes"> Yes
<input type="radio" name="shift" value="No"> No

<br><br>

<label>Wifi User ID</label>
<input type="text" name="wifi_id">

<label>Wifi Password</label>
<input type="text" name="wifi_password">

<label>Remarks</label>
<textarea name="remarks"></textarea>

<br><br>
<button type="submit">Submit</button>

</form>

<script src="script.js"></script>
</body>
</html>
