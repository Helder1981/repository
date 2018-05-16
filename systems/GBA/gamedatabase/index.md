<link href="table.css" rel="stylesheet">
<script src="jquery-3.2.1.min.js"></script>
<script type="text/javascript" charset="utf8" src="//cdn.datatables.net/1.10.16/js/jquery.dataTables.js"></script>
<script>
$(document).ready( function () {
    $('#AGBTable').DataTable( {
        paging: false,
		searching: true,
		dom: 'tpri'
    } );
} );
</script>

<script>
function searchFunction() {

    var table = $('#AGBTable').DataTable();
	var input = document.getElementById("AGBInput");
    table.search( input.value ).draw();
};
</script>

## A Database of every GBA title Publisher, id and release date

<input type="text" id="AGBInput" onkeyup="searchFunction()" placeholder="Search for Title/Publisher/ID/Relased">

<table id="AGBTable" class="display">
    <thead>
        <tr>
            <th>Title</th>
            <th>Publisher</th>
			<th>ID</th>
			<th>Released</th>
        </tr>
    </thead>
    <tbody>
  <tr>
    <td>007: Everything or Nothing(US)</td>
    <td>EA Games</td>
	<td>AGB-BJBE-USA</td>
	<td>17/11/03</td>
  </tr>
  <tr>
    <td>007: Everything or Nothing(EU)</td>
    <td>EA Games</td>
	<td>AGB-BJBP-EUR</td>
	<td>05/12/03</td>
  </tr>
  <tr>
    <td>007: Everything or Nothing(JP)</td>
    <td>Electronic Arts</td>
	<td>AGB-BJBJ-JPN</td>
	<td>11/02/04</td>
  </tr>
  <tr>
    <td>007: NightFire(US)</td>
    <td>Electronic Arts</td>
	<td>AGB-A7OE-USA</td>
	<td>18/03/03</td>
  </tr>
  <tr>
    <td>007: NightFire(EU)</td>
    <td>Electronic Arts</td>
	<td>AGB-A7OP-EUR</td>
	<td>28/03/03</td>
  </tr>
  <tr>
    <td>Tony Hawk's Underground(US)</td>
    <td>Activision</td>
	<td>AGB-BTOE-USA</td>
	<td>27/10/03</td>
  </tr>
  <tr>
    <td>Tony Hawk's Underground(EU)</td>
    <td>Activision</td>
	<td>AGB-BTOP-EUR</td>
	<td>21/11/03</td>
  </tr>
  <tr>
    <td>Kelly Slater's Pro Surfer(US)</td>
    <td>Activision</td>
	<td>AGB-AS3E-USA</td>
	<td>21/08/02</td>
  </tr>
  <tr>
    <td>Kelly Slater's Pro Surfer(EU)</td>
    <td>Activision</td>
	<td>AGB-AS3P-EUR</td>
	<td>18/10/02</td>
  </tr>
  <tr>
    <td>V-Rally 3(EU)</td>
    <td>Infogrames</td>
	<td>AGB-AVRP-EUR</td>
	<td>21/06/02</td>
  </tr>
  <tr>
    <td>V-Rally 3(JP)</td>
    <td>Atari SA</td>
	<td>AGB-AVRJ-JPN</td>
	<td>27/06/02</td>
  </tr>
  <tr>
    <td>V-Rally 3(US)</td>
    <td>Atari SA</td>
	<td>AGB-AVRE-USA</td>
	<td>30/09/02</td>
  </tr>
  <tr>
    <td>Stuntman(US)</td>
    <td>Infogrames</td>
	<td>AGB-AUXE-USA</td>
	<td>24/06/03</td>
  </tr>
  <tr>
    <td>Stuntman(EU)</td>
    <td>Infogrames</td>
	<td>AGB-AUXP-EUR</td>
	<td>04/07/03</td>
  </tr>
 </tbody>
</table>

<onebutton>
<ul>
            <li><a href="../">Go<strong>Back</strong></a></li>
          </ul>
</onebutton>
