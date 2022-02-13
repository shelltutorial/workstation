# workstation
This repository contains an Ansible playbook used to set up a workstation with main tools for daily use.

Our playbook will install the following software:

- vim (apt repository)
- htop (apt repository)
- wget (apt repository)
- python3-pip (apt repository)
- make (apt repository)
- flameshot (apt repository)
- mlocate (apt repository)
- cherrytree (apt repository)
- terminator (apt repository)
- xpad (apt repository)
- Zoom (third part software with third party repository)
- VirtualBox (third part software with third party repository)
- Vagrant (third part software with third party repository)
- Microsoft Teams (third part software with third party repository)
- Google Chrome Browser (third part software with third party repository)
- Brave Browser (third part software with third party repository)

Tested for Ubuntu 18.04.

1. Go to your user's directory:

```console
cd ~/
```

2. Update and install Ansible:

```console
sudo apt update && sudo apt install ansible unzip git
```

3. Clone repository:

```console
git clone https://github.com/shelltutorial/workstation.git
```

4. Jump inside the directory:
5. 
```console
cd workstation/
```

5. Apply:

```console
ansible-playbook workstation.yml -K
```
