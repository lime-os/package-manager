<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/banner_white.png">
  <source media="(prefers-color-scheme: light)" srcset=".github/banner_black.png">
  <img alt="LimeOS Banner">
</picture>

###

This lightweight and intuitive package manager is designed to provide access to 
the repositories of numerous other package managers, all in one place. Its goal 
is to offer a clean and clear overview of available packages, ranked from most 
reputable to least reputable, simplifying the process of discovering and 
installing software from various sources.

> **NOTE:** This project is still in development and is not ready for use.

## Building & Running

To build this project locally, you will need the following dependencies:

```bash
# The following command is intended for Debian based systems.
sudo apt install \
    gcc \
    make \
    libcurl4-openssl-dev \
    libncurses5-dev \
    libcjson-dev
```

Once the dependencies are installed, you can build the project by running:

```bash
make
```

This will compile the source code and generate an executable in the `./bin`
directory.

You can now run the package manager. Below is an example command:

```bash
./pkg install <package-name>
```

## License

This project is licensed under the GPL-3.0 License. This license reflects our 
commitment to ensuring that this software remains free and open-source. 
We believe in the values of freedom, transparency, and collaboration that the 
GPL-3.0 promotes, allowing users to freely use, modify, and distribute the 
software, ensuring that it remains a community-driven project.

For more details, see the `LICENSE.md` file.
