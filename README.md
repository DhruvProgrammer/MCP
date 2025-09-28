# MCP
<h1 align="center">🛠️ MCP Leave Manager Server</h1>
<p align="center">A beginner-friendly guide to setting up your first MCP server using Python, UV, VS Code, and Claude AI.</p>
<hr/>

<h2>📌 What Is an MCP Server?</h2>
<p>
MCP (Model Context Protocol) might sound complex, but it's simply a <b>bridge between your AI assistant (like ChatGPT or Claude)</b> and your real-world tools, files, or systems.
Instead of AI just talking — MCP lets it <b>take action</b>.
</p>

<h3>🔍 Example:</h3>
<p>Once connected to your MCP Leave Manager server, you could ask:</p>
<pre>
"Hey AI, how many leaves did Employee E001 take in August?"
</pre>
<p>
The MCP server reads the data and responds:<br/>
<b>"E001 was on leave for 5 days."</b><br/>
Simple. Automated. Smart.
</p>

<hr/>

<h2>🚀 Why Use MCP Servers?</h2>
<ul>
  <li>✅ <b>Convenience</b> – No more switching between tools manually.</li>
  <li>⚙️ <b>Automation</b> – Let AI handle repetitive or technical tasks.</li>
  <li>🔒 <b>Safety</b> – You control exactly what the AI can access.</li>
  <li>🔗 <b>Flexibility</b> – Connect anything from cloud apps to local scripts.</li>
</ul>

<hr/>

<h2>⚠️ Limitations</h2>
<ul>
  <li>🧠 Requires basic technical setup.</li>
  <li>🔌 Not plug-and-play — still early tech.</li>
  <li>🐢 Can be slightly slower due to communication layer.</li>
  <li>🛠️ Needs occasional maintenance.</li>
</ul>

<hr/>

<h2>🧰 Requirements</h2>
<ul>
  <li>A Laptop / PC</li>
  <li><a href="https://code.visualstudio.com/">VS Code (latest)</a></li>
  <li><a href="https://claude.ai/">Claude Desktop App</a></li>
  <li><a href="https://www.python.org/">Python (from python.org — NOT Microsoft Store)</a></li>
</ul>

<hr/>

<h2>📥 Installation & Setup</h2>

<h3>1️⃣ Install Python & Open Terminal (as Administrator)</h3>
<pre>
pip install uv
uv pip install mcp
uv pip install mcp[cli]
</pre>
<p><i>⚠️ Install <b>UV first</b> before installing MCP.</i></p>

<h3>2️⃣ Create Project Folder in VS Code</h3>
<pre>
uv init
</pre>
<p>This generates multiple files — leave them untouched.</p>

<h3>3️⃣ Open <code>main.py</code> and Paste Your MCP Server Code</h3>
<p>Example MCP server reference: <a href="https://github.com/DhruvProgrammer/MCP">https://github.com/DhruvProgrammer/MCP</a></p>

<h3>4️⃣ Install MCP Server into Claude</h3>
<pre>
uv run mcp install main.py
</pre>

<h3>5️⃣ Open Claude → <code>Ctrl + ,</code> → Developer Settings</h3>
<p>
✅ If you see <b>Leave Manager (running)</b> in blue — your MCP server is live!<br/>
❌ If it shows <b>Failed / Disconnected</b>, continue below.
</p>

<hr/>

<h2>🛠️ Common Issues & Fixes</h2>

<h3>🟡 Inside Claude:</h3>
<ul>
  <li>Enable the MCP tool under <b>Settings → Tools → Web Search → Leave Manager</b></li>
  <li>If missing, open Task Manager → End Claude → Reopen after 30-60 sec</li>
</ul>

<h3>🔴 Outside Claude:</h3>
<ul>
  <li>Restart your PC — surprisingly effective for random bugs.</li>
  <li>Uninstall Python from Control Panel if it was installed via Microsoft Store.</li>
  <li>Reinstall Python from <b>python.org</b> only.</li>
  <li>Ensure Python and UV paths exist in <b>Environment Variables → Path</b>.</li>
</ul>

<h3>🧠 Still Stuck?</h3>
<p>Open Claude → <code>Ctrl + ,</code> → Developer → Open Logs → Copy & Paste logs into ChatGPT — AI will tell you the issue.</p>

<hr/>

<h2>✅ Conclusion</h2>
<p>
An MCP server isn’t a scary tech beast — it’s just a <b>smart middleman</b> that gives your AI <b>hands to actually perform tasks.</b><br/>
Yes, setup takes a bit of patience — but once it’s working, it feels like magic.<br/><br/>
<b>You're not just chatting with AI anymore — you're commanding it.</b>
</p>

<hr/>

<p align="center">✨ Built with curiosity and caffeine by <b>Dhruv</b> ✨</p>
