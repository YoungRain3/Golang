# Golang

05/10/2019 

## 編譯器選擇 

vscode 支持 windows  linux   Mac  

官網 https://code.visualstudio.com/

![](D:\Github\Golang\vscode.png)

### windows 安裝步驟



![](D:\Github\Golang\vscode1.png)

![](D:\Github\Golang\Annotation 2019-10-05 141750.png)

點擊下一步就好了。

### linux 安裝步驟

RHEL, Fedora, and CentOS based distributions

We currently ship the stable 64-bit VS Code in a yum repository, the following script will install the key and repository:

```
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
```

Then update the package cache and install the package using `dnf` (Fedora 22 and above):

```
sudo dnf check-update
sudo dnf install code
```

Or on older versions using `yum`:

```
yum check-update
sudo yum install code
```

Due to the manual signing process and the system we use to publish, the yum repo may lag behind and not get the latest version of VS Code immediately.

 ![](D:\Github\Golang\dnf.png)



![](D:\Github\Golang\Annotation 2019-10-05 144152.png)