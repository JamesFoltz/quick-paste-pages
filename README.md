# quick-paste-pages
a collection of data:text/html pages to just paste into the address bar


# 
# [REALLY get a message across]
- Add `?m=<YOUR MESSAGE HERE>` to the end change the message shown
```
data:text/html;charset=UTF-8,%3C%21doctypehtml%3E%3Chtml%20lang%3Den%3E%3Cmeta%20charset%3DUTF-8%3E%3Cmeta%20content%3D%22width%3Ddevice-width%2Cinitial-scale%3D1%22name%3Dviewport%3E%3Ctitle%3ESuper%20Obnoxious%20Flashing%20Page%3C%2Ftitle%3E%3Cstyle%3Ebody%7Bmargin%3A0%3Bpadding%3A0%3Boverflow%3Ahidden%3Bbackground-color%3A%23000%3Bfont-family%3A%27Courier%20New%27%2Cmonospace%7D%23container%7Bposition%3Aabsolute%3Bwidth%3A100%25%3Bheight%3A100%25%3Banimation%3AflashBackground%205s%20infinite%2ChueRotate%205s%20linear%20infinite%3Bdisplay%3Aflex%7D%23scrollingText%7Bposition%3Aabsolute%3Bwhite-space%3Anowrap%3Bfont-size%3A24px%3Bbackground%3Alinear-gradient%28to%20right%2Cred%2Corange%2C%23ff0%2Cgreen%2C%2300f%2Cindigo%2Cviolet%29%3B-webkit-background-clip%3Atext%3B-webkit-text-fill-color%3Atransparent%3Btext-shadow%3A0%200%205px%20rgba%28255%2C255%2C255%2C.5%29%3Banimation%3AscrollText%2010s%20linear%20infinite%2CglitchText%20.3s%20infinite%2CtextPulse%202s%20infinite%3Bmargin%3Aauto%3Btext-align%3Acenter%3Balign-self%3Acenter%3Bjustify-self%3Acenter%7D%23glitchOverlay%7Bposition%3Aabsolute%3Btop%3A0%3Bleft%3A0%3Bwidth%3A100%25%3Bheight%3A100%25%3Bpointer-events%3Anone%3Bmix-blend-mode%3Aoverlay%3Banimation%3AglitchOverlay%201s%20infinite%7D%23rainbowBorder%7Bposition%3Aabsolute%3Btop%3A0%3Bleft%3A0%3Bright%3A0%3Bbottom%3A0%3Bborder%3A10px%20solid%20transparent%3Bborder-image%3Alinear-gradient%28to%20right%2Cred%2Corange%2C%23ff0%2Cgreen%2C%2300f%2Cindigo%2Cviolet%29%201%3Banimation%3AborderRotate%202s%20linear%20infinite%7D%40keyframes%20flashBackground%7B0%25%7Bbackground-color%3A%23000%7D25%25%7Bbackground-color%3Ared%7D50%25%7Bbackground-color%3A%2300f%7D75%25%7Bbackground-color%3Agreen%7D100%25%7Bbackground-color%3A%23000%7D%7D%40keyframes%20hueRotate%7B0%25%7Bfilter%3Ahue-rotate%280%29%7D100%25%7Bfilter%3Ahue-rotate%28360deg%29%7D%7D%40keyframes%20scrollText%7B0%25%7Btransform%3AtranslateX%28100%25%29%20skew%2820deg%29%7D100%25%7Btransform%3AtranslateX%28-100%25%29%20skew%28-20deg%29%7D%7D%40keyframes%20glitchText%7B0%25%7Btransform%3Atranslate%282px%2C2px%29%20rotate%281deg%29%7D25%25%7Btransform%3Atranslate%28-2px%2C-2px%29%20rotate%28-1deg%29%7D50%25%7Btransform%3Atranslate%28-2px%2C2px%29%20rotate%281deg%29%7D75%25%7Btransform%3Atranslate%282px%2C-2px%29%20rotate%28-1deg%29%7D100%25%7Btransform%3Atranslate%282px%2C2px%29%20rotate%281deg%29%7D%7D%40keyframes%20textPulse%7B0%25%2C100%25%7Bfont-size%3A40px%7D50%25%7Bfont-size%3A50px%7D%7D%40keyframes%20glitchOverlay%7B0%25%7Bbackground-color%3Argba%28255%2C0%2C0%2C.1%29%7D25%25%7Bbackground-color%3Argba%280%2C255%2C0%2C.1%29%7D50%25%7Bbackground-color%3Argba%280%2C0%2C255%2C.1%29%7D75%25%7Bbackground-color%3Argba%28255%2C255%2C0%2C.1%29%7D100%25%7Bbackground-color%3Argba%28255%2C0%2C255%2C.1%29%7D%7D%40keyframes%20borderRotate%7B0%25%7Btransform%3Arotate%280%29%7D100%25%7Btransform%3Arotate%28360deg%29%7D%7D%3C%2Fstyle%3E%3Cdiv%20id%3Dcontainer%3E%3Cdiv%20id%3DscrollingText%3E%3C%2Fdiv%3E%3Cdiv%20id%3DglitchOverlay%3E%3C%2Fdiv%3E%3Cdiv%20id%3DrainbowBorder%3E%3C%2Fdiv%3E%3C%2Fdiv%3E%3Cscript%3Econst%20urlParams%20%3D%20new%20URLSearchParams%28window.location.search%29%3B%0A%20%20%20%20%20%20%20%20const%20message%20%3D%20urlParams.get%28%27m%27%29%20%7C%7C%20%27WARNING%3A%20SYSTEM%20INFECTED%21%27%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%27scrollingText%27%29.textContent%20%3D%20Array%2810%29.fill%28message%29.join%28%27%20-%20%27%29%3B%0A%0A%20%20%20%20%20%20%20%20%2F%2F%20Add%20random%20flashing%20elements%0A%20%20%20%20%20%20%20%20setInterval%28%28%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20const%20flash%20%3D%20document.createElement%28%27div%27%29%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.position%20%3D%20%27absolute%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.width%20%3D%20%27100px%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.height%20%3D%20%27100px%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.backgroundColor%20%3D%20%60hsl%28%24%7BMath.random%28%29%20%2A%20360%7D%2C%20100%25%2C%2050%25%29%60%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.left%20%3D%20%60%24%7BMath.random%28%29%20%2A%20100%7D%25%60%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.top%20%3D%20%60%24%7BMath.random%28%29%20%2A%20100%7D%25%60%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.opacity%20%3D%20%270.5%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.borderRadius%20%3D%20%2750%25%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.filter%20%3D%20%27blur%2810px%29%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20flash.style.animation%20%3D%20%27flashFade%200.5s%20forwards%27%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20document.body.appendChild%28flash%29%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20setTimeout%28%28%29%20%3D%3E%20flash.remove%28%29%2C%20500%29%3B%0A%20%20%20%20%20%20%20%20%7D%2C%20100%29%3B%3C%2Fscript%3E%3Cstyle%3E%40keyframes%20flashFade%7B0%25%7Btransform%3Ascale%280%29%3Bopacity%3A.5%7D50%25%7Btransform%3Ascale%281.5%29%3Bopacity%3A.8%7D100%25%7Btransform%3Ascale%280%29%3Bopacity%3A0%7D%7D%3C%2Fstyle%3E
```


# 
# [Black screen]
```
data:text/html;charset=UTF-8,<title>%E2%80%8E<%2Ftitle><link%20href%3D"data%3Aimage%2Fgif%3Bbase64%2CR0lGODlhAQABAIAAAP%2F%2F%2FwAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw%3D%3D"rel%3Dicon%20type%3Dimage%2Fgif><style>body%7Bbackground-color%3A0%7D<%2Fstyle>
```


#
# [Instant Chatroom using peerjs]
```
data:text/html;charset=UTF-8,<!doctypehtml><html lang=en><meta charset=UTF-8><meta content="width=device-width,initial-scale=1"name=viewport><title>PeerJS P2P Chat</title><script src=https://unpkg.com/peerjs@1.5.4/dist/peerjs.min.js></script><input id=myId placeholder="Enter your ID"> <button onclick=initializePeer()>Initialize</button> <span id=idStatus></span><br><input id=peerId placeholder="Peer ID"> <button onclick=connectToPeer()>Connect</button> <button onclick=leaveChat()>Leave</button><br><input id=message placeholder=Message> <button onclick=sendMessage()>Send</button><br><ul id=chatLog></ul><script>let peer,conn;function initializePeer(){leaveChat();const e=document.getElementById("myId"),n=document.getElementById("idStatus"),t=new Peer(e.value,{debug:2});t.on("open",(function(o){console.log("ID is available:",o),n.textContent="ID is available!",n.style.color="green",e.value=o,peer=t,setupPeerListeners()})),t.on("error",(function(e){"unavailable-id"===e.type?(console.log("ID is taken"),n.textContent="ID is taken. Please choose another.",n.style.color="red",t.destroy()):(console.error("Error:",e),n.textContent="An error occurred. Please try again.",n.style.color="red")}))}function setupPeerListeners(){peer.on("connection",(function(e){conn=e,setupConnection()}))}function connectToPeer(){const e=document.getElementById("peerId").value;conn=peer.connect(e),setupConnection()}function setupConnection(){conn.on("open",(function(){conn.on("data",(function(e){addMessageToChat(e,conn.peer)}))}))}function sendMessage(){const e=document.getElementById("message").value;conn&&conn.open?(conn.send(e),addMessageToChat(e,"You"),document.getElementById("message").value=""):alert("Connection is not open. Please connect to a peer first.")}function leaveChat(){conn&&(conn.close(),conn=null,console.log("You have left the chat."),addMessageToChat("You have left the chat.","System")),peer&&(peer.destroy(),console.log("Peer connection closed."),document.getElementById("idStatus").textContent=""),(peer||conn)&&(document.getElementById("myId").value="",document.getElementById("peerId").value="",document.getElementById("message").value="")}function addMessageToChat(e,n){const t=document.getElementById("chatLog"),o=document.createElement("li");o.textContent=`${n}: ${e}`,t.appendChild(o)}window.onbeforeunload=function(){peer&&!peer.destroyed&&peer.destroy()}</script>
```


#
#[quick-paste-page generator]
```
data:text/html;charset=UTF-8,<!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1.0"><title>HTML,JS,and CSS Minifier</title><style> body{font-family:Arial,sans-serif;max-width:800px;margin:0 auto;padding:20px}textarea{width:100%;height:200px}</style></head><body><h1>HTML,JS,and CSS Minifier</h1><input type="file" id="fileInput" accept=".html,.htm,.js,.css"><textarea id="input" placeholder="Or paste your HTML,JS,or CSS here"></textarea><button onclick="minify()">Minify</button><h2>Minified Output:</h2><textarea id="output" readonly></textarea><button onclick="copyToClipboard()">Copy to Clipboard</button><script> function minify(){let input=document.getElementById('input').value;if(!input){alert('Please provide input');return}input=input.replace(input=input.replace(/\/\*[\s\S]*?\*\/|([^\\:]|^)\/\/.*$/gm,%27$1%27);input=input.replace(/\/\*[\s\S]*?\*\//g,%27%27);input=input.replace(/\s+/g,%27%20%27).replace(/%3E\s+%3C/g,%27%3E%3C%27).replace(/^\s+|\s+$/g,%27%27);input=input.replace(/\s*([{};,=:])\s*/g,%27$1%27).replace(/\s*\(\s*/g,%27(%27).replace(/\s*\)\s*/g,%27)%27).replace(/\s+/g,%27%20%27);input=input.replace(/\s*([{}:;,])\s*/g,%27$1%27).replace(/;\s*}/g,%27}%27).replace(/\s+/g,%27%20%27);input=%22data:text/html;charset=UTF-8,%22%20+%20input;document.getElementById(%27output%27).value=input}function%20copyToClipboard(){const%20output=document.getElementById(%27output%27);output.select();document.execCommand(%27copy%27);alert(%27Copied%20to%20clipboard!%27)}document.getElementById(%27fileInput%27).addEventListener(%27change%27,async(event)=%3E{const%20file=event.target.files[0];if(file){const%20content=await%20file.text();document.getElementById(%27input%27).value=content}});%3C/script%3E%3C/body%3E%3C/html%3E
```
