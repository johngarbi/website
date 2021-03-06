+++
type = "article"
title = "Virtualizing Haiku"
date = "2013-01-07T17:06:04.000Z"
tags = []
+++

Haiku is a complete operating system, but you don't need to format your hard drive in order to use it. Haiku can be run inside a virtual machine. Using virtualization software, such as the programs listed below on this page, your computer can simulate a virtual computer that runs Haiku on top of your current operating system. This process is called virtualization. Virtualization is a fun and easy way to try out different operating systems without risking erasing your whole hard drive. Here's how to do it.
<!--break-->
To get started with running Haiku in a virtual machine, you will need to obtain a <a href="/get-haiku">Haiku image</a>. The ISO image will work with most virtual machine managers.

You will also need a virtual machine manager, also known as a hypervisor. These come in two flavors: hosted and native. Hosted hypervisors, as the name suggests, are hosted on another operating system. These are programs that you can install, like Firefox. Native hypervisors are operating systems themselves, and run directly on the host's hardware. Although hosted hypervisors provide poorer performance, they are much simpler to use.

With regard to performance, you should make sure that the virtualization options in your BIOS are activated (Intel VT-x or AMD-V). If your hypervisor supports that, you'll get a nice boost in performance. Choosing AHCI over IDE in the BIOS can be another.

<h3>Hosted hypervisors</h3>
<b>Multi-platform</b>
<ul>
    <li><a href="/guides/virtualizing/virtualbox">VirtualBox</a><ul>
        <li><a href="/guides/virtualizing/virtualbox-linux-debugging">with serial debugging under Linux</a></li>
        <li><a href="/guides/virtualizing/virtualbox-windows-debugging">with serial debugging under Windows</a></li>
    </ul>
    </li>
    <li><a href="/guides/virtualizing/bochs">Bochs</a></li>
</ul>
<h3>Native hypervisors</h3>
<ul>
    <li><a href="/guides/virtualizing/hyper-v">Hyper-V</a></li>
</ul>