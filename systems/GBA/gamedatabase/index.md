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

## A Database of every GBA title, publisher, id and release date

<input type="text" id="AGBInput" onkeyup="searchFunction()" placeholder="Search for Title/Publisher/ID/Relased">

<table id="AGBTable" class="display">
    <thead><tr><th>Title</th><th>Publisher</th><th>ID</th><th>Released</th></tr></thead>
    <tbody>
  <tr><td>007: Everything or Nothing(US)</td><td>EA Games</td><td>AGB-BJBE-USA</td><td>17/11/03</td></tr>
  <tr><td>007: Everything or Nothing(EU)</td><td>EA Games</td><td>AGB-BJBP-EUR</td><td>05/12/03</td></tr>
  <tr><td>007: Everything or Nothing(JP)</td><td>Electronic Arts</td><td>AGB-BJBJ-JPN</td><td>11/02/04</td></tr>
  <tr><td>007: NightFire(US)</td><td>Electronic Arts</td><td>AGB-A7OE-USA</td><td>18/03/03</td></tr>
  <tr><td>007: NightFire(EU)</td><td>Electronic Arts</td><td>AGB-A7OP-EUR</td><td>28/03/03</td></tr>
  <tr><td>Tony Hawk's Underground(US)</td><td>Activision</td><td>AGB-BTOE-USA</td><td>27/10/03</td></tr>
  <tr><td>Tony Hawk's Underground(EU)</td><td>Activision</td><td>AGB-BTOP-EUR</td><td>21/11/03</td></tr>
  <tr><td>Kelly Slater's Pro Surfer(US)</td><td>Activision</td><td>AGB-AS3E-USA</td><td>21/08/02</td></tr>
  <tr><td>Kelly Slater's Pro Surfer(EU)</td><td>Activision</td><td>AGB-AS3P-EUR</td><td>18/10/02</td></tr>
  <tr><td>V-Rally 3(EU)</td><td>Infogrames</td><td>AGB-AVRP-EUR</td><td>21/06/02</td></tr>
  <tr><td>V-Rally 3(JP)</td><td>Atari SA</td><td>AGB-AVRJ-JPN</td><td>27/06/02</td></tr>
  <tr><td>V-Rally 3(US)</td><td>Atari SA</td><td>AGB-AVRE-USA</td><td>30/09/02</td></tr>
  <tr><td>Stuntman(US)</td><td>Infogrames</td><td>AGB-AUXE-USA</td><td>24/06/03</td></tr>
  <tr><td>Stuntman(EU)</td><td>Infogrames</td><td>AGB-AUXP-EUR</td><td>04/07/03</td></tr>
  <tr><td>3-in-1 Sports Pack</td><td>Majesco</td><td>AGB-B3NE-USA</td><td>18/10/05</td></tr>
  <tr><td>3 Games in 1(US)</td><td>THQ</td><td>AGB-BJUE-USA</td><td>15/10/03</td></tr>
  <tr><td>3 Games in 1(EU)</td><td>THQ</td><td>AGB-BJUP-EUR</td><td>12/03/04</td></tr>
  <tr><td>4 Games on One Game Pak</td><td>THQ</td><td>AGB-BI4E-USA</td><td>11/09/07</td></tr>
  <tr><td>A Sound of Thunder(EU)</td><td>Bam Entertainment</td><td>AGB-A3QP-EUR</td><td>28/02/04</td></tr>
  <tr><td>A Sound of Thunder(US)</td><td>Bam Entertainment</td><td>AGB-A3QE-USA</td><td>01/02/05</td></tr>
  <tr><td>Ace Combat Advance(US)</td><td>Namco</td><td>AGB-BAEE-USA</td><td>23/02/05</td></tr>
  <tr><td>Ace Combat Advance(EU)</td><td>Atari SA</td><td>AGB-BAEP-EUR</td><td>25/08/06</td></tr>
  <tr><td>Ace Lightning</td><td>Gamezlab</td><td>AGB-ALXP-EUR</td><td>25/10/02</td></tr>
  <tr><td>Action Man: Robot Atak</td><td>Atari SA</td><td>AGB-BACP-EUR</td><td>24/09/04</td></tr>
  <tr><td>Activision Anthology</td><td>Aspyr</td><td>AGB-BAVE-USA</td><td>09/12/03</td></tr>
  <tr><td>Advance Guardian Heroes(US)</td><td>Ubisoft</td><td>AGB-BGCE-USA</td><td>14/09/04</td></tr>
  <tr><td>Advance Guardian Heroes(JP)</td><td>Treasure</td><td>AGB-BAGJ-JPN</td><td>22/09/04</td></tr>
  <tr><td>Advance Guardian Heroes(EU)</td><td>Ubisoft</td><td>AGB-BGCP-EUR</td><td>18/02/05</td></tr>
  <tr><td>Advance Wars(US)</td><td>Nintendo</td><td>AGB-AWRE-USA</td><td>09/09/01</td></tr>
  <tr><td>Advance Wars(AU)</td><td>Nintendo</td><td>AGB-AWRU-AUS</td><td>2001</td></tr>
  <tr><td>Advance Wars(EU)</td><td>Nintendo</td><td>AGB-AWRP-EUR</td><td>11/01/02</td></tr>
  <tr><td></td><td></td><td></td><td></td></tr>
 </tbody>
</table>

<onebutton>
<ul>
            <li><a href="../">Go<strong>Back</strong></a></li>
          </ul>
</onebutton>
