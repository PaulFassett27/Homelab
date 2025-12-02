# Homelab
Notes and diagrams of my homelab stack

<h2>
Dell Optiplex 5050
</h2>
<h3>
  Initial Setup and Operating System
</h3>
<body>
  The first piece of hardware I acquired for my homelab was a refurbished Optiplex 5050 from a local electronics Refurbishing store. I got a pretty good deal and it came with an i5-7700 and 16 gb of ram. They ship these refurbished computers with no operating system installed so my first order of business was to install my OS of choice. I took a while to research and look into what OS would fit my needs the best and also help me gain useful skills along the way. I know I needed something lightweight enough to host as many applications as possible but I also wanted something that was stable. 
  I decided to download and install Debian 13 (Trixie).
</body>
<h3>
  Self Hosting Blog Website
</h3>
<body>
  As this was my first addition to my homelab I wanted to start off right and document everything I do so that I have records and proof that I have created things myself in this homelabbing journey. Immediately an idea sprung into my mind. My first project would be to create a website where I could write a blog about each project and go into depth with the decision process along with all of my steps along the way. This small server running linux would be a great place to host my small website and learn some good skills about correctly hosting a website. Eventually I would like to migrate the hosting of this website over into the cloud and deploy it with Terraform. But that is for another time.
</body>


<h2>
  Raspberry Pi
</h2>
<body>
  Right of the bat I set up a Pi Hole on my Raspberry Pi and configured it to be the main DNS server for my devices such as me and my wifes phones along with our tv. I found that there was a few confgiurations that Pi Hole was lacking so I switched to Adguard as I feel as if it was more robust and allowed me to have more control over the DNS settings.
</body>
