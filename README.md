# quick-paste-pages
a collection of data:text/html pages to just paste into the address bar

[Useful Html tags](https://github.com/JamesFoltz/quick-paste-pages/blob/main/html_tags.md)

# 
# [REALLY get a message across]
- Add `?m=<YOUR MESSAGE HERE>` to the end change the message shown
```
data:text/html;charset=UTF-8,%3Cstyle%3E%20body%7Bmargin%3A0%3Bpadding%3A0%3Boverflow%3Ahidden%3Bbackground-color%3A%23000%3Bfont-family%3A'Courier%20New'%2Cmonospace%7D%23container%7Bposition%3Aabsolute%3Bwidth%3A100%25%3Bheight%3A100%25%3Banimation%3AflashBackground%205s%20infinite%2ChueRotate%205s%20linear%20infinite%3Bdisplay%3Aflex%7D%23scrollingText%7Bposition%3Aabsolute%3Bwhite-space%3Anowrap%3Bfont-size%3A24px%3Bbackground%3Alinear-gradient(to%20right%2Cred%2Corange%2C%23ff0%2Cgreen%2C%2300f%2Cindigo%2Cviolet)%3B-webkit-background-clip%3Atext%3B-webkit-text-fill-color%3Atransparent%3Btext-shadow%3A0%200%205px%20rgba(255%2C255%2C255%2C.5)%3Banimation%3AscrollText%2010s%20linear%20infinite%2CglitchText%20.3s%20infinite%2CtextPulse%202s%20infinite%3Bmargin%3Aauto%3Btext-align%3Acenter%3Balign-self%3Acenter%3Bjustify-self%3Acenter%7D%23glitchOverlay%7Bposition%3Aabsolute%3Btop%3A0%3Bleft%3A0%3Bwidth%3A100%25%3Bheight%3A100%25%3Bpointer-events%3Anone%3Bmix-blend-mode%3Aoverlay%3Banimation%3AglitchOverlay%201s%20infinite%7D%23rainbowBorder%7Bposition%3Aabsolute%3Btop%3A0%3Bleft%3A0%3Bright%3A0%3Bbottom%3A0%3Bborder%3A10px%20solid%20transparent%3Bborder-image%3Alinear-gradient(to%20right%2Cred%2Corange%2C%23ff0%2Cgreen%2C%2300f%2Cindigo%2Cviolet)%201%3Banimation%3AborderRotate%202s%20linear%20infinite%7D%40keyframes%20flashBackground%7B0%25%7Bbackground-color%3A%23000%7D25%25%7Bbackground-color%3Ared%7D50%25%7Bbackground-color%3A%2300f%7D75%25%7Bbackground-color%3Agreen%7D100%25%7Bbackground-color%3A%23000%7D%7D%40keyframes%20hueRotate%7B0%25%7Bfilter%3Ahue-rotate(0)%7D100%25%7Bfilter%3Ahue-rotate(360deg)%7D%7D%40keyframes%20scrollText%7B0%25%7Btransform%3AtranslateX(100%25)%20skew(20deg)%7D100%25%7Btransform%3AtranslateX(-100%25)%20skew(-20deg)%7D%7D%40keyframes%20glitchText%7B0%25%7Btransform%3Atranslate(2px%2C2px)%20rotate(1deg)%7D25%25%7Btransform%3Atranslate(-2px%2C-2px)%20rotate(-1deg)%7D50%25%7Btransform%3Atranslate(-2px%2C2px)%20rotate(1deg)%7D75%25%7Btransform%3Atranslate(2px%2C-2px)%20rotate(-1deg)%7D100%25%7Btransform%3Atranslate(2px%2C2px)%20rotate(1deg)%7D%7D%40keyframes%20textPulse%7B0%25%2C100%25%7Bfont-size%3A40px%7D50%25%7Bfont-size%3A50px%7D%7D%40keyframes%20glitchOverlay%7B0%25%7Bbackground-color%3Argba(255%2C0%2C0%2C.1)%7D25%25%7Bbackground-color%3Argba(0%2C255%2C0%2C.1)%7D50%25%7Bbackground-color%3Argba(0%2C0%2C255%2C.1)%7D75%25%7Bbackground-color%3Argba(255%2C255%2C0%2C.1)%7D100%25%7Bbackground-color%3Argba(255%2C0%2C255%2C.1)%7D%7D%40keyframes%20borderRotate%7B0%25%7Btransform%3Arotate(0)%7D100%25%7Btransform%3Arotate(360deg)%7D%7D%3C%2Fstyle%3E%3Cdiv%20id%3Dcontainer%3E%3Cdiv%20id%3DscrollingText%3E%3C%2Fdiv%3E%3Cdiv%20id%3DglitchOverlay%3E%3C%2Fdiv%3E%3Cdiv%20id%3DrainbowBorder%3E%3C%2Fdiv%3E%3C%2Fdiv%3E%3Cscript%3E%20const%20urlParams%20%3D%20new%20URLSearchParams(window.location.search)%3Bconst%20message%20%3D%20urlParams.get('m')%20%7C%7C%20'WARNING%3ASYSTEM%20INFECTED!'%3Bdocument.getElementById('scrollingText').textContent%20%3D%20Array(10).fill(message).join('%20-%20')%3BsetInterval(()%20%3D%3E%7Bconst%20flash%20%3D%20document.createElement('div')%3Bflash.style.position%20%3D%20'absolute'%3Bflash.style.width%20%3D%20'100px'%3Bflash.style.height%20%3D%20'100px'%3Bflash.style.backgroundColor%20%3D%20%60hsl(%24%7BMath.random()%20*%20360%7D%2C100%25%2C50%25)%60%3Bflash.style.left%20%3D%20%60%24%7BMath.random()%20*%20100%7D%25%60%3Bflash.style.top%20%3D%20%60%24%7BMath.random()%20*%20100%7D%25%60%3Bflash.style.opacity%20%3D%20'0.5'%3Bflash.style.borderRadius%20%3D%20'50%25'%3Bflash.style.filter%20%3D%20'blur(10px)'%3Bflash.style.animation%20%3D%20'flashFade%200.5s%20forwards'%3Bdocument.body.appendChild(flash)%3BsetTimeout(()%20%3D%3E%20flash.remove()%2C500)%7D%2C100)%3B%3C%2Fscript%3E%3Cstyle%3E%20%40keyframes%20flashFade%7B0%25%7Btransform%3Ascale(0)%3Bopacity%3A.5%7D50%25%7Btransform%3Ascale(1.5)%3Bopacity%3A.8%7D100%25%7Btransform%3Ascale(0)%3Bopacity%3A0%7D%7D%3C%2Fstyle%3E
```


# 
# [Black screen]
```
data:text/html;charset=UTF-8,<title>%E2%80%8E</title><link href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII=" rel="icon"><body style="background-color:black;cursor:none;" onclick="document.body.requestFullscreen();"></body>
```


#
# [Instant Chatroom using peerjs]
```
data:text/html;charset=UTF-8,<!doctypehtml><html lang=en><meta charset=UTF-8><meta content="width=device-width,initial-scale=1"name=viewport><title>PeerJS P2P Chat</title><script src=https://unpkg.com/peerjs@1.5.4/dist/peerjs.min.js></script><input id=myId placeholder="Enter your ID"> <button onclick=initializePeer()>Initialize</button> <span id=idStatus></span><br><input id=peerId placeholder="Peer ID"> <button onclick=connectToPeer()>Connect</button> <button onclick=leaveChat()>Leave</button><br><input id=message placeholder=Message> <button onclick=sendMessage()>Send</button><br><ul id=chatLog></ul><script>let peer,conn;function initializePeer(){leaveChat();const e=document.getElementById("myId"),n=document.getElementById("idStatus"),t=new Peer(e.value,{debug:2});t.on("open",(function(o){console.log("ID is available:",o),n.textContent="ID is available!",n.style.color="green",e.value=o,peer=t,setupPeerListeners()})),t.on("error",(function(e){"unavailable-id"===e.type?(console.log("ID is taken"),n.textContent="ID is taken. Please choose another.",n.style.color="red",t.destroy()):(console.error("Error:",e),n.textContent="An error occurred. Please try again.",n.style.color="red")}))}function setupPeerListeners(){peer.on("connection",(function(e){conn=e,setupConnection()}))}function connectToPeer(){const e=document.getElementById("peerId").value;conn=peer.connect(e),setupConnection()}function setupConnection(){conn.on("open",(function(){conn.on("data",(function(e){addMessageToChat(e,conn.peer)}))}))}function sendMessage(){const e=document.getElementById("message").value;conn&&conn.open?(conn.send(e),addMessageToChat(e,"You"),document.getElementById("message").value=""):alert("Connection is not open. Please connect to a peer first.")}function leaveChat(){conn&&(conn.close(),conn=null,console.log("You have left the chat."),addMessageToChat("You have left the chat.","System")),peer&&(peer.destroy(),console.log("Peer connection closed."),document.getElementById("idStatus").textContent=""),(peer||conn)&&(document.getElementById("myId").value="",document.getElementById("peerId").value="",document.getElementById("message").value="")}function addMessageToChat(e,n){const t=document.getElementById("chatLog"),o=document.createElement("li");o.textContent=`${n}: ${e}`,t.appendChild(o)}window.onbeforeunload=function(){peer&&!peer.destroyed&&peer.destroy()}</script>
```


#
# [quick-paste-page generator]
```
data:text/html;charset=UTF-8,%3C!DOCTYPE%20html%3E%3Chtml%20lang%3D%22en%22%3E%3Chead%3E%3Cmeta%20charset%3D%22UTF-8%22%3E%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2Cinitial-scale%3D1.0%22%3E%3Ctitle%3EHTML%20to%20URI%20Converter%3C%2Ftitle%3E%3Cstyle%3E%20body%7Bfont-family%3AArial%2Csans-serif%3Bmax-width%3A800px%3Bmargin%3A0%20auto%3Bpadding%3A20px%3Bbackground-color%3A%23f0f0f0%7Dh1%7Bcolor%3A%23333%3Btext-align%3Acenter%7Dtextarea%7Bwidth%3A100%25%3Bheight%3A200px%3Bmargin-bottom%3A10px%3Bpadding%3A10px%3Bborder%3A1px%20solid%20%23ccc%3Bborder-radius%3A4px%3Bresize%3Avertical%7Dbutton%7Bbackground-color%3A%234CAF50%3Bcolor%3Awhite%3Bpadding%3A10px%2015px%3Bborder%3Anone%3Bborder-radius%3A4px%3Bcursor%3Apointer%3Bmargin-right%3A10px%7Dbutton%3Ahover%7Bbackground-color%3A%2345a049%7D%23outputUrl%7Bdisplay%3Ablock%3Bmargin-top%3A10px%3Bword-break%3Abreak-all%7D%3C%2Fstyle%3E%3C%2Fhead%3E%3Cbody%3E%3Ch1%3EHTML%20to%20URI%20Converter%3C%2Fh1%3E%3Cinput%20type%3D%22file%22%20id%3D%22fileInput%22%20accept%3D%22.html%2C.htm%22%3E%3Ctextarea%20id%3D%22input%22%20placeholder%3D%22Or%20paste%20your%20HTML%20here%22%3E%3C%2Ftextarea%3E%3Cbutton%20onclick%3D%22minify()%22%3EMinify%3C%2Fbutton%3E%3Cbutton%20onclick%3D%22copyToClipboard()%22%3ECopy%20to%20Clipboard%3C%2Fbutton%3E%3Ctextarea%20id%3D%22output%22%20readonly%3E%3C%2Ftextarea%3E%3Ca%20href%3D%22%23%22%20id%3D%22outputUrl%22%20style%3D%22display%3Anone%3B%22%3E%3C%2Fa%3E%3Cscript%3E%20function%20minify()%7Blet%20input%20%3D%20document.getElementById(%22input%22).value%3Bif%20(!input)%7Balert(%22Please%20provide%20input%22)%3Breturn%7Dinput%20%3D%20input.replace(%2F%5C%2F%5C*%5B%5Cs%5CS%5D*%3F%5C*%5C%2F%7C(%5B%5E%5C%5C%3A%5D%7C%5E)%5C%2F%5C%2F.*%24%2Fgm%2C%22%241%22)%20.replace(%2F%5C%2F%5C*%5B%5Cs%5CS%5D*%3F%5C*%5C%2F%2Fg%2C%22%22)%20.replace(%2F%5Cs%2B%2Fg%2C%22%20%22)%20.replace(%2F%3E%5Cs%2B%3C%2Fg%2C%22%3E%3C%22)%20.replace(%2F%5E%5Cs%2B%7C%5Cs%2B%24%2Fg%2C%22%20%22)%20.replace(%2F%5Cs*(%5B%7B%7D%3A%3B%2C%5D)%5Cs*%2Fg%2C%22%241%22)%20.replace(%2F%3B%5Cs*%7D%2Fg%2C%22%7D%22)%20.replace(%2F%5Cs%2B%2Fg%2C%22%20%22)%3Binput%20%3D%20%22data%3Atext%2Fhtml%3Bcharset%3DUTF-8%2C%22%20%2B%20encodeURIComponent(input)%3Bdocument.getElementById(%22output%22).value%20%3D%20input%3Bconst%20outputUrl%20%3D%20document.getElementById(%22outputUrl%22)%3BoutputUrl.href%20%3D%20input%3BoutputUrl.textContent%20%3D%20%22Drag%20To%20URL%20Bar%20To%20Open%22%3BoutputUrl.style.display%20%3D%20%22block%22%7Dfunction%20copyToClipboard()%7Bconst%20output%20%3D%20document.getElementById(%22output%22)%3Boutput.select()%3Bdocument.execCommand(%22copy%22)%7Ddocument.getElementById(%22fileInput%22).addEventListener(%22change%22%2Casync%20(event)%20%3D%3E%7Bconst%20file%20%3D%20event.target.files%5B0%5D%3Bif%20(file)%7Bconst%20content%20%3D%20await%20file.text()%3Bdocument.getElementById(%22input%22).value%20%3D%20content%7D%7D)%3B%3C%2Fscript%3E%3C%2Fbody%3E%3C%2Fhtml%3E%20
```


# 
# [PNG ⮕ JPG]
```
data:text/html;charset=UTF-8,%3Chead%3E%3Ctitle%3EPNG%20%E2%AE%95%20JPG%3C/title%3E%3C/head%3E%3Cbody%3E%3Ch1%3EPNG%20%E2%AE%95%20JPG%3C/h1%3E%3Cinput%20type=%22file%22%20id=%22fileInput%22%20accept=%22.png%22%20/%3E%3Cbutton%20onclick=%22convertToJPG()%22%3EConvert%3C/button%3E%3Cbr%3E%3Cdiv%20id=%22output%22%3E%3C/div%3E%3Cscript%3E%20function%20convertToJPG()%7Bconst%20fileInput%20=%20document.getElementById('fileInput');const%20file%20=%20fileInput.files%5B0%5D;const%20output%20=%20document.getElementById('output');if%20(file%20&&%20file.type%20===%20'image/png')%7Bconst%20reader%20=%20new%20FileReader();reader.onload%20=%20function(e)%7Bconst%20img%20=%20new%20Image();img.onload%20=%20function()%7Bconst%20canvas%20=%20document.createElement('canvas');canvas.width%20=%20img.width;canvas.height%20=%20img.height;const%20ctx%20=%20canvas.getContext('2d');ctx.drawImage(img,0,0);const%20jpgDataUrl%20=%20canvas.toDataURL('image/jpeg');const%20link%20=%20document.createElement('a');link.href%20=%20jpgDataUrl;link.download%20=%20file.name.replace('.png','.jpg');link.textContent%20=%20'Download%20JPG';output.innerHTML%20=%20'';output.appendChild(link)%7D;img.src%20=%20e.target.result%7D;reader.readAsDataURL(file)%7Delse%7Boutput.textContent%20=%20'Please%20select%20a%20valid%20PNG%20file.'%7D%7D%3C/script%3E%3C/body%3E
```


# 
# [Decompress And Render Quick-Paste-Page]
```
data:text/html;charset=UTF-8,%20%3Ctitle%3EData%20URI%20Code%20Extractor%20and%20Renderer%3C%2Ftitle%3E%3Cstyle%3E%20body%7Bfont-family%3AArial%2Csans-serif%3Bmax-width%3A800px%3Bmargin%3A0%20auto%3Bpadding%3A20px%7Dtextarea%7Bwidth%3A100%25%3Bheight%3A150px%3Bmargin-bottom%3A10px%7Dbutton%7Bpadding%3A10px%3Bbackground-color%3A%234CAF50%3Bcolor%3Awhite%3Bborder%3Anone%3Bcursor%3Apointer%3Bmargin-right%3A10px%7Dbutton%3Ahover%7Bbackground-color%3A%2345a049%7D%23output%2C%23renderFrame%7Bwidth%3A100%25%3Bheight%3A300px%3Bborder%3A1px%20solid%20%23ccc%3Bmargin-top%3A10px%7D%3C%2Fstyle%3E%3C%2Fhead%3E%3Cbody%3E%3Ch1%3EData%20URI%20Code%20Extractor%20and%20Renderer%3C%2Fh1%3E%3Ctextarea%20id%3D%22input%22%20placeholder%3D%22Paste%20your%20data%20URI%20here...%22%3E%3C%2Ftextarea%3E%3Cbutton%20onclick%3D%22extractFormatAndRender()%22%3EExtract%2CFormat%2Cand%20Render%3C%2Fbutton%3E%3Cbutton%20onclick%3D%22copyToClipboard()%22%3ECopy%20Formatted%20Code%3C%2Fbutton%3E%3Ch2%3EFormatted%20Code%3A%3C%2Fh2%3E%3Ctextarea%20id%3D%22output%22%20readonly%3E%3C%2Ftextarea%3E%3Ch2%3ERendered%20Output%3A%3C%2Fh2%3E%3Ciframe%20id%3D%22renderFrame%22%3E%3C%2Fiframe%3E%3Cscript%20src%3D%22https%3A%2F%2Fcdnjs.cloudflare.com%2Fajax%2Flibs%2Fjs-beautify%2F1.14.0%2Fbeautify-html.min.js%22%3E%3C%2Fscript%3E%3Cscript%3E%20function%20extractFormatAndRender()%7Bconst%20input%20%3D%20document.getElementById('input').value%3Bconst%20output%20%3D%20document.getElementById('output')%3Bconst%20renderFrame%20%3D%20document.getElementById('renderFrame')%3Blet%20extractedCode%20%3D%20''%3Btry%7Bconst%20htmlPart%20%3D%20input.split('%2C')%5B1%5D%3Bconst%20decodedHtml%20%3D%20decodeURIComponent(htmlPart)%3BextractedCode%20%3D%20html_beautify(decodedHtml%2C%7Bindent_size%3A2%7D)%3Boutput.value%20%3D%20extractedCode%3BrenderFrame.srcdoc%20%3D%20decodedHtml%7Dcatch%20(error)%7Boutput.value%20%3D%20'Error%3AUnable%20to%20extract%20and%20format%20the%20code.%20Please%20make%20sure%20you%20entered%20a%20valid%20data%20URI.'%3BrenderFrame.srcdoc%20%3D%20'%3Cp%3EError%3AUnable%20to%20render%20the%20content.%3C%2Fp%3E'%7D%7Dfunction%20copyToClipboard()%7Bconst%20output%20%3D%20document.getElementById('output')%3Boutput.select()%3Bdocument.execCommand('copy')%3Balert('Formatted%20code%20copied%20to%20clipboard!')%7D%3C%2Fscript%3E%3C%2Fbody%3E
```


#
# [Random Number]
- Default max is 2, set `?max=<MAX RANDOM NUMBER>` to choose a different max number.
```
data:text/html;charset=UTF-8,%3Cbody%3E%3Cp%20id%3D%22out%22%3ENone%3C%2Fp%3E%3Cinput%20type%3D%22number%22%20name%3D%22max%22%20id%3D%22max-input%22%20style%3D%22width%3Afit-content%3B%22%3E%3Cbutton%20id%3D%22button%22%20onclick%3D%22generateNumber()%22%3ENew%20Number%3C%2Fbutton%3E%3C%2Fbody%3E%3Cscript%3E%20const%20queryString%20%3D%20window.location.search%3Bconst%20urlParams%20%3D%20new%20URLSearchParams(queryString)%3Bconst%20maxInput%20%3D%20document.getElementById(%22max-input%22)%3Blet%20max%20%3D%202%3BmaxInput.value%20%3D%20urlParams.get(%22max%22)%20%7C%7C%20max%3Bmax%20%3D%20Math.max(maxInput.value%2C2)%3BgenerateNumber()%3Bif%20(urlParams.get(%22close%22)%20%3D%3D%20%22close%22)%7Bwindow.close()%7Dfunction%20generateNumber()%7Bmax%20%3D%20Math.max(maxInput.value%2C2)%3BurlParams.set(%22max%22%2Cmax)%3Bvar%20rand%20%3D%20Math.round(Math.random()%20*%20Math.max(max%2C2))%3Bdocument.getElementById(%22out%22).innerText%20%3D%20rand%3BsetClipboard(rand)%7Dasync%20function%20setClipboard(text)%7Bconst%20type%20%3D%20%22text%2Fplain%22%3Bconst%20blob%20%3D%20new%20Blob(%5Btext%5D%2C%7Btype%7D)%3Bconst%20data%20%3D%20%5Bnew%20ClipboardItem(%7B%5Btype%5D%3Ablob%7D)%5D%3Bawait%20navigator.clipboard.write(data)%7D%3C%2Fscript%3E%3C%2Fhtml%3E%20
```
