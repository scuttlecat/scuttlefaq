---
title: "When does the season end?"
summary: "Season 3 of 2026 ends at 11:59pm on January 6th, 2027, your server's local time. Servers use different timezones. Click for info. This timer is _LITERALLY_ always available in the client. Click your profile icon in the top right, then click ranked. You will see a countdown for your server's season end. Wow!"
category: "Seasons & Ranked"
order: 3
---
Season 3 of 2026 ends at 11:59pm on January 6th, 2027, your server's local time. Servers use different timezones. This timer is <strong>LITERALLY</strong> always available in the client. Click your profile icon in the top right, then click ranked. You will see a countdown for your server's season end. Wow!

<table>
  <thead><tr><th>Region</th><th>End Time</th></tr></thead>
  <tbody>
    <tr><td>OCE</td>  <td class="ts" data-ts="1799240399"></td></tr>
    <tr><td>JP</td>   <td class="ts" data-ts="1799247599"></td></tr>
    <tr><td>KR</td>   <td class="ts" data-ts="1799247599"></td></tr>
    <tr><td>SEA</td>  <td class="ts" data-ts="1799251199"></td></tr>
    <tr><td>TW</td>   <td class="ts" data-ts="1799251199"></td></tr>
    <tr><td>VN</td>   <td class="ts" data-ts="1799254799"></td></tr>
    <tr><td>RU</td>   <td class="ts" data-ts="1799269199"></td></tr>
    <tr><td>TR</td>   <td class="ts" data-ts="1799269199"></td></tr>
    <tr><td>EUNE</td> <td class="ts" data-ts="1799276399"></td></tr>
    <tr><td>EUW</td>  <td class="ts" data-ts="1799279999"></td></tr>
    <tr><td>BR</td>   <td class="ts" data-ts="1799290799"></td></tr>
    <tr><td>LAS</td>  <td class="ts" data-ts="1799290799"></td></tr>
    <tr><td>LAN</td>  <td class="ts" data-ts="1799297999"></td></tr>
    <tr><td>NA</td>   <td class="ts" data-ts="1799308799"></td></tr>
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