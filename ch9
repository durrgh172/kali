#Understanding the Boot Process

Any time you modify the way that your computer boots, the possibility exists that you won’t get the results that you would expect. In these cases, it’s useful to know where you can turn for more information about what is happening during startup. The reports that you receive on a particular boot can better guide you, once you understand something about what’s supposed to happen when a Linux system boots.

Extracting Information about the Boot Process

Certain Linux kernel and module log information is stored in what is called the kernel ring buffer. By default, Linux displays messages destined for the kernel ring buffer during the boot process—they’re those messages that scroll past too quickly to read. You can inspect this information with this command:

# dmesg

This command generates a lot of output, so you may want to pipe it through the less pager or redirect it to a file. Here are some examples of these commands:

		# dmesg | less

		# dmesg > boot.messages

