# readme engine

### Events

Event    | Description
:------------- | :-------------
connect  | emits when a connection is established to the Redis server.
ready    | emits when `CLUSTER INFO` reporting the cluster is able to receive commands (if `enableReadyCheck` is `true`) or immediately after `connect` event (if `enableReadyCheck` is false).
error    | emits when an error occurs while connecting with a property of `lastNodeError` representing the last node error received. This event is emitted silently (only emitting if there's at least one listener).
close    | emits when an established Redis server connection has closed.
reconnecting | emits after `close` when a reconnection will be made. The argument of the event is the time (in ms) before reconnecting.
end     | emits after `close` when no more reconnections will be made.
+node   | emits when a new node is connected.
-node   | emits when a node is disconnected.
node error | emits when an error occurs when connecting to a node


# Contributors
<table>
  <tr>
    <td width="20%"><a href="https://github.com/luin"><img src="https://avatars2.githubusercontent.com/u/635902?v=4" /></a><p align="center">luin</p></td>
    <td width="20%"><a href="https://github.com/shaharmor"><img src="https://avatars3.githubusercontent.com/u/10861920?v=4" /></a><p align="center">shaharmor</p></td>
    <td width="20%"><a href="https://github.com/iamjochem"><img src="https://avatars0.githubusercontent.com/u/792188?v=4" /></a><p align="center">iamjochem</p></td>
    <td width="20%"><a href="https://github.com/doublesharp"><img src="https://avatars3.githubusercontent.com/u/571472?v=4" /></a><p align="center">doublesharp</p></td>
    <td width="20%"><a href="https://github.com/nakulgan"><img src="https://avatars3.githubusercontent.com/u/189836?v=4" /></a><p align="center">nakulgan</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/AVVS"><img src="https://avatars1.githubusercontent.com/u/1713617?v=4" /></a><p align="center">AVVS</p></td>
    <td width="20%"><a href="https://github.com/ramonsnir"><img src="https://avatars1.githubusercontent.com/u/1024028?v=4" /></a><p align="center">ramonsnir</p></td>
    <td width="20%"><a href="https://github.com/hayeah"><img src="https://avatars2.githubusercontent.com/u/50120?v=4" /></a><p align="center">hayeah</p></td>
    <td width="20%"><a href="https://github.com/albin3"><img src="https://avatars3.githubusercontent.com/u/6190670?v=4" /></a><p align="center">albin3</p></td>
    <td width="20%"><a href="https://github.com/phlip9"><img src="https://avatars0.githubusercontent.com/u/918989?v=4" /></a><p align="center">phlip9</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/chris-olszewski"><img src="https://avatars1.githubusercontent.com/u/4131117?v=4" /></a><p align="center">chris-olszewski</p></td>
    <td width="20%"><a href="https://github.com/fracmak"><img src="https://avatars1.githubusercontent.com/u/378178?v=4" /></a><p align="center">fracmak</p></td>
    <td width="20%"><a href="https://github.com/ddunkin"><img src="https://avatars2.githubusercontent.com/u/264744?v=4" /></a><p align="center">ddunkin</p></td>
    <td width="20%"><a href="https://github.com/ruimarinho"><img src="https://avatars0.githubusercontent.com/u/288709?v=4" /></a><p align="center">ruimarinho</p></td>
    <td width="20%"><a href="https://github.com/suprememoocow"><img src="https://avatars0.githubusercontent.com/u/594566?v=4" /></a><p align="center">suprememoocow</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/jpallen"><img src="https://avatars0.githubusercontent.com/u/31305?v=4" /></a><p align="center">jpallen</p></td>
    <td width="20%"><a href="https://github.com/reconbot"><img src="https://avatars2.githubusercontent.com/u/25966?v=4" /></a><p align="center">reconbot</p></td>
    <td width="20%"><a href="https://github.com/lpinca"><img src="https://avatars0.githubusercontent.com/u/1443911?v=4" /></a><p align="center">lpinca</p></td>
    <td width="20%"><a href="https://github.com/frankvm04"><img src="https://avatars1.githubusercontent.com/u/796475?v=4" /></a><p align="center">frankvm04</p></td>
    <td width="20%"><a href="https://github.com/jeffjen"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">jeffjen</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/SamBergeron"><img src="https://avatars1.githubusercontent.com/u/3879294?v=4" /></a><p align="center">SamBergeron</p></td>
    <td width="20%"><a href="https://github.com/seoker"><img src="https://avatars1.githubusercontent.com/u/7975797?v=4" /></a><p align="center">seoker</p></td>
    <td width="20%"><a href="https://github.com/southpolesteve"><img src="https://avatars1.githubusercontent.com/u/471400?v=4" /></a><p align="center">southpolesteve</p></td>
    <td width="20%"><a href="https://github.com/devaos"><img src="https://avatars0.githubusercontent.com/u/5412167?v=4" /></a><p align="center">devaos</p></td>
    <td width="20%"><a href="https://github.com/headquarters"><img src="https://avatars0.githubusercontent.com/u/347079?v=4" /></a><p align="center">headquarters</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/9point6"><img src="https://avatars1.githubusercontent.com/u/627697?v=4" /></a><p align="center">9point6</p></td>
    <td width="20%"><a href="https://github.com/horx"><img src="https://avatars2.githubusercontent.com/u/1332618?v=4" /></a><p align="center">horx</p></td>
    <td width="20%"><a href="https://github.com/darrachequesne"><img src="https://avatars3.githubusercontent.com/u/13031701?v=4" /></a><p align="center">darrachequesne</p></td>
    <td width="20%"><a href="https://github.com/damianhodgkiss"><img src="https://avatars2.githubusercontent.com/u/4359427?v=4" /></a><p align="center">damianhodgkiss</p></td>
    <td width="20%"><a href="https://github.com/ColmHally"><img src="https://avatars3.githubusercontent.com/u/20333?v=4" /></a><p align="center">ColmHally</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/klinquist"><img src="https://avatars2.githubusercontent.com/u/1343376?v=4" /></a><p align="center">klinquist</p></td>
    <td width="20%"><a href="https://github.com/alsotang"><img src="https://avatars1.githubusercontent.com/u/1147375?v=4" /></a><p align="center">alsotang</p></td>
    <td width="20%"><a href="https://github.com/zhuangya"><img src="https://avatars2.githubusercontent.com/u/499038?v=4" /></a><p align="center">zhuangya</p></td>
    <td width="20%"><a href="https://github.com/taichunmin"><img src="https://avatars3.githubusercontent.com/u/2192626?v=4" /></a><p align="center">taichunmin</p></td>
    <td width="20%"><a href="https://github.com/Gerhut"><img src="https://avatars1.githubusercontent.com/u/2500247?v=4" /></a><p align="center">Gerhut</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/barwin"><img src="https://avatars3.githubusercontent.com/u/3289?v=4" /></a><p align="center">barwin</p></td>
    <td width="20%"><a href="https://github.com/jcperez"><img src="https://avatars0.githubusercontent.com/u/4073359?v=4" /></a><p align="center">jcperez</p></td>
    <td width="20%"><a href="https://github.com/pensierinmusica"><img src="https://avatars1.githubusercontent.com/u/3594037?v=4" /></a><p align="center">pensierinmusica</p></td>
    <td width="20%"><a href="https://github.com/TeeAaTeeUu"><img src="https://avatars1.githubusercontent.com/u/997511?v=4" /></a><p align="center">TeeAaTeeUu</p></td>
    <td width="20%"><a href="https://github.com/henstock"><img src="https://avatars3.githubusercontent.com/u/13809467?v=4" /></a><p align="center">henstock</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/i5ting"><img src="https://avatars3.githubusercontent.com/u/3118295?v=4" /></a><p align="center">i5ting</p></td>
    <td width="20%"><a href="https://github.com/devoto13"><img src="https://avatars1.githubusercontent.com/u/823594?v=4" /></a><p align="center">devoto13</p></td>
    <td width="20%"><a href="https://github.com/tkalfigo"><img src="https://avatars2.githubusercontent.com/u/3481553?v=4" /></a><p align="center">tkalfigo</p></td>
    <td width="20%"><a href="https://github.com/ArtskydJ"><img src="https://avatars2.githubusercontent.com/u/1833684?v=4" /></a><p align="center">ArtskydJ</p></td>
    <td width="20%"><a href="https://github.com/nswbmw"><img src="https://avatars0.githubusercontent.com/u/4279697?v=4" /></a><p align="center">nswbmw</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/igrcic"><img src="https://avatars1.githubusercontent.com/u/394398?v=4" /></a><p align="center">igrcic</p></td>
    <td width="20%"><a href="https://github.com/VikramTiwari"><img src="https://avatars3.githubusercontent.com/u/1330677?v=4" /></a><p align="center">VikramTiwari</p></td>
    <td width="20%"><a href="https://github.com/mtlima"><img src="https://avatars0.githubusercontent.com/u/9111440?v=4" /></a><p align="center">mtlima</p></td>
    <td width="20%"><a href="https://github.com/pra85"><img src="https://avatars2.githubusercontent.com/u/829526?v=4" /></a><p align="center">pra85</p></td>
    <td width="20%"><a href="https://github.com/joeledwards"><img src="https://avatars3.githubusercontent.com/u/412853?v=4" /></a><p align="center">joeledwards</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/dguo"><img src="https://avatars0.githubusercontent.com/u/2763135?v=4" /></a><p align="center">dguo</p></td>
    <td width="20%"><a href="https://github.com/stipsan"><img src="https://avatars2.githubusercontent.com/u/81981?v=4" /></a><p align="center">stipsan</p></td>
    <td width="20%"><a href="https://github.com/bradvogel"><img src="https://avatars1.githubusercontent.com/u/821706?v=4" /></a><p align="center">bradvogel</p></td>
    <td width="20%"><a href="https://github.com/pyros2097"><img src="https://avatars0.githubusercontent.com/u/1687946?v=4" /></a><p align="center">pyros2097</p></td>
    <td width="20%"><a href="https://github.com/tempname11"><img src="https://avatars0.githubusercontent.com/u/8409150?v=4" /></a><p align="center">tempname11</p></td>
  </tr>
</table>
