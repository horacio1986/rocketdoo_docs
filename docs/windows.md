## Windows and WSL2

Certainly we will not see step by step how to install WSL2 on Windows, since the internet is full of guides.
Even the official Windows website has a step by step guide on how to install WSL2 on your computers.

[Official WSL2 Guide](https://learn.microsoft.com/en-us/windows/wsl/install)

But what we will address are some recommendations on how to use this tool to be able to develop with Rocketdoo and WLS2
to develop with Rocketdoo and VSCode.

Assuming you already have WSL2 installed on your computer, properly configured with sudo access to the user you created.
Access to the user you created. Let's continue with some necessary steps to get our machine ready to develop with Rocketdoo and VSCode.
ready to be able to develop with ROCKETDOO. Remember that you can use any Linux distribution,
although for daily use we suppose that Ubuntu 20/22/24.04 or Debian 11/12 should be able to handle it.

## Necessary Steps:

1. Enter the WLS2 terminal.
2. Update Linux packages:

~~~ 
sudo apt update
~~~

3. Install git:

~~~
sudo apt install git -y
~~~

4. Install Visual Studio Code, inside WSL2:

~~~
sudo apt install code
~~~

5. After having installed VSCode, with the command :

~~~
code . 
~~~
you will be able to open the software in question.

6. Finally it is important to verify that you have installed “pip”, if not install it.

~~~
sudo apt install python-pip
~~~

***Luego sera necesario continuar con los pasos de la pagina Instrucciones ya que luego
de tener estas herramientas listas, los pasos de ejecucion son los mismos.***