---
ID: 1622
post_title: Attack of the Bots!
author: HusbandVader
post_excerpt: ""
layout: post
permalink: >
  https://portalrepository.com/2018/03/02/attack-of-the-bots/
published: true
post_date: 2018-03-02 00:16:55
---
At 4:00am US East Coast time on March 1st the enemies of The Atlas launched a global, brute-force botnet attack against The Portal Repository. However, despite their best attempts to hack this website I am happy to report that no harm was done and no user information was compromised during the assault.

[caption id="attachment_1624" align="aligncenter" width="1109"]<a href="https://portalrepository.com/wp-content/uploads/2018/03/ddosattack.png"><img class="wp-image-1624 size-full" src="https://portalrepository.com/wp-content/uploads/2018/03/ddosattack.png" alt="DDOS Attack Final Lockout Report" width="1109" height="196" /></a> Brute-Force Attack Final Lockout Report[/caption]

The attack focused exclusively on trying to brute-force non-existent account names that less-hardened websites sometimes leave vulnerable.  The final tally was nearly 3600 brute-force login attempts. Thankfully this site already implements professional-grade security software that not only fix common exploits but also detects and thwarts any kind of malicious activity.

[caption id="attachment_1625" align="aligncenter" width="668"]<a href="https://portalrepository.com/wp-content/uploads/2018/03/cloudflare.png"><img class="size-full wp-image-1625" src="https://portalrepository.com/wp-content/uploads/2018/03/cloudflare.png" alt="Protected by Cloudflare" width="668" height="180" /></a> Protected by Cloudflare[/caption]

In an effort to get one step ahead of these kinds of attacks I decided to move this site onto the <a href="https://www.cloudflare.com/" target="_blank" rel="noopener">Cloudflare</a> CDN network. Cloudflare specializes in DDoS (Distributed Denial of Service) mitigation. At 4:35pm (EST) I migrated the DNS to point to the new Cloudflare network. A little over an hour later at 5:44pm (EST) the DNS servers were fully propagated and the SSL certificate was authenticated.

After moving this site to the Cloudflare network the brute-force botnet attack was instantly stopped. In addition to providing higher security Cloudflare's CDN (Content Delivery Network) also will theoretically improve site performance, especially for users outside the United States. During the next few days I will be closely monitoring this site to see how it performs on Cloudflare's network. If you have any issues please leave a comment below, or email me using the contact form below.

Thank you for your patience during today's attack and for bearing with me while I moved the site to a more secure network. As you can imagine running a (secure) website can quickly become a costly ordeal. If you like The Portal Repository and want to help support it please consider donating via PayPal or becoming a <a href="https://www.patreon.com/portalrepository" target="_blank" rel="noopener">Patron</a>.

[contact-form-7 id="417" title="Basic"]

&nbsp;

[wpedon id="1052" align="center"]