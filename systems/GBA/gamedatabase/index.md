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

## A full table of every AGB component and their part numbers/specification.

<input type="text" id="AGBInput" onkeyup="searchFunction()" placeholder="Search for Component/Part Number/Specification">

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
 </tbody>
</table>

<onebutton>
<ul>
            <li><a href="../">Go<strong>Back</strong></a></li>
          </ul>
</onebutton>
