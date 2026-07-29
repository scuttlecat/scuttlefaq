---
title: "When does the season start?"
summary: "ACCORDING TO RIOT IN PATCH NOTES 26.15, Season 3 of 2026 starts at 12pm (noon) on July 29, your server's local time. Servers use different timezones. Click for timezone info. THIS IS WHEN RANKED QUEUE IS BACK. Riot is bad at dates and times and coding, so expect it to be late."
category: "Seasons & Ranked"
order: 2
---
ACCORDING TO RIOT IN PATCH NOTES 26.15, Season 3 of 2026 starts at 12pm (noon) on July 29, your server's local time. Servers use different timezones. THIS IS WHEN RANKED QUEUE IS BACK. Riot is bad at dates and times and coding, so expect it to be late.

<table>
  <thead><tr><th>Region</th><th>Start Time</th></tr></thead>
  <tbody>
    <tr><td>OCE</td>  <td class="ts" data-ts="1785290400"></td></tr>
    <tr><td>JP</td>  <td class="ts" data-ts="1785294000"></td></tr>
    <tr><td>KR</td>  <td class="ts" data-ts="1785294000"></td></tr>
    <tr><td>SEA</td>  <td class="ts" data-ts="1785297600"></td></tr>
    <tr><td>TW</td>  <td class="ts" data-ts="1785297600"></td></tr>
    <tr><td>VN</td>  <td class="ts" data-ts="1785301200"></td></tr>
    <tr><td>RU</td>   <td class="ts" data-ts="1785315600"></td></tr>
    <tr><td>TR</td>  <td class="ts" data-ts="1785315600"></td></tr>
    <tr><td>EUNE</td> <td class="ts" data-ts="1785319200"></td></tr>
    <tr><td>EUW</td> <td class="ts" data-ts="1785322800"></td></tr>
    <tr><td>BR</td>  <td class="ts" data-ts="1785337200"></td></tr>
    <tr><td>LAS</td>  <td class="ts" data-ts="1785337200"></td></tr>
    <tr><td>LAN</td>  <td class="ts" data-ts="1785344400"></td></tr>
    <tr><td>NA</td>  <td class="ts" data-ts="1785351600"></td></tr>
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
