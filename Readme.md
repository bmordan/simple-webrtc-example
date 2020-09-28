<h1>Hackathon Challenge</h1>
<p>How does this work? First You need to establish the root peer. To do this use
<br /><pre>http://localhost:3000/#1</pre><br />
("#1" on the URL) to establish the root peer. You should then see a printout of a JSON object rendered on the page. Copy this and open another browser window and visit: <pre>http://loaclhost:3000</pre> (without the "#1" on the URL) and paste the "offer" JSON object into the field. Then click on <button>connect</button> wait for the "ask" to be rendered in that browser window. Then you can copy and paste that "ask" into your original browser window (with "#1" on the URL).

![](https://user-images.githubusercontent.com/4499581/69050963-f8458100-09fa-11ea-9d52-b6bddb484e73.jpg)

Finally press <button>connect</button> and you should see the peers connect over WebRTC and the video streams being rendered in each others window.</p>
<p>Can you create a piece of software that enables people to video chat without having to do the cutting and pasteing in this example? You need to facilitate the peers discovering each other and establishing connections.</p>

![](https://user-images.githubusercontent.com/4499581/69050955-f5e32700-09fa-11ea-9545-72f656ae4514.jpg)
