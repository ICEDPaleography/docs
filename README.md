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
      <td>TtB, LtR</td>
      <td>U+10F00-U+10F2F</td>
   </tr>
   <tr>
      <th>Cursive</th>
      <td>RtL, TtB</td>
      <td>U+10F30-U+10F6F</td>
   </tr>
   <tr>
      <th colspan="2">Old Uyghur script</th>
      <td>TtB, LtR</td>
      <td>U+10F70-U+10FAF</td>
      <td></td>
      <td></td>
      <td><a href="http://www.ukij.org/fonts/">UKIJ Orxun-Yensey</a>, <a href="http://www.daicing.com/manchu/index.php?page=fonts-downloads">Daicing</a>, <a href="https://www.turkolog.ist/">Islamic Old Uyghur</a></td>
   </tr>
   <tr>
      <th rowspan="2">Bactrian</th>
      <th>Inscriptional</th>
      <td rowspan="2">LtR, TtB</td>
      <td rowspan="2">U+101F0-U+1010FF</td>
      <td rowspan="2">Greek</td>
      <td rowspan="2"></td>
   </tr>
   <tr>
      <th>Cursive</th>
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
      <th colspan="2">Pahlavi script</th>
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
      <th colspan="2">Northern Tarim Brāhmī (Tokharian)</th>
      <td>LtR, TtB</td>
      <td><b>no</b> (U+11E00-U+11E6F)</td>
      <td></td>
      <td>Brāhmī <a href="http://www.unicode.org/L2/L2003/03249r-brahmi-proposal.pdf">(an old proposal including Tokharian)</a>, <a href="https://www.unicode.org/L2/L2014/14192-turkestani.pdf">(Turkestani proposal, includes Khotanese)</a>, <a href="https://www.unicode.org/L2/L2015/15023-tocharian.pdf">(Tokharian-specific proposal)</a></td>
      <td></td>
   </tr>
   <tr>
      <th colspan="2">Southern Tarim Brāhmī (Khotanese)</th>
      <td>LtR, TtB</td>
      <td><b>no</b> (U+11E70-U+11ECF)</td>
      <td></td>
      <td>Brāhmī <a href="https://www.unicode.org/L2/L2015/15022-khotanese.pdf">(Khotanese-specific proposal)</a></td>
      <td></td>
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
