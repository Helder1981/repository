<link href="table.css" rel="stylesheet">
<script src="jquery-3.2.1.min.js"></script>
<script type="text/javascript" charset="utf8" src="//cdn.datatables.net/1.10.16/js/jquery.dataTables.js"></script>
<script>
$(document).ready( function () {
    $('#FlashTable').DataTable( {
        paging: false,
		searching: true,
		dom: 'tpri'
    } );
} );
</script>

<script>
function searchFunction() {

    var table = $('#FlashTable').DataTable();
	var input = document.getElementById("FlashInput");
    table.search( input.value ).draw();
};
</script>

## NDS Flashcart Firmware/Software

Note: Scans might contain False Positives.

<input type="text" id="FlashInput" onkeyup="searchFunction()" placeholder="Search for Flashcarts">

<table id="FlashTable" class="display">
    <thead>
        <tr>
            <th>Name</th>
            <th>Website</th>
			<th>DSi</th>
			<th>Version</th>
			<th>Scan</th>
        </tr>
    </thead>
    <tbody>
    <tr>
	    <td><a href="AceKard.zip">AceKard</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>No</td>
		<td>1.10</td>
		<td><a href="https://www.virustotal.com/#/file/88b88e2615f4d20aec63919a9994c1ee940e33388de2bd36340671e1469e2bc1/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="Acekard2.zip">AceKard 2</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>No</td>
		<td>4.23</td>
		<td><a href="https://www.virustotal.com/#/file/037ec6bb9f6f56a5bbeaed6aebee578bf14056c02b70fcfdcfdb92c5e69aaa14/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="Acekard21.zip">Acekard 2.1</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>No</td>
		<td>1.8.1</td>
		<td><a href="https://www.virustotal.com/#/file/5765a29cfa045cce9b9d5db6ef201c4baf143cf02b067e4de31e12f13594642f/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="Acekard2i.zip">Acekard 2i</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>Yes</td>
		<td>1.4.1</td>
		<td><a href="https://www.virustotal.com/#/file/6c7dbe833a0b7835ed4267968e675860ccba0b4d27b845d96902fdc48fa6a0e8/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="AcekardRPG.zip">Acekard RPG</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>No</td>
		<td>1.16</td>
		<td><a href="https://www.virustotal.com/#/file/6a2c63cc41db41da15c9eb459f3c0f2f13e803c4d6dece4838d3d7b3b5eeb33f/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="Acekard+.zip">Acekard+</a></td>
		<td><a href="http://www.acekard.com">Website</a></td>
		<td>No</td>
		<td>1.15</td>
		<td><a href="https://www.virustotal.com/#/file/42b415daa454f0705e7ce14a662362130bfd5824c629149f58c4a0e74002b687/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="CycoloDSEvo.zip">CycloDS Evolution</a></td>
		<td><a href="http://www.cyclopsds.com">Website</a></td>
		<td>No</td>
		<td>2.3|1.59|B.4</td>
		<td><a href="https://www.virustotal.com/#/file/ecc4a0fab6cdc9f0c8203a029ae6be5b690f606405d31fc1f33ce9602cb02d93/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DSFireLink.zip">DS Fire Link</a></td>
		<td><a href="http://dsfirelink.com">Website</a></td>
		<td>No</td>
		<td>1.45</td>
		<td><a href="https://www.virustotal.com/#/file/63ad22aec84e799ea78cf8e069127f8add4d69e83c9ff12cd40b2b29d8fb4f5c/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DSLink.zip">DS Link</a></td>
		<td><a href="http://www.ds-link.net/">Website</a></td>
		<td>No</td>
		<td>2.32</td>
		<td><a href="https://www.virustotal.com/#/file/e13c9b1c208aabbbefd0c79689d5985a1d0876aaf9b36baecb78ea7fc591ecc5/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DSLinker.zip">DSLinker</a></td>
		<td><a href="http://www.dslinker.com/">Website</a></td>
		<td>No</td>
		<td>1.45</td>
		<td><a href="https://www.virustotal.com/#/file/53599e749ff0ab7dc3b4dad0511f11fe04eca27948c8410ded48a9b80f279284/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DSTT.zip">DSTT</a></td>
		<td><a href="http://www.ndstt.com/">Website</a></td>
		<td>Yes</td>
		<td>N/A</td>
		<td><a href="https://www.virustotal.com/#/file/5ff790beb2def9b2d6501aab620bd62b92157015044f2ddd0a429c2cf19685d9/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DSTTi.zip">DSTTi</a></td>
		<td><a href="http://www.ndstt.com/">Website</a></td>
		<td>Yes</td>
		<td>1.4.1</td>
		<td><a href="https://www.virustotal.com/#/file/5ff790beb2def9b2d6501aab620bd62b92157015044f2ddd0a429c2cf19685d9/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="DS-Xtreme.zip">DS-Xtreme</a></td>
		<td><a href="http://www.ds-x.com/">Website</a></td>
		<td>No</td>
		<td>1.1.3</td>
		<td><a href="https://www.virustotal.com/#/file/42da2af0402216452f76860014af0b332dfe51c48aafb4cb5a03c9601cc6ee76/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="E7.zip">E7</a></td>
		<td>N/A</td>
		<td>No</td>
		<td>2.01</td>
		<td><a href="https://www.virustotal.com/#/file/8177fb04f2a6eee76907f6a6e74355bd87a6e91e83b7f5585519036e20d8fc04/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="EDGE.zip">EDGE</a></td>
		<td><a href="http://www.edge-ds.cn/">Website</a></td>
		<td>No</td>
		<td>1.11</td>
		<td><a href="https://www.virustotal.com/#/file/6ea7ee0e636254a18cfb945933aaa380c265f7bd59d855ce9966e176b230d9e0/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="eWin2.zip">eWin2</a></td>
		<td><a href="http://www.ewin2.net/">Website</a></td>
		<td>No</td>
		<td>1.96.8</td>
		<td><a href="https://www.virustotal.com/#/file/ffd271657722f53e2cda71daaa093e14d8ef9f3d66808ec45837b7c2400ed8ec/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="EZ-FlashIV.zip">EZ-Flash IV</a></td>
		<td><a href="http://www.ezflash.cn/">Website</a></td>
		<td>No</td>
		<td>2.05</td>
		<td><a href="https://www.virustotal.com/#/file/8881506392478848b57c7726924ea8437c6b0cd5b51715577682b563333523c5/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="EZ-FlashV.zip">EZ-Flash V</a></td>
		<td><a href="http://www.ezflash.cn/">Website</a></td>
		<td>No</td>
		<td>2.0 RC20</td>
		<td><a href="https://www.virustotal.com/#/file/21284ae2b6d2601b7474023e58f16663961646bb063492d503b4d19ec8519c15/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="EZ-FlashV.zip">EZ-Flash V+</a></td>
		<td><a href="http://www.ezflash.cn/">Website</a></td>
		<td>No</td>
		<td>2.0 RC20</td>
		<td><a href="https://www.virustotal.com/#/file/21284ae2b6d2601b7474023e58f16663961646bb063492d503b4d19ec8519c15/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="EZ-FlashVi.zip">EZ-Flash Vi</a></td>
		<td><a href="http://www.ezflash.cn/">Website</a></td>
		<td>Yes</td>
		<td>3.0ob8|108a</td>
		<td><a href="https://www.virustotal.com/#/file/5a4ca734c46325861d9f3b2b6efb975ad90de43295670347992d71575bef352c/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="G6DSReal.zip">G6 DS Real</a></td>
		<td><a href="http://www.g6flash.com/">Website</a></td>
		<td>No</td>
		<td>4.8f</td>
		<td><a href="https://www.virustotal.com/#/file/ef4eff8926be19053d763601339fdeaf164133152fdac7b01bec08127315ee74/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="G6Flash.zip">G6 Flash</a></td>
		<td><a href="http://www.g6flash.com/">Website</a></td>
		<td>No</td>
		<td>4.8|5.1</td>
		<td><a href="https://www.virustotal.com/#/file/626e4ad774f4d62d617271971fa7667fceeda11a4cf82256af89a6e754c0338a/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="G6Flash.zip">G6 Lite</a></td>
		<td><a href="http://www.g6flash.com/">Website</a></td>
		<td>No</td>
		<td>4.8|5.1</td>
		<td><a href="https://www.virustotal.com/#/file/626e4ad774f4d62d617271971fa7667fceeda11a4cf82256af89a6e754c0338a/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="GamesNMusic.zip">Games'N'Music</a></td>
		<td><a href="http://us.codejunkies.com/Products/NDS-Games-n-Music__EF000155.aspx">Website</a></td>
		<td>N/A</td>
		<td>N/A</td>
		<td><a href="https://www.virustotal.com/#/file/95a60d70f0d05412afb27ee3f2068f212b5cd6c700e1cd2c0111003f4ad73d86/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="GEiDS.zip">GEi DS</a></td>
		<td><a href="http://www.ge.ndsi.in/">Website</a></td>
		<td>Yes</td>
		<td>4.2</td>
		<td><a href="https://www.virustotal.com/#/file/025af37e5e6d1c5c65d069b753cd95f3cf55c1c263ac9a621e25c6dd9ec7ba21/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="iEDGE.zip">iEDGE</a></td>
		<td><a href="http://www.edge-ds.cn/">Website</a></td>
		<td><1.4</td>
		<td>1.11</td>
		<td><a href="https://www.virustotal.com/#/file/3f46f0ca422de4220a9e62a553127650f7e5f58ce1fce7c0b9ff699458f9871b/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="iPlayer.zip">iPlayer</a></td>
		<td><a href="http://www.dsiplayer.com/">Website</a></td>
		<td>Yes</td>
		<td>1.06|1.41</td>
		<td><a href="https://www.virustotal.com/#/file/52920dbf0c2e29d41df0bc7b4531e5dd610719e1bf2653a89f7eb0777451500b/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="iSmartPremium.zip">iSmart Premium</a></td>
		<td><a href="http://ismartds.com">Website</a></td>
		<td>Yes</td>
		<td>1.05</td>
		<td><a href="https://www.virustotal.com/#/file/f2c01d507db8061890636191c02ba52d76bafbc4c07109b4797bd7b2a8dcf283/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="iTouch2.zip">iTouch2</a></td>
		<td><a href="http://www.itouchds.com/">Website</a></td>
		<td>Yes</td>
		<td>3.8e</td>
		<td><a href="https://www.virustotal.com/#/file/762836f15e02cdca4aa44a3b307c6e076c5e12387791222a67a487c30de076e1/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3DS.zip">M3 DS Real</a></td>
		<td><a href="http://m3adapter.com">Website</a></td>
		<td>No</td>
		<td>1.49X|4.9</td>
		<td><a href="https://www.virustotal.com/#/file/b4fd80b7a910d9ae86eb46ed8023baf4d985754ef1bedfe0d630f085db1fd1e9/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3DS.zip">M3 Perfect</a></td>
		<td><a href="http://m3adapter.com">Website</a></td>
		<td>No</td>
		<td>1.49X|4.9</td>
		<td><a href="https://www.virustotal.com/#/file/b4fd80b7a910d9ae86eb46ed8023baf4d985754ef1bedfe0d630f085db1fd1e9/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3Simply.zip">M3 Simply</a></td>
		<td><a href="http://m3adapter.com">Website</a></td>
		<td>N/A</td>
		<td>1.62</td>
		<td><a href="https://www.virustotal.com/#/file/2ff2c74ad99bea334ccb11a523d70bd5c380e8aa8ac6fee66365f89895f9eedc/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3iSDHC.zip">M3i SDHC</a></td>
		<td><a href="http://m3isdhc.com/">Website</a></td>
		<td>Yes</td>
		<td>1.4</td>
		<td><a href="https://www.virustotal.com/#/file/8ba574ecb302ede271cb32aa09a03154a5c9e8a3a9e5213e7cbca09665f4062d/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3iUpgrade.zip">M3i Upgrade</a></td>
		<td>N/A</td>
		<td>Yes</td>
		<td>1.45</td>
		<td><a href="https://www.virustotal.com/#/file/b2d8e7cf6c1730aaf124ab9741032267dbe25fea38053cbd6ed177c15f97bee0/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3iZero.zip">M3i Zero</a></td>
		<td><a href="http://m3adapter.com">Website</a></td>
		<td>Yes</td>
		<td>4.5.0|1.49X|4.9</td>
		<td><a href="https://www.virustotal.com/#/file/3abb9a4b7af96da4ad44cda5dd6880e8c4f16be8e9b944a1cf272db997e9be97/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="M3lUpgrade.zip">M3l Upgrade</a></td>
		<td><a href="http://m3iupgrade.com/">Website</a></td>
		<td>Yes</td>
		<td>1.45</td>
		<td><a href="https://www.virustotal.com/#/file/4ab30ab38876e94b5f387a53f8b7c2dd8154347a59dfa1af930f57a1a123b87f/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="MARS.zip">MARS</a></td>
		<td>N/A</td>
		<td>N/A</td>
		<td>1.03</td>
		<td><a href="https://www.virustotal.com/#/file/eae83fdf02f738d256549156b59b7ffc55b1d999eee775bd70d179d1e20b4a14/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="MaxMediaPlayer.zip">Max Media Player</a></td>
		<td><a href="http://us.codejunkies.com/mpds/index.htm">Website</a></td>
		<td>N/A</td>
		<td>1.22</td>
		<td><a href="https://www.virustotal.com/#/file/525449834667955d61c9498d4cd66b865c28ef9f2edbcfaf11c28320185124a6/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="MK5.zip">MK5</a></td>
		<td><a href="http://www.neoflash.com">Website</a></td>
		<td>No</td>
		<td>2.56</td>
		<td><a href="https://www.virustotal.com/#/file/7b3ad8014471443a6501ff4de68f0222322dcc6324069c27cbf2cb6614e12472/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="N5.zip">N5</a></td>
		<td><a href="http://www.dsn5.com/EN-N5/n5-en.htm">Website</a></td>
		<td>N/A</td>
		<td>1.32</td>
		<td><a href="https://www.virustotal.com/#/file/fb2e9b0a72fc08bd06f53d53d28a8a5d7d2501eb8c7a70185c2cb1b73ae2b1d0/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="N5i.zip">N5i</a></td>
		<td><a href="http://www.dsn5.com/EN-N5/n5-en.htm">Website</a></td>
		<td>Yes</td>
		<td>2.03</td>
		<td><a href="https://www.virustotal.com/#/file/9506fefc273ef3f2c751adb332813fb1aca20b2b5c4b6f9365c513c87e069d6b/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="N-Card.zip">N-Card</a></td>
		<td>N/A</td>
		<td>No</td>
		<td>v25</td>
		<td><a href="https://www.virustotal.com/#/file/e88ae06f7ea692aae7814d2b5dc7257ba60ef9838cac40acebc375eac530e7c8/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="R43DS.zip">R4 3DS Upgrade SDHC Dual-Core RTS</a></td>
		<td><a href="http://r4-usas.com/">Website</a></td>
		<td>Yes</td>
		<td>3.9b</td>
		<td><a href="https://www.virustotal.com/#/file/87199364c910763689d0497ddec36d83f6169a1d613e831cb00980ab3162dc00/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="R4DS.zip">R4 DS</a></td>
		<td><a href="http://www.r4ds.com/">Website</a></td>
		<td>No</td>
		<td>1.62</td>
		<td><a href="https://www.virustotal.com/#/file/5c4dc90c03ebd82af786deefbcbf80940dc21e1159379db8448d962de9de9c07/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="R4SDHCUpgrade.zip">R4 SDHC Upgrade</a></td>
		<td><a href="http://www.r4i-sdhc.com/">Website</a></td>
		<td>No</td>
		<td>1.27b</td>
		<td><a href="https://www.virustotal.com/#/file/6668835406235ba2b215db811f8b25616c554770e99fa178617b2dbb02a96e33/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="R4Ultra.zip">R4 Ultra</a></td>
		<td><a href="http://www.r4ultra.com">Website</a></td>
		<td>N/A</td>
		<td>1.56</td>
		<td><a href="https://www.virustotal.com/#/file/cc17c9d1156f2d6549be3dc1eb962276d495f8c7ef0e94b5f1b9aa885b555778/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="SuperR4i.zip">Super R4i</a></td>
		<td><a href="http://www.super4i.com/">Website</a></td>
		<td>Yes</td>
		<td>1.20</td>
		<td><a href="https://www.virustotal.com/#/file/d29fb6c767c7e0561625b8edc3ea7658548e1cf6294820aea416025365ea99ff/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="SuperCardDSONE.zip">SuperCard DSONE</a></td>
		<td><a href="http://eng.supercard.sc/">Website</a></td>
		<td>No</td>
		<td>1.0</td>
		<td><a href="https://www.virustotal.com/#/file/976d949f38d2e0eb04c59f9e1a63842a80257bda2971be86c22078c027b06607/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="SuperCardDSONE.zip">SuperCard DSONE v3</a></td>
		<td><a href="http://eng.supercard.sc/">Website</a></td>
		<td>No</td>
		<td>1.0</td>
		<td><a href="https://www.virustotal.com/#/file/976d949f38d2e0eb04c59f9e1a63842a80257bda2971be86c22078c027b06607/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="SuperCardDSONEi.zip">SuperCard DSONEi</a></td>
		<td><a href="http://eng.supercard.sc/">Website</a></td>
		<td>Yes</td>
		<td>1.0|1.1|1.4.1</td>
		<td><a href="https://www.virustotal.com/#/file/be4e5174942947c28823c57dcd9227361b9a6b8135c3d4357a3c171eaf619872/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="SuperCardDSTWO.zip">SuperCard DSTWO</a></td>
		<td>N/A</td>
		<td>Yes</td>
		<td>1.30</td>
		<td><a href="https://www.virustotal.com/#/file/61157adf51692dd680320c1e9e39516c894ee5c8ebee9d1a29eadd8bb06785a0/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="TTiUpgrade.zip">TTi Upgrade</a></td>
		<td><a href="http://www.nds-tti.com">Website</a></td>
		<td>Yes</td>
		<td>1.19</td>
		<td><a href="https://www.virustotal.com/#/file/167bb060fe7588c1afd649aabd388489c71ccf2f8f3b55e25969fa01418e4f09/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="U2DS.zip">U2DS</a></td>
		<td><a href="http://www.u2ds.com/">Website</a></td>
		<td>N/A</td>
		<td>1.7c</td>
		<td><a href="https://www.virustotal.com/#/file/2d971101b40188b980a443d1f82bfdd183e8af73ab2d60612994aba93462ac08/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="UltraFlashpassEx.zip">Ultra Flashpass Ex</a></td>
		<td><a href="http://www.ndsgba.net/">Website</a></td>
		<td>N/A</td>
		<td>1.45</td>
		<td><a href="https://www.virustotal.com/#/file/e22c40e6bc5f95814580ef4f9f4b179df09c5ad0683d8fd52062519ac1180617/detection">Scan</a></td>
	</tr>
    <tr>
	    <td><a href="R4i_RTS_3DS.zip">R4i RTS 3DS</a></td>
		<td><a href="http://r4ids.cn/">Website</a></td>
		<td>Yes</td>
		<td>1.64</td>
		<td><a href="https://www.virustotal.com/#/file/5e36a6389b2641bf2569d3e232c4ef3cdd452a5f7d5d8c93aae5a0bd56d678cd/detection">Scan</a></td>
	</tr>
 </tbody>
</table>

<onebutton>
<ul>
            <li><a href="../">Go<strong>Back</strong></a></li>
          </ul>
</onebutton>
