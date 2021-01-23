# lxcenter-taidos
I will name this fork as hypervm-taidos, right now i'm was able to install HyperVM in diferent OS (CentOS 6 and CentOS 7) for those who want to try hypervm working again you are now able to, i still need to make some changes on the installation process because of the hypervm-ng, the latest fork who changed some code for the good, now is down. some bugs have been found, like repository install 3 times. 

FAQ:
Q: Is secure use HyperVM?
A: I advert everyone thats not secure yet to run in production servers, right now is better test, develop this further, some exploids still need to check if they are solved.

Q: When it becomes available for the masses?
A: I dont know, right now i think, i still need testing, but after solve many issues and turn this to a working.

Q: I am able to test it now?
A: If you know somethings. Like install openvz and debug programs yes, i saw this kind of project die, and this home as 3 died forks, i believe this one will not, so please test as you want but please give a feedback on how improve it for the better, i have some ideias.

Repo of all RPM's of Lxcenter.org

Temporary download link is still thier server:

http://66.160.179.101/download/update/

http://75.98.169.138/download/update/


Its better keeping all RPM's for further development.

My repo:

https://ip-television.ml/repo (sorry was what i found free for me to put the files in)

If you want to install it and test like i am doing please do it:

yum-config-manager --add-repo https://raw.githubusercontent.com/taidos/lxcenter-repo/master/lxcenter.repo

or

wget https://raw.githubusercontent.com/taidos/lxcenter-repo/master/lxcenter.repo -O /etc/yum.repos.d/lxcenter.repo

Carlos Faustino

I will be more arround the HyperVM installation, until its a working panel, any help will be great :)


Credits:

Me: http://carlos-faustino.com
BigBoxHost: http://bigboxhost.com
