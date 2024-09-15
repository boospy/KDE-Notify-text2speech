# KDE Notify text2speech

Das Projekt beinhaltet eine Sammlung von generierten Sprachdateien weitgehenst im Wavformat. Die Sprachdateien wurden mit Hilfe von [CereProc Cloud](https://www.cereproc.com) generiert und stehen dem Benutzer frei zur Verfügung. 

**You would like to show your appreciation for our help 8-o. Gladly. We thank you for your donation! ;)**

<a href="https://www.paypal.com/donate/?hosted_button_id=JTFYJYVH37MNE">
  <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif">
</a>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/L3L813B3CV)


## Installation
Die Installation kann über das hier bereitgestellte Git Repostory erfolgen, oder direkt über das bereit gestellte [Apt-Repostory](https://apt.iteas.at). Das Apt-Repostory ist der empfohlene Weg.

```
gpg -k && gpg --no-default-keyring --keyring /usr/share/keyrings/iteas-keyring.gpg --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 23CAE45582EB0928
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/iteas-keyring.gpg] https://apt.iteas.at/iteas noble main" > /etc/apt/sources.list.d/iteas.list
apt update
apt install kde-notify-text2speech
```

### Projekt Status
Beta-Status: Soundfiles müssen den Events in KDE manuell zugewiesen werden.
