# push_swap

![](https://img.shields.io/badge/Language-C-blue)
![](https://img.shields.io/badge/School-42-black)

<p align=center>
  <img width="200" height="200" src="https://github.com/byaliego/42-project-badges/blob/main/badges/get_next_linem.png"/>
</p>
<p align="center">
 <img src="https://img.shields.io/badge/Puntuation-125%2F100-brightgreen">
</p>

## Description

**get_next_line** is a project developed by 42School to create a function that reads a file descriptor and returns a line from that file. The function allows reading from multiple file descriptors without losing the reading thread. It provides a convenient way to process files line by line, regardless of their size or content.

The get_next_line function takes a file descriptor as a parameter and dynamically allocates memory to store the line read from the file. It reads the file in small, manageable chunks, ensuring efficient memory usage and preventing buffer overflows. The function keeps track of the file position, allowing consecutive calls to retrieve subsequent lines.

Students are required to implement the function using appropriate memory management techniques and file manipulation methods. They need to handle cases where a line exceeds the read buffer or spans across multiple read operations. Error handling and resource cleanup are also crucial aspects of the implementation.

The get_next_line project serves as an opportunity for students to deepen their understanding of file input/output operations, memory allocation, and data manipulation. It enhances their ability to work with complex I/O scenarios and strengthens their programming skills in C.

## Documentation

* Peer to Peer
* [ChatGPT](https://chat.openai.com/)