# hashjacking
All current versions of Windows are affected by an architectural vulnerability due to the presumptive nature of SMB authentication. Hashed credentials will secretly be sent in cleartext across the Internet. This attack vector is trivial to execute and has critical consequences. See proof of concept videos below.

## Author
Written by Julian "hob0" Dunning ([@hob0man](https://twitter.com/hob0man))

##Read more: 
[Hashjacking: Anyone can steal your Windows password](https://www.praetorian.com/blog/hashjacking-anyone-can-steal-your-windows-password)

##Proof of Concept Examples
###Email
![Email](https://raw.githubusercontent.com/hob0/hashjacking/master/email.gif)
###Direct Access With Chrome
![Direct with Chrome](https://raw.githubusercontent.com/hob0/hashjacking/master/Chrome.gif)
###Malicious image embedded in HTML
![HTTP](https://raw.githubusercontent.com/hob0/hashjacking/master/HTTP.gif)

