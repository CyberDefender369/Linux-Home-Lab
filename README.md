# Linux Home Lab


## Description

This project utilizes the Linux distribution Ubuntu and centers around a thorough exploration of operating system functionalities. To achieve this, the terminal is exclusively employed. It is common for beginners to shy away from becoming proficient with the terminal, but this project aims to demonstrate that mastering it is not a daunting task.

Key tasks include:
* Navigating the file system
* Performing file operations
* Performing directory operations
* Viewing and editing files
* File properties
* Locating files
* Manipulating text within files
* Compressing files
* File comparison
* Spellchecking
* Handling disks and file systems
* Implementing backups
* Monitoring processes
* Controlling process execution
* System reboot/shutdown
* User account administration
* Group management
* Host information retrieval
* Network connections analysis
* Web browsing
* Screen output management
* Clipboard operations
* Mathematical calculations
* Date and time handling
* Graphics manipulation
* Software installation
* Basic shell script programming


## Languages and Utilities Used

- Bash
- VMware Workstation 17 Player


## Environments Used

- Ubuntu 23.10


## Notes

Currently at controlling process execution.  

## Project Walk-Through:

- Navigating the file system
  - Moving through home directory
  ![home_dir](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/76f866bb-5d2a-45fe-a6f9-9691dccba058)

  - Moving through system directory
  ![system_dir](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/0a9364c2-12de-4cc6-852f-ecc88573c8af)


- Performing file operations
  - Listing all files
  ![ls_hidden](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/3aa5ea2b-258d-4cab-8659-56c888ff4a8a)

  - Long listing
  ![long_listing](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/61b43414-97f1-431f-999c-52b02c242922)

  - Copying file
  ![copy](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/fa07c970-cc66-4303-b69d-3b4637ba6a35)

  - Renaming and moving file
  ![move](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/1047c7b7-19ce-4c95-bc90-2ee5a541a31d)

  - Deleting file
  ![delete](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/785a77f7-91ba-4be1-9139-0e8c1dd0a6a5)


- Performing directory operations
  - Making directory
  ![create_dir](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/d55c05ed-f843-402c-8a79-ffdbff571764)

  - Deleting empty directory
  ![delete_empty_dir](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/3299a77d-3539-464d-830a-a48d6f29c43d)

  - Deleting nonempty directory
  ![delete_dir](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/65f12b67-068d-4ac8-b2d3-cd92b6689862)


- Viewing and editing files
  - Viewing entire file, with lines numbered, first 10 lines, and last 10 lines
  ![viewing](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/475563c4-727b-4b79-bea7-0611b3e62198)

  - Creating and writing data to file
  ![file_creation_edit](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/207ee066-2818-45b0-a667-77e95a44e2af)

  - Editing a file with Nano
  ![nano](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/a5e94527-3321-4ccd-a79b-a7f7cc03faa9)


- File properties
  - Displaying attributes of file
  ![stat](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/54ebade2-c267-4f79-88d6-86b6815f6fda)

  - Counting lines, words, and bytes
  ![wc](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/3b36f4df-647a-4640-a92e-c5c5a28618b7)

  - Guessing the type of file
  ![file](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/b7cc12ae-696f-4d42-906b-4d97b93b87c1)


- Locating files
  - Finding location of file
  ![find](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/b95e4b5e-90cf-491a-804d-0ccbd05d2f4d)


- Manipulating text within files
  - Finding all lines that contain the word "Linux"
  ![grep](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/dbb58461-5de5-4357-8cb3-bce9d5e935c0)

  - Combining text to standard output
  ![paste](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/78618dc5-ff11-4e10-a090-2175aeaeb417)

  - Capitalizing all text in a file
  ![tr](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/7f496360-0c0f-44d0-9803-d42cc020d17b)

  - Sorting text in aplabetical order
  ![sort](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/798a40d9-0004-44ae-901c-97cd177a0cca)

  - Removing dulpicate lines of text
  ![uniq](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/d953afb3-7df2-466e-b72d-259eee71ebde)

  - Printing first, third, and fifth word of each line
  ![awk](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/1729972a-4874-41cc-b313-75b5dc177fb8)


- Compressing files
  - Creating, compressing, and naming archiving file
  ![tar](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/c5806e4d-2ce8-4496-a262-20f5954d6ee8)


- File comparison
  - Verifying MD5 checksums
  ![md5](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/49a64784-144c-4112-99bf-9a5cf53d94c3)

  - Verifying SHA-256 checksums
  ![sha256](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/115378b0-c5b1-4831-997d-a828604ced76)


- Spellchecking
  - Looking up how to spell a word
  ![look](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/898f679e-022b-499e-a8b5-291b5aea1228)

  - Checking for misspelled words
  ![spell](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/7bc7e141-6b78-4fc7-b108-91a3fe3dd7a9)


- Handling disks and file systems
  - Displaying all mounted filesytems
  ![df](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/313af8cf-729a-469d-b685-57de9b94f8c8)

  - Mounting an empty directory
  ![mount](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/2d5cbc24-bae9-46f6-8ab9-ba8af2ee6935)


- Implementing backups
  - Copying a set of files locally
  ![rsync](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/f050b1c8-2cde-4847-98e6-23f1618f7278)


- Monitoring processes
  - Displaying all running processes
  ![ps](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/0e04ef6b-dd78-43b0-843b-7012e6211808)

  - Displaying system running time since last boot
  ![uptime](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/11d5d58f-0b1e-49a9-a0a6-3cc5d45fc59e)

  - Tracking running processes
  ![top](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/da6a4c33-f7b9-473e-8967-dcdcb83289fb)


- Controlling process execution
  - Terminating process
  ![kill](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/c4842722-de85-4bea-bc36-215b26685bb2)


- System shutdown
  - Rebooting system
  ![reboot](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/f261b22b-f434-4332-ba05-b4b162cf6e24)

  - Shutting down system
  ![shutdown](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/bf90242c-e380-4a23-83ce-b9ee536d9f9a)


- User account administration
  - Creating an account, then setting a password
  ![useradd-passwd](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/37e8524e-7d45-4899-a792-eac3e001bc56)

  - Deleting account (consider deactivating before deletion)
  ![userdel](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/551704e6-e3b3-45c3-8f79-5a3e26673e79)

  - Changing user shell
  ![usermod](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/91088756-34b7-4b75-9b3b-c48fa215456f)

- Group management
  - Creating group, then adding user to group
  


- Software installation
  - Installing spell program
  ![install_software](https://github.com/CyberDefender369/Linux-Home-Lab/assets/96165986/670362f0-0268-46fa-b426-b01482b7475e)

