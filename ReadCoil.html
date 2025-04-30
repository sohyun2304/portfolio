<!DOCTYPE html> 
<html> 
<body> 
<h1 style="background-color:DodgerBlue;color:white">EECE8061-25W-Sec1-Data Communications</h1>  
<p><img src="https://conestoga.desire2learn.com/d2l/api/lp/1.9/courses/1343751/image?height=230&width=540&t=2025-04-16T19:17:27.720Z" alt="Course Image" width="540" height="230" style="display: block; margin: 1;"></p> 
<h1><?php echo "This message is from server side." ?></h1> 

<p> 
<?php 
echo "Inside the main php block<br>"; 
$dbServerName = "sql103.infinityfree.com:3306"; 
$dbUsername = "if0_38669150"; 
$dbPassword = "IWSRbFKcrxcKki9"; 
$dbName = "if0_38669150_Lab4C"; 

echo "After establishing the dbservername, etc<br>"; 
// create connection 
$conn = new mysqli($dbServerName, $dbUsername, $dbPassword, $dbName); 

echo "Made the connection object----->";  
// check connection 

if ($conn->connect_error) { 
    die("Connection failed: " . $conn->connect_error); 
} 
?> 
</p>
<p style="color:red;">Connected successfully</p>
<p><b>&lt;coils Table&gt;</b>
<?php 

/* 
 * get data from coils table 
 */ 

$sql = "SELECT addr, value FROM coils"; 

$result = $conn->query($sql); 
if ($result->num_rows > 0) { 
    // output data of each row 
    echo "<table border='2' style='border-collapse: collapse; text-align: center;'> 
            <tr> 
            <th>Address</th> 
            <th>Value</th>
            <th>Light</th>
            </tr>"; 

    while($row = $result->fetch_assoc()) { 
        $value = $row["value"];
        echo "<tr>"; 
        echo "<td>" . $row['addr']. "</td>" ; 
        echo "<td>" . $row['value']. "</td>"; 

        if ($value == 0) { 
            echo "<td style='padding: 1px;'><svg width='40' height='20'><rect x='1' y='1' width='40' height='20' stroke='black' fill='red' stroke-width='0'/></svg></td>"; 
        } else { 
            echo "<td style='padding: 1px;'><svg height='20' width='20'><circle cx='10' cy='10' r='9' stroke='black' stroke-width='1' fill='green' /></svg></td>"; 
        } 
        echo "</tr>"; 
    } 

    echo "</table>"; 
} else { 
    echo "0 results"; 
} 
?> 
<br><br><b>&lt;regValues Table&gt;</b>
<?php 

/* 
 * get data from coils table 
 */ 
$sql = "SELECT addr, value FROM regValues"; 

$result = $conn->query($sql); 
if ($result->num_rows > 0) { 
    // output data of each row 
    echo "<br><br><table border='2' style='width: 150px; border-collapse: collapse; text-align: center;'> 
            <tr> 
            <th style='width: 50%;'>Address</th> 
            <th style='width: 50%;'>Value</th>
            </tr>"; 

    while($row = $result->fetch_assoc()) { 
        $value = $row["value"];
        echo "<tr>"; 
        echo "<td>" . $row['addr']. "</td>" ; 
        echo "<td>" . $row['value']. "</td>"; 

        echo "</tr>"; 
    } 

    echo "</table>"; 

} else { 

    echo "0 results"; 

} 


?> 

</p> 
</body> 
</html> 
