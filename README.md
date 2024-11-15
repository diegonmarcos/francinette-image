<h1 align="center">Francinette install on <strong>42-Session-Ubuntu</strong></h1>

Francinette created by **[xicodomingues](https://github.com/xicodomingues)** is a tool to be able to test different projects of 42 (`libft`, `ft_printf`, `get_next_line`, `minitalk` and `pipex`).

Here is a simple installer that enables you to install Francinette on an **Ubuntu PC** within a **cluster of 42**  without `sudo` access. I would like to point out that I am not the creator of the Francinette! This is just a script that makes installation easier. Thanks to [xicodomingues](https://github.com/xicodomingues).

How does the installer work? It utilizes `Docker` to create an isolated Ubuntu environment which will automatically set up Francinette with all the necessary permissions within this virtual space. Your local `$HOME` directory will be shared with the Docker container, allowing the container to execute commands that interact with your files and thus run Francinette.

After installation, use the `francinette` or `paco` command inside your project's directory to execute it.

> [!note]
> This script was developed for installation on **42 school computers**. Use the original script for your personal computer, available [here](https://github.com/xicodomingues/francinette/tree/master#readme).

## INSTALL:

Copy and paste the following line into your terminal to kick off the installation, and you'll be all set to start testing your school 42 projects with Francinette in no time!

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/diegonmarcos/francinette-image/master/install.sh)"
```

## Documentation

I can only advise you to look at the [original Francinette documentation](https://github.com/xicodomingues/francinette/tree/master#readme) for good use of this great tool!

## Who should I thank?

* [WaRtr0](https://github.com/WaRtr0) for [francinette-image](https://github.com/WaRtr0/francinette-image)
* [xicodomingues](https://github.com/xicodomingues) and [arsalas](https://github.com/arsalas) creator of the [francinette](https://github.com/xicodomingues/francinette) having link different tests, carried out by the people below
* [Tripouille](https://github.com/Tripouille) for [libftTester](https://github.com/Tripouille/libftTester), [gnlTester](https://github.com/Tripouille/gnlTester) and [printfTester](https://github.com/Tripouille/printfTester)
* [jtoty](https://github.com/jtoty) and [y3ll0w42](https://github.com/y3ll0w42) for [libft-war-machine](https://github.com/y3ll0w42/libft-war-machine)
* [alelievr](https://github.com/alelievr) for [libft-unit-test](https://github.com/alelievr/libft-unit-test) and [printf-unit-test](https://github.com/alelievr/printf-unit-test)
* [cacharle](https://github.com/cacharle) for [ft_printf_test](https://github.com/cacharle/ft_printf_test)
* [vfurmane](https://github.com/vfurmane) for [pipex-tester](https://github.com/vfurmane/pipex-tester)
* [gmarcha](https://github.com/gmarcha) for [pipexMedic](https://github.com/gmarcha/pipexMedic)
