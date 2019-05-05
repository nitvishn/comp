<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ch8</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#security-and-ethics">Security and Ethics</a>
<ul>
<li><a href="#security-risks">Security Risks</a></li>
<li><a href="#loss-of-data-and-data-corruption">Loss of data and data corruption</a></li>
<li><a href="#firewalls">Firewalls</a></li>
<li><a href="#proxy-servers">Proxy servers</a></li>
<li><a href="#security-protocols">Security protocols</a></li>
<li><a href="#encryption">Encryption</a></li>
<li><a href="#computer-ethics">Computer Ethics</a></li>
<li><a href="#non-commercial-software">Non-commercial software</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <h1 id="security-and-ethics">Security and Ethics</h1>
<h2 id="security-risks">Security Risks</h2>
<h3 id="hacking">Hacking</h3>
<ul>
<li>The act of gaining illegal access to a computer system.</li>
<li>It may not be harmful.</li>
<li>Effects:
<ol>
<li>Identity theft.</li>
<li>Gaining personal information.</li>
<li>Deletion, change, or corruption of data.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>Firewalls.</li>
<li>Strong passwords/IDs.</li>
<li>Anti-hacking software.</li>
</ol>
</li>
<li>Cracking.
<ul>
<li>Source code is edited for malicious purposes.</li>
<li><strong>Always totally illegal.</strong></li>
</ul>
</li>
</ul>
<h3 id="viruses">Viruses</h3>
<ul>
<li>Self-replicating program with the purpose of corrupting computer files, or triggering malfunction.</li>
<li>Effects.
<ol>
<li>Computer crash (freezes).</li>
<li>Deletion/Corruption of data.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>Anti-virus software.</li>
<li>Don’t use software from unknown sources.</li>
<li>Be careful when opening emails from unknown senders.</li>
</ol>
</li>
</ul>
<h3 id="phishing">Phishing</h3>
<ul>
<li>Legitimate-looking email which, when clicked on, sends the user to a fake website.</li>
<li>Effects.
<ol>
<li>Email creator can gain access to personal details.</li>
<li>Identity theft.</li>
<li>Fraud.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>ISPs filter phishing emails.</li>
<li>Caution while opening emails from unknown senders.</li>
</ol>
</li>
</ul>
<h3 id="pharming">Pharming</h3>
<ul>
<li>Malicious code.</li>
<li>Installed on hard drive or server.</li>
<li>Code will redirect user to fake website without user consent.</li>
<li>Effects.
<ol>
<li>Creator can gain access to personal data.</li>
<li>Identity theft.</li>
<li>Fraud.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>Anti-spyware.</li>
<li>User should look for clues that they are being redirected.</li>
</ol>
</li>
</ul>
<h3 id="war-driving">War driving</h3>
<ul>
<li>Locating &amp; illegally using wireless internet.</li>
<li>Effects.
<ol>
<li>Stealing internet time.</li>
<li>Hacking &amp; stealing user’s password.</li>
<li>Hacking &amp; stealing user’s personal data.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>Use complex passwords.</li>
<li>Firewall.</li>
<li>Wired equivalent privacy (WEP) encryption.</li>
</ol>
</li>
</ul>
<h3 id="spywarekey-logging-software.">Spyware/Key-logging software.</h3>
<ul>
<li>Software that gathers data by monitoring key presses on user’s keyboard.</li>
<li>Effects.
<ol>
<li>Access to all keyboard-entered data.</li>
<li>Other spyware can be installed.</li>
<li>Access to cookie data.</li>
<li>Can change user’s default web browser.</li>
</ol>
</li>
<li>Prevention.
<ol>
<li>Anti-spyware.</li>
<li>Look for clues that keyboard activity is being monitored.</li>
<li>Virtual keyboard.</li>
</ol>
</li>
</ul>
<h3 id="cookies">Cookies</h3>
<ul>
<li>Packet of data sent from web server to web browser.</li>
<li>Generated every time user accesses website.</li>
<li>Contains key data about user to maintain user preferences.</li>
<li>The information gathered by cookies forms an <strong>anonymous user profile</strong> which can be used to track users’ activity.</li>
</ul>
<h3 id="denial-of-service-attacks">Denial of service attacks</h3>
<p>An attempt at preventing users from accessing part of a network, notably an internet server. This can be done by flooding the internet server with useless traffic.</p>
<ul>
<li>Users might not be able to:
<ul>
<li>access their emails</li>
<li>access websites/web pages</li>
<li>access online services</li>
</ul>
</li>
<li>Mitigation (both user side and web server side)
<ul>
<li>using an up-to-date malware/virus checker</li>
<li>setting up a firewall to restrict traffic to and from the internet server or user’s computer</li>
<li>applying email filters to manage or filter out unwanted traffic or spam emails</li>
</ul>
</li>
<li>Signs to look out for DoS:
<ul>
<li>slow network performance</li>
<li>inability to access particular websites</li>
<li>large amounts of spam email reaching the user’s email account</li>
</ul>
</li>
</ul>
<hr>
<h2 id="loss-of-data-and-data-corruption">Loss of data and data corruption</h2>
<p>To prevent the deletion or corruption of data:</p>
<ol>
<li>Use back-ups in case something goes wrong</li>
<li>Use parallel systems as back-up hardware</li>
<li>Save data on a regular basis</li>
<li>Use passwords and user ids to restrict access to authorised users only</li>
<li>Train users so that they are aware of the correct operation of hardware</li>
</ol>
<hr>
<h2 id="firewalls">Firewalls</h2>
<p>A firewall is either software or hardware. It sits between the user’s computer and an external network and filters information in and out of the computer.</p>
<h3 id="what-it-does">What it does</h3>
<ol>
<li>Examines the traffic between the user’s computer and the internet</li>
<li>Checks whether incoming or outgoing data meets a given set of criteria</li>
<li>If not, then the firewall blocks the traffic and gives the user or network manager a warning that there might be a security issue</li>
<li>Logs all incoming and outgoing traffic for later interrogation by network manager or users</li>
<li>Prevents access to certain undesirable sites using criteria.</li>
<li>Warns the user if software on their system is trying to access an external data source.</li>
</ol>
<h3 id="drawbacks">Drawbacks</h3>
<ol>
<li>It can’t prevent individuals on internal networks from using their own modems to bypass the firewall</li>
<li>It can’t control employee misconduct or carelessness (control of passwords or use of accounts)</li>
<li>Users on stand-alone computers can choose to disable the firewall, leaving their computer open to harmful traffic from the internet</li>
</ol>
<hr>
<h2 id="proxy-servers">Proxy servers</h2>
<ul>
<li>Proxy servers act as an intermediary between the user and web server.</li>
</ul>
<h3 id="what-it-does-1">What it does</h3>
<ol>
<li>Everything that a firewall does</li>
<li>Uses a feature known as <strong>cache</strong> to speed up access to a website by storing its files in the proxy server so that the cached files can be served to the user</li>
<li>Keeps the user’s IP address secret</li>
</ol>
<hr>
<h2 id="security-protocols">Security protocols</h2>
<h3 id="secure-sockets-layer-ssl">Secure Sockets Layer (SSL)</h3>
<p>This is a type of protocol that allows data to be sent and received securely across the internet.</p>
<h4 id="how-it-works">How it works</h4>
<ol>
<li>The user’s web browser sends a message so that it can connect with the required website which is secured by SSL.</li>
<li>The web browser then requests that the web server identifies itself</li>
<li>The web server responds by sending a cop of its SSL certificate to the user’s web browser</li>
<li>If the web browser can authenticate this certificate, it sends a message back to the web server to allow communication to begin</li>
<li>Once this message is received, the web server acknowledges the web browser, and the SSL-encrypted two-way data transfer begins</li>
</ol>
<h3 id="transport-layer-security-tls">Transport Layer Security (TLS)</h3>
<p>It is formed of two layers:<br>
1. Record protocol<br>
2. Handshake protocol</p>
<h4 id="session-caching">Session caching</h4>
<ul>
<li>A lot of computer time is required to open a TLS session</li>
<li>TLS can either establish a new session or resume an existing session.</li>
<li>Resuming an existing session considerably boosts system performance.</li>
</ul>
<h4 id="differences-between-ssl-and-tls">Differences between SSL and TLS</h4>
<ul>
<li>It is possible to extend TLS by adding new authentication methods</li>
<li>TLS makes use of session caching which improves the overall performance</li>
<li>TLS separates the handshaking process from the record protocol</li>
</ul>
<hr>
<h2 id="encryption">Encryption</h2>
<h3 id="symmetric-encryption">Symmetric encryption</h3>
<ul>
<li>Uses a key which can be used to both encrypt and decrypt the ciphertext.</li>
<li>The <strong>key distribution problem</strong> arises when the sender has to send the key along with the message, which could then be intercepted  by a hacker and used to decrypt the message.</li>
</ul>
<h3 id="asymmetric-encryption">Asymmetric encryption</h3>
<ul>
<li>A public key is known to both the sender and receiver.</li>
<li>The private key is only known by the receiver.</li>
<li>The process
<ol>
<li>The sender applies a symmetric key to encrypt the message</li>
<li>The symmetric key is then encrypted using the receiver’s public key</li>
<li>The message is sent over the internet</li>
<li>The receiver decrypts the symmetric key using their private key</li>
<li>The decoded symmetric key is now used to decrypt the message sent by user A.</li>
</ol>
</li>
</ul>
<hr>
<h2 id="computer-ethics">Computer Ethics</h2>
<p>Computer ethics is a set of principles set out to regulate the use of computers. Three factors are considered:</p>
<ol>
<li>Intellectual property rights</li>
<li>Privacy issues</li>
<li>Effect of computers on society</li>
</ol>
<hr>
<h2 id="non-commercial-software">Non-commercial software</h2>
<h3 id="free-software">Free Software</h3>
<ul>
<li>Users have the freedom to run, copy, change or adapt free software, regardless of purpose.</li>
<li>However, the user:
<ul>
<li>cannot produce software which copies existing software subject to copyright laws</li>
<li>cannot adapt the software in such a way that it infringes copyright laws protecting other software</li>
<li>may not use the source code to produce software which is deemed offensive by third parties.</li>
</ul>
</li>
</ul>
<h3 id="freeware">Freeware</h3>
<ul>
<li>This is software that a user can download from the internet free of charge.</li>
<li>There are no fees associated with using the software.</li>
<li>However, this is subject to copyright laws.</li>
<li>The user is not allowed to study or modify the source code in any way.</li>
</ul>
<h3 id="shareware">Shareware</h3>
<ul>
<li>Users are allowed to try our software free of charge for a trial period.</li>
<li>The trial version of the software is missing some of the features found in the full version.</li>
<li>Fully protected by copyright laws.</li>
<li>Permission needs to be obtained to distribute the software.</li>
</ul>
<hr>

    </div>
  </div>
</body>

</html>
