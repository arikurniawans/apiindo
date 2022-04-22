# apiindo

<!DOCTYPE html>
<html>
<head>
    <title>Tutorial PHP Datatables Dengan PHP Dan MySQL</title>
    <link rel="stylesheet" type="text/css" media="screen" href="https://cdn.datatables.net/1.10.19/css/jquery.dataTables.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdn.datatables.net/1.10.19/js/jquery.dataTables.min.js"></script>
</head>
<body>

<table id="tabel-data">
  <thead>
    <tr>			
      <th>Nama</th>
      <th>Alamat</th>
      <th>Pekerjaan</th>
      <th>Usia</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Malas Ngoding</td>
      <td>Bandung</td>
      <td>Web Developer</td>
      <td>26</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Malas Ngoding</td>
      <td>Bandung</td>
      <td>Web Developer</td>
      <td>26</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
    <tr>				
      <td>Andi</td>
      <td>Jakarta</td>
      <td>Web Designer</td>
      <td>21</td>
      <td>Aktif</td>
    </tr>
  </tbody>

<script>
    var intervalID = setInterval(test(), 1000); // Will alert every second.
// clearInterval(intervalID); // Will clear the timer.

setTimeout(test(), 1000); // Will alert once, after a second.
setInterval(function(){ 
  fetchWithAsyncAwait('2022-04-22');
}, 2000);//run this thang every 2 seconds

function test(){
  console.log('Mulai !');
}

async function fetchWithAsyncAwait (id)  {
  try {
    let response = await fetch('https://api.pray.zone/v2/times/day.json?city=mecca&date=' + id)
    response = await response.json()
    console.log(response)
  } catch (error) {
    console.log('opps' + error)
  }
}

</script>

</table>
</body>
</html>
