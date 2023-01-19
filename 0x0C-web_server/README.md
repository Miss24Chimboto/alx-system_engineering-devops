<h1>Web server</h1>
<h2>A Bash script that transfers a file from our client to a server:</h2>
<ul>Accepts 4 parameters</ul>
<ol>
<li>The path to the file to be transferred</li>
<li>The IP of the server we want to transfer the file to</li>
<li>The username scp connects with</li>
<li>The path to the SSH private key that scp uses</li>
</ol>
<ul>
<li>Display Usage: 0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY if less than 3 parameters passed</li>
<li>scp must transfer the file to the user home directory ~/</li>
<li>Strict host key checking must be disabled when using scp</li>
</ul>
