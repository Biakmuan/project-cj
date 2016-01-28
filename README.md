<html>
<head>
<script type="text/javascript">

function myFunc()
{
var a = "biakmuan";
alert("Ans : " + a );
getElemntById("showName").innerHTML("My name is" + a);
}

</script>
</head>
<body>

<p>Q : Na min bang a ?</p>
<p>Ans: <span id="showName"></span></p>
<!-- Browser a aki et chiang a Ans zom chet a span id koihsom ka hi-->

<form>
<input type="Button" value="Click here" onclick="myFunc();" />
</form>
</body>
</html>
