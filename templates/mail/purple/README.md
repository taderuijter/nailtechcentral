```
<style type="text/css">
    @font-face {
        font-family: 'PeachCrush';
        src: url('https://files.nailtechcentral.com/Peach_Crush.otf') format('opentype');
    }
    
    @font-face {
        font-family: 'OakesGrotesk';
        src: url('https://files.nailtechcentral.com/OakesGrotesk-Regular.otf') format('opentype');
    }

    .grotest-font {
        font-family: 'OakesGrotesk', sans-serif !important;
        font-size: 20px;
        line-height:30px;
    }
    
    .peach-font {
	    font-family: 'PeachCrush', sans-serif !important;
	    font-size: 46px;
    }
    
    .custom-button {
        font-family: 'PeachCrush', sans-serif !important;
        background-color: #75FB8D;
        color:#000000 !important;
        padding: 15px 20px;
        border-radius:100px;
        margin: 20px 0;
        display:inline-block;
    }
    
    .custom-footer {
        font-family: 'OakesGrotesk', sans-serif !important;
        background-color: #715AF6;
        width:100%;
        text-align: center;
        font-size: 10px;
        padding:0 0 20px 0;
    }
</style>

<div class="mail-wrapper" style="background-color: #715AF6;">
    <div style="width: 100%; text-align: center; margin-bottom:20px;">
        {{logo}}
    </div>
    <div class="mail grotest-font" style="border-radius:20px; text-align: center;">
        <h1 class="peach-font">Hi {{name}}</h1>, 
        <p>Welcome to {{school_name}}, the online school of nail art. From now on you           will have access to your own personal account. This will give you unlimited             access to your purchased courses!</p>
        <p>So what are you waiting for? Learn wherever and whenever!</p>
        <a class="custom-button" href="#">View courses</a>
    </div>
</div>

<div class="custom-footer">
 Copyright © {{school_name}}, All rights reserved. {{address}}
</div>
```