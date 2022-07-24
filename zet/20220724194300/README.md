# Removing and reinstalling Ubuntu Server

I was successful in installing Ubuntu server on VMWare in my M1ni about 2 months ago. I had to install it **FOUR TIMES**. The downside is Linux has some kernel issue VMWare can't do anything about it until there's a patch. They're still waiting. At the moment I have to install it without connecting to the Network. After installing and rebooting, I have to prevent Ubuntu from upgrading certain files so it can run properly. I have forgotten which files I'm supposed to hold!! This has proven zettels really are needed. Just note down everything you learn and/or ideas you come up with. I can see the light! Now I need to search again for which files I need to hold...

```bash
sudo apt-mark hold linux-generic linux-headers-generic linux-image-generic
```

Actually, I had saved the Gist page where it gives me the kernels to hold, but I'd forgotten is was there. I thought I had starred it on GitHub. Whatevs, now it's on here. I'll update when the kernel security issues are resolved. After I get the machine up and runnig like before, I'm gonna look for another version of Linux (server) and install it and do the process all over again.
