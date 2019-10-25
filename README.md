# CPUtemp
CPUtemp (raspbian)
 - will view the CPU temp and frequency in raspbian OS
 - thermal locations can vary on other linux systems
 
 
 If you want to view the temp permanently in your terminal you can create an alias in your .bashrc
 1. move the CPUtemp file to /bin/ (mv CPUtemp /bin)
 2. edit the bashrc (sudo nano ~/.bashrc)
 3. search for aliases (in nano just type CTRL + W and search for aliases)
 4. example for the alias: alias temp="watch -n 0.5 -t CPUtemp"
 5. open a new terminal and type temp and it should work.
 
 
