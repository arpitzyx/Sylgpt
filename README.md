# Sylgpt
A open source free working ai for template and designs highly customizable, try now 
<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    * { box-sizing: border-box; }
    html, body { height: 100%; margin: 0; }
    body { font-family: Arial, sans-serif; background: #f3f4f6; color: #333; }
    .container { max-width: 1100px; margin: 0 auto; padding: 0 12px 40px; }
    .hero { height: 100vh; width: 100%; background: #ddd; display: flex; align-items: stretch; justify-content: center; border-bottom: 1px solid #e5e5e5; }
    .hero img { width: 100%; height: 100%; object-fit: cover; display: block; }
    #slots { display: grid; grid-template-columns: 1fr; gap: 12px; padding: 12px 0; }
    .slot {
      height: 230px;
      border: 2px dashed #bbb;
      border-radius: 8px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      position: relative;
    }
    .slotImg { max-width: 100%; max-height: 100%; display: none; }
    .hint { color: #888; font-size: 14px; }
    .slotInput { display: none; }
    /* Simple helper to keep things tidy on small screens */
    @media (max-width: 600px) {
      .slot { height: 180px; }
    }

  </style>
</head>
<body>
  <div class="container">
     <div id="hero" class="hero">
      <img id="heroImg" alt="Full screen screenshot" src="assets/Screenshot 2026-04-19 193407.png" >
    </div> <br>
    <div id="slots" style="display:none;">
      <div class="slot" data-index="0" title="Upload image for slot 1">
        <img class="slotImg" src="assets/Screenshot 2026-04-19 203631.png" alt="screenshot 1" />        
      </div>
      <div class="slot" data-index="1" title="Upload image for slot 2">
        <img class="slotImg" src="assets/Screenshot 2026-04-19 203645.png" alt="screenshot 2" />         
      </div>
      <div class="slot" data-index="2" title="Upload image for slot 3">
        <img class="slotImg" src="assets//Screenshot 2026-04-19 203727.png" alt="screenshot 3" />
            </div>
    </div>
        <div id="hero" class="hero">
      <img id="heroImg" alt="Full screen screenshot" src="assets/Screenshot 2026-04-19 203751.png" >
    </div> <br>
        <div id="hero" class="hero">
      <img id="heroImg" alt="Full screen screenshot" src="assets/Screenshot 2026-04-19 203852.png" >
    </div> <br>
        <div id="hero" class="hero">
      <img id="heroImg" alt="Full screen screenshot" src="assets/Screenshot 2026-04-19 203903.png" >
    </div> <br>
            <div id="hero" class="hero">
      <img id="heroImg" alt="Full screen screenshot" src="assets/Screenshot 2026-04-19 204227.png" >
    </div> <br>


  </div>
</body>
</html>
