# Fluxion by Mr. SAGE 

<p align="center"><img src="https://github.com/thehackingsage/Fluxion/blob/master/logos/Logo.png?raw=true" /></p>

"Fluxion is the Future of MITM WPA Attacks" It is a remake by Mr. SAGE with less bugs and more functionality. It's compatible with the latest release of Kali (rolling). The attack is mostly manual, but experimental versions will automatically handle most functionality from the stable releases. (https://thehackingsage.github.io/Fluxion/)

## How It Works :

* Scan the networks.
* Capture a handshake (can't be used without a valid handshake, it's necessary to verify the password)
* Use WEB Interface
* Launch a FakeAP instance to imitate the original access point
* Spawns a MDK3 process, which deauthenticates all users connected to the target network, so they can be lured to connect to the FakeAP and enter the WPA password.
* A fake DNS server is launched in order to capture all DNS requests and redirect them to the host running the script
* A captive portal is launched in order to serve a page, which prompts the user to enter their WPA password
* Each submitted password is verified by the handshake captured earlier
* The attack will automatically terminate, as soon as a correct password is submitted..

## How To Install? & How To Use? :
Watch This Tutorial : [Click Here](https://www.youtube.com/watch?v=i6VN5C2qLK4) (Tutorial in Hindi)

## Changelog :
Fluxion gets weekly updates with new features, improvements and bugfixes.
Be sure to check out the [changelog here](https://github.com/FluxionNetwork/fluxion/commits/master).

## Requirements :
A Linux-based operating system. We recommend Kali Linux 2 or Kali 2016.1 rolling. Kali 2 & 2016 support the latest aircrack-ng versions. An external wifi card is recommended.

## Disclaimer :

Fluxion is intended to be used for legal security purposes only, and you should only use it to protect networks/hosts you own or have permission to test. Any other use is not the responsibility of the developer(s).  Be sure that you understand and are complying with the Fluxion licenses and laws in your area.  In other words, don't be stupid, don't be an asshole, and use this tool responsibly and legally.

# License :

[MIT Licence](https://github.com/thehackingsage/Fluxion/blob/master/LICENSE)

Thats It... If You Like This Repo. Please Share This With Your Friends..

& Don't Forget To Follow Me At [Twitter](https://www.twitter.com/thehackingsage), [Instagram](https://www.instagram.com/thehackingsage), [Github](https://www.github.com/thehackingsage) & Don't Forget To SUBSCRIBE My [YouTube](https://www.youtube.com/channel/UCYK1n9A4TUq1CvGc6F3DzoA) Channel..!!!

***Thankyou.***
***Keep Visiting..***
***Enjoy.!!! :)***
