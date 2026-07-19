---
title: "When does the season end?"
summary: "Season 2 of 2026 ends at 11:59pm on July 28, your server's local time. Servers use different timezones. Click for info."
order: 2
---
Season 2 of 2026 ends at 11:59pm on July 28, your server's local time. Servers use different timezones.

<table>
  <thead><tr><th>Region</th><th>Start Time</th></tr></thead>
  <tbody>
    <tr><td>OC1</td>  <td class="ts" data-ts="1785247140"></td></tr>
    <tr><td>JP1</td>  <td class="ts" data-ts="1785250740"></td></tr>
    <tr><td>KR1</td>  <td class="ts" data-ts="1785250740"></td></tr>
    <tr><td>PH</td>   <td class="ts" data-ts="1785254340"></td></tr>
    <tr><td>SG</td>   <td class="ts" data-ts="1785254340"></td></tr>
    <tr><td>TW</td>   <td class="ts" data-ts="1785254340"></td></tr>
    <tr><td>VN</td>   <td class="ts" data-ts="1785257940"></td></tr>
    <tr><td>TH</td>   <td class="ts" data-ts="1785257940"></td></tr>
    <tr><td>RU</td>   <td class="ts" data-ts="1785272340"></td></tr>
    <tr><td>TR1</td>  <td class="ts" data-ts="1785272340"></td></tr>
    <tr><td>EUN1</td> <td class="ts" data-ts="1785275940"></td></tr>
    <tr><td>EUW1</td> <td class="ts" data-ts="1785279540"></td></tr>
    <tr><td>BR1</td>  <td class="ts" data-ts="1785293940"></td></tr>
    <tr><td>LA2</td>  <td class="ts" data-ts="1785293940"></td></tr>
    <tr><td>LA1</td>  <td class="ts" data-ts="1785301140"></td></tr>
    <tr><td>NA1</td>  <td class="ts" data-ts="1785308340"></td></tr>
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