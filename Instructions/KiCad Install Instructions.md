## Kicad Install Instructions

This project is dependant on my [PCIexpress-KiCad repository](https://github.com/Supercookiegaming/PCIexpress-KiCad/tree/89d8b5851c22fd8a89731272d48e080e1a528090). The linked commit of PCIexpress-KiCad is the version used in this project.

1. Clone the repository and its dependants to your desired location using your preferred method. For example 

   `cd desired-repository-location`
   
   `git clone https://github.com/Supercookiegaming/M.2-to-USB.git`
   
2. Install the symbol librarys by opening KiCad 9 then going to Prefrences>Manage Symbol Librarys...

    ![Symbol Manager Location](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Symbol%20Library%20Location.jpg)
   
3. Click the plus symbol in the Symbol Library window. The number of rows added must be equal to the number of libraries you are adding.

    ![Symbol Plus Button](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Symbol%20Library%20Plus%20Button.jpg)
   
4. Set the Nickname of the new row(s) to

      
   `M.2-to-USB-Library`
   


5. Set the Library Path to 


   
   `respository-location/M.2-to-USB/KiCad Files/M.2-to-USB-Library.kicad_sym`


   Example of correctly added Symbol Libraries

   ![Correctly added Symbol Libraries](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Symbol%20Library%20Example.jpg)
   
6. Click Ok to save.
7. Install the footprint librarys by going to Prefrences>Manage Footprint Librarys...

    ![Footprint Manager Location](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Footprint%20Library%20Location.jpg)
    
8. Click the plus symbol in the Footprint Library window. The number of rows added must be equal to the number of libraries you are adding.

    ![Footprint Plus Button](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Footprint%20Library%20Plus%20Button.jpg)
    
9. Set the Nickname of the new row(s) to

   
    `M.2-to-USB-Library`
   


10. Set the Library Path to 

   
    `respository-location/M.2-to-USB/KiCad Files/M.2-to-USB-Library.pretty`



    Example of correctly added Footprint Libraries:

    ![Correctly added Footprint Libraries](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Footprint%20Library%20Example.jpg)
11. Click Ok to save.   
12. Add the library's internal path by going to Prefrences > Configure Paths...

    ![Configure Path Loction](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Configure%20Paths%20Location.jpg)
    
13. Click the plus symbol in the Configure Paths window.

    ![Path Plus Button](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Configure%20Paths%20Plus%20Button.jpg)
    
14. Set the Name to

    `KICAD9_USER_M2USB_REPO_DIR`

15. Set the Path to root folder of the repository
    
     `repository-location/M.2-to-USB`
    
    Example of correctly added path:

    ![correctly added path](https://github.com/Supercookiegaming/M.2-to-USB/blob/e2acc7e42a25a49ea7f5bd83e153a5057910e5da/Instructions/Instruction%20Pictures/Configure%20Paths%20Exmaple.jpg)

16. Click Ok to Save
