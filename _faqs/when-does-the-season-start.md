---
title: "When does the season start?"
summary: "Since 2025, seasons (this means RANKED QUEUE) begins 12 noon your local server time. Click for timezone info.
category: "Seasons & Ranked"
order: 2
---
Since 2025, seasons (this means RANKED QUEUE) begins 12 noon your local server time. See the times below. This is just when it IS SCHEDULED, anmd Riot regularly fucks this up so don't @ me.

<table>
  <thead><tr><th>Region</th><th>Start Time</th></tr></thead>
  <tbody>
    <tr><td>OCE</td>  <td class="ts" data-ts="1799283600"></td></tr>
    <tr><td>JP</td>   <td class="ts" data-ts="1799290800"></td></tr>
    <tr><td>KR</td>   <td class="ts" data-ts="1799290800"></td></tr>
    <tr><td>SEA</td>  <td class="ts" data-ts="1799294400"></td></tr>
    <tr><td>TW</td>   <td class="ts" data-ts="1799294400"></td></tr>
    <tr><td>VN</td>   <td class="ts" data-ts="1799298000"></td></tr>
    <tr><td>RU</td>   <td class="ts" data-ts="1799312400"></td></tr>
    <tr><td>TR</td>   <td class="ts" data-ts="1799312400"></td></tr>
    <tr><td>EUNE</td> <td class="ts" data-ts="1799319600"></td></tr>
    <tr><td>EUW</td>  <td class="ts" data-ts="1799323200"></td></tr>
    <tr><td>BR</td>   <td class="ts" data-ts="1799334000"></td></tr>
    <tr><td>LAS</td>  <td class="ts" data-ts="1799334000"></td></tr>
    <tr><td>LAN</td>  <td class="ts" data-ts="1799341200"></td></tr>
    <tr><td>NA</td>   <td class="ts" data-ts="1799352000"></td></tr>
  </tbody>
</table>

<script>
  document.querySelectorAll('.ts').forEach(el => {
    const d = new Date(el.dataset.ts * 1000);
    el.textContent = d.toLocaleString(undefined, {
      weekday: 'short', month: 'short', day: 'numeric',
      hour: 'numeric', minute: '2-digit', timeZoneName: 'short'
    });
  });
</script>
