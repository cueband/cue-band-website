---
title: Download
layout: page
permalink: /app/
intro_image_absolute: true
intro_image_hide_on_mobile: false
---

<p style="text-align: center"> 
   The Cue Band app is available to download on your mobile device.
</p>



<!--a href="{{ link }}" style="background-color: #E5261F; width: 100%; color: white; border: solid; height: 50px; border-radius: 10px; font-size: 15px; line-height: 50px; text-decoration: none;  display: inline-block; cursor: pointer"> Download App </a-->
            
<div id="noPhoneContainer" style="text-align: center; display: block;">
    <p style="text-align: center">
        On your mobile device web browser please go to the site:
    </p>
    <p style="text-align: center">
        https://<strong>cue.band/app</strong>
    </p>
    <p style="text-align: center">
        Alternatively use the links below to download the app:
    </p>
    <ul style="list-style: none">
        <li style="padding-bottom: 25px"><a href="{{ "appandroid" | relative_url }}" onclick="fathom.trackGoal('2KINLWDL', 1);">Android, Google Play Store</a></li>
        <li><a href="{{ "appios" | relative_url }}" onclick="fathom.trackGoal('JIDYSHSY', 1);">iPhone, App Store</a></li>
    </ul>
</div>

<div id="androidContainer" style="text-align: center; display: none;">
    <p>Tap the following link to be taken to the Play Store and install the app:</p>
    <p style="text-align: center; padding-bottom: 25px">
        <a href="{{ "appandroid" | relative_url }}" onclick="fathom.trackGoal('2KINLWDL', 1);">Android, Google Play Store</a>
    </p>
    <p style="text-align: center">
        If you are installing the app on another device, on that device's web browser go to the site:
    </p>
    <p style="text-align: center; padding-bottom: 25px">
        https://<strong>cue.band/app</strong>
    </p>
    <p style="text-align: center;">
        The app is also available on iPhone:
    </p>
    <p>
        <a href="{{ "appios" | relative_url }}" onclick="fathom.trackGoal('JIDYSHSY', 1);">iPhone, App Store</a>
    </p>
</div>


<div id="iosContainer" style="text-align: center; display: none;">
    <p>Tap the following link to be taken to the App Store and install the app:</p>
    <p style="text-align: center; padding-bottom: 25px">
        <a href="{{ "appios" | relative_url }}" onclick="fathom.trackGoal('JIDYSHSY', 1);">iPhone, App Store</a>
    </p>
    <p style="text-align: center">
        If you are installing the app on another device, on that device's web browser go to the site:
    </p>
    <p style="text-align: center; padding-bottom: 25px">
        https://<strong>cue.band/app</strong>
    </p>
    <p style="text-align: center;">
        The app is also available on Android:
    </p>
    <p>
        <a href="{{ "appandroid" | relative_url }}" onclick="fathom.trackGoal('2KINLWDL', 1);">Android, Google Play Store</a>
    </p>
</div>
<p style="text-align: left">
    During your study onboarding in the app, you will be prompted to input a study token.
</p>
<div id="tokenContainer" style="text-align: left; display: none;">
    <p> This token will allow us to get the choices you selected during the pre-registeration on the website.</p>
    <p style="text-align: center">
        Your study token    
    </p>
    <p style="font-size: 30px; text-align: center;"> 
        <strong id="tokenText"></strong>
    </p>
    
</div>
<div id="noTokenContainer" style="text-align: center; display: block;">
    <p style="text-align: left">
        If you pre-registered your token will be in your e-mail, if not press "I don't have a token" on the app. 
    </p>
</div>

<p>
    If you are having difficulties installing the <strong>Cue Band</strong> app on your smartphone device, please refer to our online support website at <a href="https://faq.cue.band">https://faq.cue.band</a>
</p>

<script>
    const urlSearchParams = new URLSearchParams(window.location.search);
    const params = Object.fromEntries(urlSearchParams.entries());
    
    var token = params['t'];

    var noTokenContainer = document.getElementById("noTokenContainer");

    if(token != null) {
        var tokenContainer = document.getElementById("tokenContainer");
        tokenContainer.style.display = "block";

        var tokenText = document.getElementById("tokenText");
        tokenText.innerText = token;
        noTokenContainer.style.display = "none";
    } 

    var platform = getMobileOperatingSystem();
    var noPhoneContainer = document.getElementById("noPhoneContainer");

    if(platform == "Android") {
        var androidContainer = document.getElementById("androidContainer");
        androidContainer.style.display = "block"
        noPhoneContainer.style.display = "none"
    } else if(platform == "iOS") {
        var iosContainer = document.getElementById("iosContainer");
        iosContainer.style.display = "block"
        noPhoneContainer.style.display = "none"
    }


/**
 * Determine the mobile operating system.
 * This function returns one of 'iOS', 'Android', 'Windows Phone', or 'unknown'.
 *
 * @returns {String}
 */
function getMobileOperatingSystem() {
    var userAgent = navigator.userAgent || navigator.vendor || window.opera;

    // Windows Phone must come first because its UA also contains "Android"
    if (/windows phone/i.test(userAgent)) {
        return "unknown";
    }

    if (/android/i.test(userAgent)) {
        return "Android";
    }

    // iOS detection from: http://stackoverflow.com/a/9039885/177710
    if (/iPhone|iPod/.test(userAgent) && !window.MSStream) {
        return "iOS";
    }

    return "unknown";
}


</script>
    