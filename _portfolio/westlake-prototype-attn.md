---
title: "Object Replacement with Large Differences in Video Editing"
excerpt: |
  <table style="width:100%; table-layout:fixed; border-spacing:12px;">
    <tr style="text-align:center;">
      <th>Original Input</th>
      <th>Vanilla Flow Director</th>
      <th>Fixed Late Noise</th>
    </tr>
    <tr style="text-align:center; vertical-align:top;">
      <td><img src="/images/wolf_ori.gif" alt="Original input" style="width:80%; max-width:420px; height:auto;"></td>
      <td><img src="/images/wolf_bad.gif" alt="Vanilla Flow Director" style="width:80%; max-width:420px; height:auto;"></td>
      <td><img src="/images/wolf.gif" alt="Fixed Late Noise" style="width:80%; max-width:420px; height:auto;"></td>
    </tr>
  </table>
collection: portfolio
---

- Context: Westlake University AIGC Summer Research (Supervisor: Prof. Chi Zhang)
- Goal: Replace a source object with a target object with large differences (in size/type...)while maintaining spatial–temporal consistency and scene realism.
- Method: Late-step editing schedule with smoothed guidance to prevent background leakage and flicker.

- Outcomes: Stable shape/identity across frames and cleaner transitions in long sequences.
- Links: [GitHub](https://github.com/CeciliaTheBirb/LargeEditVid)
