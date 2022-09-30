FROM ghcr.io/pi-hole/ftl-build:x86_64 AS FTL-AD

RUN apt-get update && apt-get upgrade -y && apt-get install -y build-essential realmd libnss-sss libpam-sss sssd sssd-tools \
adcli samba-common-bin oddjob oddjob-mkhomedir packagekit libldap-dev

RUN useradd -m vscode