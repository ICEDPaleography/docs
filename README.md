Welcome to the **Initiative for Central Eurasian Digital Palaeography** (ICEDPaleography)!

## About this project
The point of this project is to develop Free and Open digital resources for the historical writings of Central Eurasia.  The current goals primarily include **fonts** and **keyboards** for the historical scripts of Central Eurasia.

## Scripts
The following scripts are priorities:
<table>
   <tr>
      <th colspan="2">script name</th>
      <th>direction</th>
      <th>unicode block</th>
      <th>related script</th>
      <th>developed fonts</th>
      <th>other fonts</th>
   </tr>
   <tr>
      <th colspan="2">Imperial Aramaic</th>
      <td>RtL, TtB</td>
      <td>U+10840-U+1085F</td>
      <td></td>
      <td>Khulmi</td>
   </tr>
   <tr>
      <th colspan="2">Orkhon-Yenisei runiform script</th>
      <td>RtL, TtB</td>
      <td>U+10C0X-U+10C4X</td>
      <td>—</td>
      <td>Irq Bitig</td>
      <td>Orkun, <a href="http://www.ukij.org/fonts/">UKIJ Orxun-Yensey</a></td>
   </tr>
   <tr>
      <th rowspan="2">Sogdian script</th>
      <th>Ancient</th>
      <td>U+10F00-U+10F2F</td>
   </tr>
   <tr>
      <th>Cursive</th>
      <td>U+10F30-U+10F6F</td>
   </tr>
   <tr>
      <th colspan="2">Old Uyghur script</th>
      <td>TtB, LtR</td>
      <td><b>no</b> (U+180X-U+18AX)</td>
      <td>Mongolian</td>
      <td></td>
      <td><a href="http://www.ukij.org/fonts/">UKIJ Orxun-Yensey</a>, <a href="http://www.daicing.com/manchu/index.php?page=fonts-downloads">Daicing</a></td>
   </tr>
   <tr>
      <th colspan="2">'Phags-pa script</th>
      <td></td>
      <td>U+A84X-U+A87X</td>
      <td>—</td>
      <td></td>
      <td>BabelStone Phags-pa Book, Microsoft PhagsPa, Code2000</td>
   </tr>
   <tr>
      <th colspan="2">Manichaean script</th>
      <td></td>
      <td><b>no</b> (U+070X-U+074X)</td>
      <td>Syriac</td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <th colspan="2">[[Pahlavi script]]</th>
      <td>RtL, TtB</td>
      <td>U+10B6X-U+10B7X</td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <th colspan="2">Avestan script</th>
      <td>RtL, TtB</td>
      <td>U+10B0X-U+10B3X</td>
      <td></td>
      <td></td>
      <td>Ahuramzda, Zavesta, Avestan</td>
   </tr>
   <tr>
      <th colspan="2">[[Tokharian Brāhmī]]</th>
      <td>LtR, TtB</td>
      <td><b>no</b></td>
      <td></td>
      <td>Brāhmī <a href="http://www.unicode.org/L2/L2003/03249r-brahmi-proposal.pdf">(an old proposal including Tokharian)</a></td>
      <td></td>
   </tr>
   <tr>
      <th rowspan="2">Bactrian</th>
      <th>Inscriptional</th>
      <td rowspan="2">LtR, TtB</td>
      <td rowspan="2"><b>no</b> (U+037X-U+03FX)</td>
      <td rowspan="2">Greek</td>
      <td rowspan="2"></td>
   </tr>
   <tr>
      <th>Cursive</th>
   </tr>
   <tr>
      <th colspan="2">Kitań large script</th>
      <td></td>
      <td><b>no</b></td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <th colspan="2">Kitań small script</th>
      <td></td>
      <td><b>no</b></td>
      <td></td>
      <td></td>
   </tr>
</table>
## Taking part
If you'd like to join us to work towards developing fonts for any of these writing systems, please contact us!

## The process
The general process we're taking for developing fonts is as follows:

1. Gather images of manuscripts in the style you want your font to appear.
2. Copy characters from the manuscript and add them as individual images in `dev/sources/yourfont/`.
3. Trace (and edit) a version of each character add each one as an SVG in `dev/svg/yourfont/`.
4. Having determined what unicode codepoint you're going to use for each character, import the SVG into that code point of a font, and save the font in `fonts/yourfont`.
