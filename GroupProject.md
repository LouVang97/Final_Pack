# Welcome to the Netboot Project!

Lou Vang

CSCI 2461-70/71

Group Project - Netboot

Team Oops Slackers

**Introduction**

I began with no knowledge of Netboot, but with my teammates help I be able to
accomplished this project. In the group, I'm a supporter. The following below
are the works and assignments that I had done with this project.

**[Report 1](https://github.com/LouVang97/Week12/blob/master/Report%231.txt)**

Our groups began with this project without any knowledge of it, so everyone
were decided to did a background check before begin and assigned roles. In report 1, I searched
about the background of Netboot, the different types, and the requirements of
it. Also, I did a research how the internet and network work because this
Netboot will deal a lot of it. I would had to know which ports were required
for this process, so I did a research of that as well. Since, I still didn't
have enough knowledge of it, I went to YouTube and watched "How to install
Netboot and how is work".

**[Report 2](https://github.com/LouVang97/Week13/blob/master/Report%232.md)**

This week I worked on installed Netboot in the virtual box manager to have
knowledge of how it work. The type Netboot I installed was ISO(legacy) which
used for CD/DVD, virtual CDs like DRAC/iLO, VMare, and Virtual Box. However,
it doesn't success because without ipxe, window, and other things it won't
work.

**[Report 3](https://github.com/LouVang97/Week14/blob/master/Report3.md)**

This week I focus on installed iPXE(Preboot eXecution Environment) on the
USB. iPXE is the leading open source network boot firmware and a part of netboot
that will need to install to provide a user friendly menu from within the BIOS
that will easily choose the operating system along with any specific types of
versions or bootable flags. First, I went to ipxe's website to installed the
version of it. However, the biggest mistaked I made was I installed ipxe
without read the requirements of it. I went back to the website and read the
instruction.
1. Got to clone the iPXE source code
2. Installed the packages in order to build iPXE

However, it still doesn't work. I went to asked Pavel for help, since he did
the same thing and had accomplished. He told me to look at his report, but
while looking at it and try to configure I still couldn't figure it out. Some
steps in the report were unclear. During class, I asked him to show me how to
do it. By showing me how to process work, I be able to configured ipxe. During the
process I realized my mistakes. With liblzma, I configured wrong in the
first place, with Pavel's report I be able to configured right. The second
mistake I did was I forgot to turn the https(port 443) on in ipxe/src/config.
The last part of it was to guide ipxe to my home directory for me to be able to 
installed on my USB. I went to ipxe/src/bin and copied "ipxe.ios". I drag that to the USB
on rufus.

**[Report 4](https://github.com/LouVang97/Week15/blob/master/Report4.md)**

This week our group was focus on install a live window for our project to test
out the system. The window I chose to installed was Win10PE SE, which is a
lightweight Win10 PE environment using a Windows 10 DVD, x86, or x64
architecture. I installed Win10PE SE to run a live CD on Window 10.
1. I went to Win10PE SE's page to download the version of it
2. A window pop up after the installed is done, click accepted for the process
to complete
3. After the process completed, there was a survey to fill out
4. It created a .zip file, drag this file to the CD's file
5. Burn the CD

When I boot the CD on the computer, the boot was failed. However, with Pavel
helps I understand why and be able to configured. I started everything
over and the file came out a .iso file. Then I burned this file in the CD.

**]Presentation](https://sootsplash.csci2461.com/teamOps.html)** 

Before our group going to present, we gathered together to makre sure everything work. 
We putted everything together in one computer to test the system. Everything work 
prfectly and was success. During the presentation, everyone in our group talked a 
little about what they did. I didn't talked during the presentation because what I did
I already presented it. Lucus demonstrated who the process and everyone in the class
gathered around him.

**Challenge**

There were  many challenges I had face while worked on this project. As a
supporter, I tried my best to help my teammates and asked questions if I had
problems. Before I left, I always asked what was our goal for the week.
Sometimes I felt like I was useless and couldn't help them. However,
this doesn't bring me down. I worked harder each time I felt like that. I spent
hours each week to work on our goal. Whenever, I got stuck I asked my
teammates for help. Without them, I don't think I would be ale to accomplished
this project. I really appreciated for what they had done to me, especially
Pavel who help me the most.
