
# Afbakeningsregels van registratie van overbouw en onderbouw {#792BF0F2}
<span style='color: #auto;'>Delen van panden die zich boven maaiveld bevinden (overbouw): </span>  
<ol type='1'><li><span style='color: #auto;'>De geometrie van overbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &gt; 0.</span></li>
<li><span style='color: #auto;'>Een overbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (relatieve hoogte is 0) aanwezig is, met uitzondering van de in paragraaf 10.7.1 van de catalogus BGT 2.1 genoemde uitzonderingen. Zie voorbeeld A in de Bijlage.</span></li>
<li><span style='color: #auto;'>Alleen de </span><span style='color: #auto;'><u>uít</u></span><span style='color: #auto;'>stekende delen - uítstekend ten opzichte van maaiveld - van de overbouw worden afgebakend (zoals uitkragende delen van panden);</span></li>
<li><span style='color: #auto;'>De geometrie van </span><span style='color: #auto;'><u>uít</u></span><span style='color: #auto;'>stekende delen (zoals verblijfsruimtes hangend boven maaiveld) krijgen een relatieve hoogte &gt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</span></li>
<li><span style='color: #auto;'>Meerdere overbouwen met dezelfde relatieve hoogte &gt; 0 die bij één BGT pand horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &gt; 0 (dus niet als </span><span style='color: #auto;'>multi</span><span style='color: #auto;'>-geometrie);</span></li>
<li><span style='color: #auto;'>Overlapping is alleen toegestaan tussen geometrieën van overbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van overbouw met gelijke relatieve hoogte.</span></li>
<li><span style='color: #auto;'>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de overbouw.</span></li>
</ol>
<br/>
<br/>
<span style='color: #auto;'>Delen van panden die zich onder maaiveld bevinden (onderbouw):</span>  
<ol type='1'><li><span style='color: #auto;'>De geometrie van onderbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &lt; 0.</span></li>
<li><span style='color: #auto;'>Een onderbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (met relatieve hoogte = 0), aanwezig is.</span></li>
<li><span style='color: #auto;'>Geheel ondergrondse panden, - die niet horen bij een  pand op maaiveld, met status bestaand én met dezelfde BAG-identificatie -, zijn geen onderbouw. Ze worden met een relatieve hoogte &lt; 0 vastgelegd  en zijn daarmee een uitzondering op de regel dat panden altijd op maaiveld liggen, net als bv </span><span style='color: #auto;'>brugwachterhuisjes</span><span style='color: #auto;'> ook een uitzondering zijn. Zie voorbeeld C in de bijlage.</span></li>
<li><span style='color: #auto;'>Alleen de </span><span style='color: #auto;'><u>uít</u></span><span style='color: #auto;'>stekende delen - uítstekend ten opzichte van maaiveld - van de onderbouw worden afgebakend (zoals uitkragende delen van panden);</span></li>
<li><span style='color: #auto;'>De geometrie van uítstekende delen (zoals kelders of inpandige parkeergarages) krijgen een relatieve hoogte &lt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</span></li>
<li><span style='color: #auto;'>Meerdere onderbouwen met dezelfde relatieve hoogte &lt; 0 die bij één BGT pand horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &lt; 0  (dus niet als </span><span style='color: #auto;'>multi</span><span style='color: #auto;'>-geometrie);</span></li>
<li><span style='color: #auto;'>Overlapping is alleen toegestaan tussen geometrieën van onderbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van onderbouw met gelijke relatieve hoogte.</span></li>
<li><span style='color: #auto;'>Als één BAG pand ondergrondse delen (bijvoorbeeld parkeerkelder) én bovengrondse delen (bijvoorbeeld ingangen/trappenhuisjes/liften/ etc.) heeft (die niet als afzonderlijk BAG pand(en) zijn benoemd), dan worden:</span><ul><li>    <span style='color: #auto;'>De  bovengrondse delen als BGT pand op maaiveld vastgelegd (multivlak als het meerdere losse delen zijn)</span></li>
<li>    <span style='color: #auto;'>Het ondergrondse deel wordt vastgelegd als onderbouw, met hetzelfde BAG-identificatie, waarbij alleen de uítstekende delen van de geometrie worden opgenomen(d.w.z. dat de ingangen/trappenhuisjes/liften/ etc. uitgesneden worden in de geometrie van de onderbouw). Zie voorbeeld B.</span></li>
</ul>
</li>
<li><span style='color: #auto;'>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de onderbouw.</span></li>
</ol>
<br/>
<br/>
<span style='color: #auto;'>Panden op maaiveld:</span>  
<ol type='1'><li><span style='color: #auto;'>Geometrie van panden op maaiveld blijven op </span><i><span style='color: #auto;'>relatieve hoogte = 0 </span></i><span style='color: #auto;'>en de afzonderlijke geometrieën vormen samen een </span><span style='color: #auto;'>multi</span><span style='color: #auto;'>-vlak.</span></li>
</ol>
<br/>
<br/>
<span style='color: #auto;'>Totale pand:</span>  
<ol type='1'><li><span style='color: #auto;'>De samengestelde 2D-projectie van alle geometrieën van het BGT pand bij elkaar, waarbij onderlinge overlap is geëlimineerd, is topologisch aangesloten én is gelijk aan de BAG geometrie van dat pand.</span></li>
<li><span style='color: #auto;'>Van de BGT panden met dezelfde BAG-identificatie mag maar één BGT pand de volledige </span><span style='color: #auto;'>nummeraanduidingsreeks</span><span style='color: #auto;'> (NAR) krijgen, die gerelateerd is aan dat BAG-pand. Deze NAR wordt geplaatst in een BGT pand (met status = bestaand) met een relatieve hoogte = 0. Voor een geheel ondergronds pand met relatieve hoogte &lt; 0 wordt de NAR in dat pand geplaatst.</span></li>
</ol>
