# AI_MAD_NumGame
<h1 align=center> Information about the Project </h1>
<ul>
<li>This Project is a partially built project on Simple Arithmetic Game for <i>single player</i>.</li>

<li>Most of the coding part is already done, however, some clues are left in between (comments //) where students can write their codes.</li>

<li><b>matchCounter</b> will keep track of how many matches are played. A match is akin to answer one question.</li>

<li>If a player correctly answers a match, a one is added in the score array; otherwise, a zero will be added.</li>

<li>When matchCounter reaches a value 3, the sum of last three matches will be added to the <b>performance</b> array, which is initially set with -1 at all places.
For example, the performance array at the start of your app will be like [-1, -1, -1, -1, -1, -1], but after the completion of three matches let the
score array be like [1, 0, 1] then the performance array would be like [-1, -1, -1, -1, -1, 2]. Each time the performance array will be updated, the new value will
be added at the last element of the array, and all previous values will be shifted one place left. The first value will be lost, as we have to analyze the performance
  of the last six gammes only. </li>
  
