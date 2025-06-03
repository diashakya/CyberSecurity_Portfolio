## Analyzing a Cyber Attack

# Types of malware
Cybercriminals use many different types of malicious software, or malware, to carry out their activities. Malware is any code that can be used to steal data, bypass access controls, or cause harm to or compromise a system. Knowing what the different types are and how they spread is key to containing and removing them.

# Most common Malware
1. Spyware

![Spyware](images/spyware.png)

Designed to track and spy on you, spyware monitors your online activity and can log every key you press on your keyboard, as well as capture almost any of your data, including sensitive personal information such as your online banking details. Spyware does this by modifying the security settings on your devices.

It often bundles itself with legitimate software or Trojan horses.
Legitimate software = Software that is genuine, legal, and safe to use

2. Adware

![Adware](images/adware.png)

Adware is often installed with some versions of software and is designed to automatically deliver advertisements to a user, most often on a web browser. You know it when you see it! It’s hard to ignore when you’re faced with constant pop-up ads on your screen.

It is common for adware to come with spyware.

3. Backdoor

![Backdoor](images/backdoor.png)

This type of malware is used to gain unauthorized access by bypassing the normal authentication procedures to access a system. As a result, hackers can gain remote access to resources within an application and issue remote system commands.

A backdoor works in the background and is difficult to detect.

4. Ransomware

![Ransomware](images/ransomware.png)

This malware is designed to hold a computer system or the data it contains captive until a payment is made. Ransomware usually works by encrypting your data so that you can’t access it.

Some versions of ransomware can take advantage of specific system vulnerabilities to lock it down. Ransomware is often spread through phishing emails that encourage you to download a malicious attachment or through a software vulnerability.

5. Scareware

![Scareware](images/scareware.png)

This is a type of malware that uses 'scare’ tactics to trick you into taking a specific action. Scareware mainly consists of operating system style windows that pop up to warn you that your system is at risk and needs to run a specific program for it to return to normal operation.

If you agree to execute the specific program, your system will become infected with malware.

6. Rootkit

![Rootkit](images/rootkit.png)

This malware is designed to modify the operating system to create a backdoor, which attackers can then use to access your computer remotely. Most rootkits take advantage of software vulnerabilities to gain access to resources that normally shouldn’t be accessible (privilege escalation) and modify system files.

Rootkits can also modify system forensics and monitoring tools, making them very hard to detect. In most cases, a computer infected by a rootkit has to be wiped and any required software reinstalled.

7. Virus

![Virus](images/virus.png)

A virus is a type of computer program that, when executed, replicates and attaches itself to other executable files, such as a document, by inserting its own code. Most viruses require end-user interaction to initiate activation and can be written to act on a specific date or time.

Viruses can be relatively harmless, such as those that display a funny image. Or they can be destructive, such as those that modify or delete data.

Viruses can also be programmed to mutate in order to avoid detection. Most viruses are spread by USB drives, optical disks, network shares or email.

8. Trojan horse

![Trojan horse](images/Trojanhorse.png)

This malware carries out malicious operations by masking its true intent. It might appear legitimate but is, in fact, very dangerous. Trojans exploit your user privileges and are most often found in image files, audio files or games.

Unlike viruses, Trojans do not self-replicate but act as a decoy to sneak malicious software past unsuspecting users.

9. Worms

![Worms](images/worms.png)

This is a type of malware that replicates itself in order to spread from one computer to another. Unlike a virus, which requires a host program to run, worms can run by themselves. Other than the initial infection of the host, they do not require user participation and can spread very quickly over the network.

Worms share similar patterns: They exploit system vulnerabilities, they have a way to propagate themselves, and they all contain malicious code (payload) to cause damage to computer systems or networks.

Worms are responsible for some of the most devastating attacks on the Internet. In 2001, the Code Red worm had infected over 300,000 servers in just 19 hours.

## Sypmtoms of Malware
Regardless of the type of malware a system has been infected with, there are some common symptoms to look out for. These include:
i. an increase in CPU usage, which slows down your device
ii. your computer freezing or crashing down
iii. a decrease in your web browsing speed
iv. unexplainable problems with your network connections
v. modified or deleted files
vi. the presence of unknown files, programs or desktop icons
vii. unknown processes running
viii. programs turning off or reconfiguring themselves
ix. emails being sent without your knowledge or consent.

## Methods of Infilteration
Infiltration is how attackers gain unauthorized access to a system, network, or device  often by bypassing defenses stealthily.

1. Social Engineering
Social engineering is the manipulation of people into performing actions or divulging confidential information. Social engineers often rely on people’s willingness to be helpful, but they also prey on their weaknesses. 

For example, an attacker will call an authorized employee with an urgent problem that requires immediate network access and appeal to the employee’s vanity or greed or invoke authority by using name-dropping techniques in order to gain this access.

i. Pretexting

![Pretexting](images/pretexting.png)

This is when an attacker calls an individual and lies to them in an attempt to gain access to privileged data.

For example, pretending to need a person’s personal or financial data in order to confirm their identity.

ii. tailgating

![Tailgating](images/tailgating.png)

This is when an attacker quickly follows an authorized person into a secure, physical location.

iii. Something for something (quid pro quo)

![Inexchange](images/free.png)

This is when an attacker requests personal information from a person in exchange for something, like a free gift.

2. Denial-of-Service
Denial-of-Service (DoS) attacks are a type of network attack that is relatively simple to carry out, even by an unskilled attacker. A DoS attack results in some sort of interruption of network service to users, devices or applications.

# Two main types of DoS attack
i. Overwhelming quality of traffic
This is when a network, host or application is sent an enormous amount of data at a rate which it cannot handle. This causes a slowdown in transmission or response, or the device or service to crash.

ii. Maliciously formatted packets
A packet is a collection of data that flows between a source and a receiver computer or application over a network, such as the internet. When a maliciously formatted packet is sent, the receiver will be unable to handle it.

foreg: If an attacker forwards packets containing errors or improperly formatted packets that cannot be identified by an application, this will cause the receiving device to run very slowly or crash.

 DoS attacks are considered a major risk because they can easily interrupt communication and cause significant loss of time and money.

 3. Distributed DoS
 A Distributed DoS (DDoS) attack is similar to a DoS attack but originates from multiple, coordinated sources. For example:

An attacker builds a network (botnet) of infected hosts called zombies, which are controlled by handler systems.
The zombie computers will constantly scan and infect more hosts, creating more and more zombies.
When ready, the hacker will instruct the handler systems to make the botnet of zombies carry out a DDoS attack.