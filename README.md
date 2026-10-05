# FAT-Simulation
This project is written in C and it shows how FAT File System handles data around. It consists of 3 essential segments each FAT structure has. 
- **FAT** represented as Linked List,
- **ROOT** represented as Structure, 
- **DATA** represented a file input output.
  
With little extra things on my own like working with **Time** and ANSI colour codes.
It was a project for professor but it could serve as my personal achievement of understanding more advanced function of C 

Sadly it is not in english yet, but i will post a updated translated version and turn this into sort of console command like program with various abilities.

<img width="1122" height="633" alt="image" src="https://github.com/user-attachments/assets/9c6ab67c-aef5-4fea-a1b9-5c983ef3c2c0" />

Each cluster is filled with 8 words maximum and continue incrementing into other cluster which represents DATA. All of them are connected into a single Linked List which represents FAT. ROOT is just showing the pointer of a first cluster of a file. Then FAT overtakes as linked list to connected them, and DATA is assembled together into a sentence back.
