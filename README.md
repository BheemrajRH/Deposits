#### Generate a New SSH Key

1. Microservices\MSVC\Deposits> ssh-keygen -t rsa -b 4096 -C "bheemarajrh@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (C:\Users\bheem/.ssh/id_rsa):

Enter passphrase (empty for no passphrase):
Enter same passphrase again:

Your identification has been saved in C:\Users\bheem/.ssh/id_rsa
Your public key has been saved in C:\Users\bheem/.ssh/id_rsa.pub

2. go tot GitHub → Settings → SSH and GPG keys → New SSH key → paste the key C:\Users\bheem/.ssh/id_rsa.pub.
