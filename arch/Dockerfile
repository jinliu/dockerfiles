FROM base/archlinux
RUN echo 'Server = https://mirrors.ustc.edu.cn/archlinux/$repo/os/$arch' > /etc/pacman.d/mirrorlist 
RUN pacman -Sy --noconfirm openssh

EXPOSE 22
CMD sshd -D
