# Question & Answer
## Windows

## MAC OS
1. How to remove JDK installation from the terminal?   
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

## Linux
