# MyNewSite
thise is fast ewb
<html lang="">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Javascript Clock | CSS Neumorphism Working Analog Clock UI Design</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

  body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #212121;
}
  
.clock {
    display: flex;
    width: 350px;
    height: 350px;
    justify-content: center;
    align-items: center;
    background: url(http://samuel-garcia.site/img/clock-sam.png);
    background-size: cover;
    border: 4px solid #191919;
    border-radius: 50%;
    box-shadow: -4px -4px 10px rgba(67, 67, 67, 0.5),
        inset 4px 4px 10px rgba(0, 0, 0, 0.5),
        inset -4px -4px 10px rgba(67, 67, 67, 0.3),
        4px 4px 10px rgba(0, 0, 0, 0.3);
}


.clock:before {
    content: "";
    position: absolute;
    width: 15px;
    height: 15px;
    background: #747474;
    border-radius: 50%;
    z-index: 999;

    
