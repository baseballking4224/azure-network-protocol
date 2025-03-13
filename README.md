
<h1>Proton VPN Setup & IP Address Testing</h1>
In this lab, I used Proton VPN on a Windows VM to explore how connecting via different VPN servers changes my public IP and potentially impacts region-based website content. I tested multiple server locations and confirmed each assigned IP address through whatismyipaddress.com.<br />

<h2>Focus points</h2>

-Public IP identification
-VPN installation & account setup
-Testing website differences when changing IP/country

<h2>tools & services</h2>

- Azure Windows VM or local Windows machine
-Proton VPN client
-Web browser checks (Google, Disney, etc.)

<h2>Actions and Observations</h2>
<p>
  Check Baseline Public IP
  <P>
I navigated to whatismyipaddress.com to note my current public IP. This gave me a baseline to compare once the VPN was activated.
  <P>
  <img width="478" alt="image" src="https://github.com/user-attachments/assets/871a60dd-29c4-453b-b3c7-1be4e1fdd441" />
</p>
<p>
Create Proton Account & Download Client
  <P>
I signed up for a Proton VPN account at protonvpn.com (free tier for this demo) and downloaded the Windows client installer.
  <P></P>
<img width="477" alt="image" src="https://github.com/user-attachments/assets/a6bc3921-b913-45c0-afea-59d1c070cd2c" />
  
<p>
</p>

Install & Launch Proton VPN
<P></P>
After running the installer on my VM, I logged in with my newly created account. The dashboard displays available servers around the world.
<img width="469" alt="image" src="https://github.com/user-attachments/assets/9c034c0f-8819-4eb1-80f0-9062c176b7e5" />
<P></P>
<img width="476" alt="image" src="https://github.com/user-attachments/assets/54afde00-8b3f-40b3-97fb-f65d9df08527" />

<p> 
</p>

Websites Before VPN
<P></P>
I visited google.com and disney.com to note any region-specific content. This helps detect changes once I connect to a VPN server in a different location.
<img width="370" alt="image" src="https://github.com/user-attachments/assets/6050cb5d-148c-4933-938e-66147c92f23f" />
<P></P>
<img width="365" alt="image" src="https://github.com/user-attachments/assets/6d245242-8a5a-422a-80b1-76033b945923" />

<p>
</p>

Connect to Proton VPN & Recheck IP
<P></P>
I picked a server in another country and clicked Connect. Returning to whatismyipaddress.com now showed a new public IP, often in the assigned server’s location.
<img width="369" alt="image" src="https://github.com/user-attachments/assets/2391dafa-a14d-4285-b1e1-be68dc3d09d1" />
<P></P>
<img width="368" alt="image" src="https://github.com/user-attachments/assets/a5fa520d-f2d9-43fa-affa-62dbe6e1e35e" />

<p>
</p>


Websites After VPN
<P></P>
Finally, with the VPN active, I reloaded google.com and disney.com. Depending on the server location, I occasionally saw content in another language or different region-based services. This highlights how easily the VPN changes your perceived location.
<img width="477" alt="image" src="https://github.com/user-attachments/assets/0814ef29-dac2-46d5-ac7c-a8fcd4afce3e" />
<P></P>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/f166f478-edbc-44cf-a79c-f3d411e9c9ee" />

<p> 
</p>
<p>
</p>

<h1>CONCLUSION</h1>
By using Proton VPN, I illustrated how connecting to different servers changes your external IP address and can influence localized content on websites. This lab underscores VPN benefits (e.g., privacy, bypassing regional restrictions) and the importance of understanding how public IP location can affect your browsing experience.
