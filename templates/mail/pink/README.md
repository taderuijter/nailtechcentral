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
        font-size: 20px !important;
        line-height:30px !important;
    }
    
    .peach-font {
	    font-family: 'PeachCrush', sans-serif !important;
	    font-size: 46px;
    }
    
    .custom-button {
        font-family: 'PeachCrush', sans-serif !important;
        background-color: #00FF7F !important;
        color:#000000 !important;
        padding: 15px 20px;
        border-radius:100px;
        margin: 20px 0 0 0;
        display:inline-block;
    }
    
    .custom-footer {
        font-family: 'OakesGrotesk', sans-serif !important;
    }
    
    .content {
        background-color: #ffffff;
        color: #000000;
    }
    
    @media (prefers-color-scheme: dark) {
        .content {
            background-color: #ffffff;
            color: #000000;
        }
        
        .custom-button {
            font-family: 'PeachCrush', sans-serif !important;
            background-color: #00FF7F !important;
            color:#000000 !important;
            padding: 15px 20px;
            border-radius:100px;
            margin: 20px 0 0 0;
            display:inline-block;
        }
    }
</style>

<div class="mail-wrapper" style="background-color: #E595B9;">
    <div style="width: 100%; text-align: center; margin-bottom:20px;">
        <img width="185px" src="https://lwfiles.mycourse.app/6485e0440c0c35ee7db7d97c-public/53dbd778d7e6f751740a8d461022b554.png">
    </div>
    <div class="content grotest-font" style="background-color: #ffffff; border-radius:20px; text-align: center; padding:5%; width:80%; margin:0 auto;">
        <h1 class="peach-font">Hi {{name}},</h1> 
        <br>
        <p>Welcome to {{school_name}}, the online school of nail art. <br>From now on you           will have access to your own personal account. This will give you unlimited             access to all your purchased courses!</p>
        <p>So what are you waiting for? Learn wherever and whenever!</p>
        <a class="custom-button" href="https://www.nailtechcentral.com/courses">View courses</a>
    </div>
    <div class="custom-footer" style="margin:20px 0; text-align: center; font-size: 10px;">
     Copyright © {{school_name}}, All rights reserved. {{address}}
    </div>
</div>


```