# MP3 Tag Reader & Editor (C)

## Overview
MP3 Tag Reader & Editor is a C-based application that reads and modifies ID3 metadata tags from MP3 audio files. The project allows users to view and edit information such as song title, artist, album, year, and genre by directly accessing binary data in MP3 files.

This project demonstrates low-level file handling, binary data processing, and structured programming, making it relevant for system programming and embedded software roles.

## Features
- Read ID3 metadata from MP3 files
- Edit MP3 tag information:
  - Title
  - Artist
  - Album
  - Year
  - Genre
- Supports ID3v1 / ID3v2 tags
- Validates MP3 file format
- Menu-driven console interface

## Technologies Used
- Language: C
- Concepts:
  - File handling (binary mode)
  - Structures and pointers
  - String manipulation
  - Bitwise operations
  - Modular programming

## Project Flow

### Reading Tags
1. Open MP3 file in binary mode.
2. Validate ID3 tag presence.
3. Read metadata fields from the header.
4. Display tag information to the user.

### Editing Tags
1. Select the tag field to edit.
2. Update metadata with user input.
3. Write modified data back to the MP3 file.
4. Save and close the file safely.

## Usage

### Compilation
gcc *.c -o mp3tag

### View MP3 Tags
./mp3tag -v song.mp3

### Edit MP3 Tags
./mp3tag -e song.mp3

## Project Structure
MP3-Tag-Reader/
│
├── read_tags.c
├── edit_tags.c
├── file_operations.c
├── types.h
├── main.c
└── README.md

## Limitations
- Console-based application
- Limited support for extended ID3 features
- No audio playback support

## Future Enhancements
- Support for more ID3 versions
- Batch editing of MP3 files
- GUI-based interface
- Add backup before editing tags

## Learning Outcomes
- Understanding of MP3 file structure
- Practical experience with binary file manipulation
- Improved pointer and memory handling skills
- Exposure to multimedia file processing

## Author
Syed Shifan Ali
