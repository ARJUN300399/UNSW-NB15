The UNSW-NB 15 data set was created by utilising an IXIA
PerfectStorm tool to extract a hybrid of modern normal and
contemporary attack activities of network traffic. A tcpdump
tool was used to capture 100 GB of raw network traffic (pcap
files). Each pcap file contains 1000 MB in order to make
analysis of packets easier. Argus and Bro-IDS techniques and
twelve procedures were executed in a parallel implementation
to generate 49 features with the class label. This data set
contains 2, 540,044 records which are stored in four CSV
files. Moreover, a part from this data set was divided into a
training set and a testing set. The training set involved 175,341
records, while the testing set contained 82,332 records from
all involved attack types and normal records [11], [12].
The involved attacks of the UNSW-NB15 data set were
categorised into nine types as in the following points:
1) Fuzzers: is an attack in which the attacker attempts to
discover security loopholes in an application, operating
system or a network by feeding it with the massive
inputting of random data to make it crash.
2) Analysis: is a type of variety intrusions that penetrate
the web applications via ports (e.g. port scans), emails
(e.g. spam) and web scripts (e.g. HTML files).
3) Backdoor: is a technique of bypassing a stealthy normal
authentication, securing unauthorised remote access to a
device, locating the entrance to plain text, as it struggles
to continue unobserved.
4) DoS: is an intrusion which disrupts the computer resources via memory so as to cause excessive business,
in order to prevent authorised requests from accessing a
device.
5) Exploit: is a sequence of instructions that takes advantage of a glitch, bug or vulnerability, causing an
unintentional or unsuspected behavior on a host or a
network.
6) Generic: is a technique that establishes against every
block-cipher using a hash function to cause a collision
without respect to the configuration of the block-cipher.
7) Reconnaissance: also can be defined as a probe, and it
is an attack which gathers information about a computer
network to evade its security controls.
8) Shellcode: is malware in which the attacker penetrates
a slight piece of code starting from a shell to control the
compromised machine.
9) Worm:is an attack in which the attacker replicates
itself to spread on other computers. Often, it utilises
a computer network to spread itself, depending on the
security failures of the target computer used to access
it
