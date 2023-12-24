# Question & Answer
## Windows

## MAC OS
1. How to get the MAC OS version?   
   Run the below command to get the information:
   ```shell
   $ sw_vers
   ```
2. How to identify the command line we are using?   
   Run below command to get the information:
   ```shell
   $ echo $SHELL
   ```
   On macOS 10.15 Catalina and later, the default Terminal shell switches from the bash to zsh.   
   - For bash shell, we can put the environment variables at ~/.bash_profile or ~/.bashrc.
   - For zsh shell, we can put the environment variables at ~/.zshenv or ~/.zshrc.

4. How to remove JDK installation from the command line?   
   Navigate to the root directory in which the Java virtual machines are installed.
   ```shell
   $ cd /Library/Java/JavaVirtualMachines
   ```

   The directory whose name matches the following format:   
   `/Library/Java/JavaVirtualMachines/jdkmajor.minor.macro[_update].jdk`

   For example, to uninstall 8u6:
   ```shell
   $ rm -rf jdk1.8.0_06.jdk
   ```
   After uninstalling JDK, run the below command to verify the Java version.
   ```shell
   $ java -version
   ```
5. How to set up the JAVA_HOME on Mac?
   

## Linux
