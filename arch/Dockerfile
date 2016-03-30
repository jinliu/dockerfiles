FROM base/archlinux
RUN echo 'Server = https://mirrors.ustc.edu.cn/archlinux/$repo/os/$arch' > /etc/pacman.d/mirrorlist 
RUN yaourt -Sy openssh

EXPOSE 22
CMD sshd -D
