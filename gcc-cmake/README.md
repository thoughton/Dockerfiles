# gcc-cmake Dockerfile

Most CMake-including setups on here seem to use Ubuntu's apt-get to install it, but unfortunately Ubuntu's repositories contain quite an old version of CMake.

So I decided to make this setup instead. It's based on the latest official GCC repository, and downloads the CMake 3.7.2 binaries directly from their official website. (I wish there was an official binary release that always pointed to the very latest CMake version, but I could not find one. Otherwise I would've included that instead.)

Please note that this is my first attempt at using Docker, so it's very possible that I've made some mistakes. However, "it works for me" (™) and I am successfully using it to continuously build some CMake-based C11 projects.

