# Creating a Windows VM on Mac for browser testing

This is easy. Honest. My advice is:

1. Download 'Virtualbox' - this is an application that lets you run VM on your Mac:
https://www.virtualbox.org/wiki/Downloads

2. Install it.

3. Download an appropriate Windows image:
http://www.modern.ie/en-us/virtualization-tools#downloads

	Go to > "Select Desired Testing OS" > "Mac" > "Select Virtualisation Platform" > "Virtual box" > Download whichever one you want and wait… It will take for ever so do it in work :)

	I'd recommend not using Windows 8 unless there is a good reason to - it'll take bloody ages to load!

4. If only an OVA file exists for that VM, that file can be opened directly, else:
	* From the terminal, allow the downloaded file to execute by typing chmod +x filename.sfx on the SFX file only.
	* Run the SFX file from a terminal, such as by ./filename.sfx and it will expand into the OVA you can open with VirtualBox.

5. Find that OVA file you've extracted (i.e. IE10.Win8.For.MacVirtualBox.ova) and double-click on it.

6. Give it a while. It may say 2 hours, but for me it just took 20 minutes.

7. In VirtualBox click on the new VM you just added in the left hand column and hit 'start'.

8. Windows ahoy. I'm not sure what the limitations of this are, but you can use the browser to your hearts content.

This used to be a lot easier when ~~I felt happy ripping off~~ other people used ripped off software, but at least this way is safe and legal.
