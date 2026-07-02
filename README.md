# MP3 Tag Reader

A command-line application written in **C** for reading and displaying metadata stored in MP3 files using the **ID3v2** tag format. The project demonstrates efficient binary file parsing, modular programming, and file handling techniques commonly used in systems programming.

---

## Project Overview

The MP3 Tag Reader extracts metadata embedded within MP3 files and displays it in a readable format. It validates the input file, parses ID3v2 frames, and retrieves information such as the song title, artist, album, year, genre, and comments without modifying the original audio content.

This project was developed to strengthen core C programming concepts including binary file processing, structures, command-line argument handling, and modular software design.

---

## Features

* Read ID3v2 metadata from MP3 files
* Display song title
* Display artist name
* Display album name
* Display release year
* Display genre
* Display comments
* Validate MP3 file format
* Handle invalid files and missing metadata gracefully
* Modular and maintainable code structure

---

## Technologies Used

| Category             | Technology                                                                           |
| -------------------- | ------------------------------------------------------------------------------------ |
| Programming Language | C                                                                                    |
| Compiler             | GCC                                                                                  |
| Platform             | Linux / Unix                                                                         |
| Concepts             | File Handling, Binary Files, Structures, Command-Line Arguments, String Manipulation |

---

## Project Structure

```text
MP3-Tag-Reader/
├── main.c
├── view.c
├── edit.c
├── support.c
├── main.h
├── Makefile
├── sample.mp3
└── README.md
```

---

## Build Instructions

Clone the repository:

```bash
git clone https://github.com/Shrinidhi-Khanchanale/MP3-Tag-Reader.git
cd MP3-Tag-Reader
```

Compile the project:

```bash
gcc *.c -o mp3_tag_reader
```

Or, if a Makefile is available:

```bash
make
```

---

## Usage

Display metadata from an MP3 file:

```bash
./mp3_tag_reader -v sample.mp3
```

If editing functionality is implemented:

```bash
./mp3_tag_reader -e -t "New Title" sample.mp3
```

---

## Sample Output

```text
--------------------------------------------------
             MP3 TAG INFORMATION
--------------------------------------------------

Title      : Shape of You
Artist     : Ed Sheeran
Album      : Divide
Year       : 2017
Genre      : Pop
Comments   : Sample MP3 File

--------------------------------------------------
```

---

## Key Concepts Demonstrated

* Binary file parsing
* ID3v2 metadata processing
* File pointer manipulation (`fopen`, `fread`, `fseek`, `ftell`)
* Structures and user-defined data types
* Command-line argument processing
* Error handling and input validation
* Modular programming in C

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Reading and interpreting binary file formats
* Designing modular applications in C
* Working with low-level file operations
* Implementing robust input validation
* Writing maintainable and reusable code

---

## Future Enhancements

* Support for ID3v1 and ID3v2.4 tags
* Album artwork extraction
* Batch processing of multiple MP3 files
* Interactive command-line interface
* Unicode metadata support
* Enhanced error reporting

---

## Author

**Shrinidhi Khanchanale**

Embedded Systems Trainee | C Programmer | IoT & Embedded Systems Enthusiast

GitHub: https://github.com/Shrinidhi-Khanchanale

---

## License

This project is intended for educational and learning purposes.
