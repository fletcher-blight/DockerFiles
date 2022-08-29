FROM archlinux:latest
RUN pacman -Syu --noconfirm cmake make ninja git python-pip mingw-w64
RUN pip install conan

COPY toolchain.cmake /opt/toolchain.cmake
ENV CMAKE_TOOLCHAIN_FILE=/opt/toolchain.cmake