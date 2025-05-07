# Proxy/Dockerfile
FROM debian:bullseye
RUN apt update && apt upgrade -y \
 && apt install -y curl git zsh neovim python3 python3-pip ssh locales
# (ajoute ici ton script install_debian_only.sh + entrypoint si besoin)
EXPOSE 2222
CMD ["/usr/sbin/sshd", "-D"]
