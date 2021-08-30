<!doctype html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
  <title>Online Tuner</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div style="text-align: center;">&nbsp;
  <div class="separator" style="clear: both; text-align: center;">
    <a href="https://topcifrasepartituras.blogspot.com/2021/08/aprenda-tocar-usando-o-celular.html#more" style="margin-left: 1em; margin-right: 1em;">
      <img border="0" data-original-height="180" data-original-width="180" height="180" src="https://1.bp.blogspot.com/-LOmRI74pDvY/YSzqu6WaxqI/AAAAAAAATbQ/yBF8ABgALWsj_7-gKInL4mzV_bupJazzACLcBGAsYHQ/s180/avatar-180x180%2Bcom%2Bselo%2B%25281%2529.png" width="180"/>
    </a>
  </div>
<canvas class="frequency-bars"></canvas>
<div class="meter">
  <div class="meter-dot"></div>
  <div class="meter-pointer"></div>
</div>
<div class="notes">
  <div class="notes-list"></div>
  <div class="frequency"> <span>Hz</span></div>
</div>
<div class="a4">A<sub>4</sub> = <span>440</span> Hz</div>
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@9"></script>
<script src="aubio.js"></script>
<script src="tuner.js"></script>
<script src="meter.js"></script>
<script src="frequency-bars.js"></script>
<script src="notes.js"></script>
<script src="app.js"></script>
</body>
</html>
