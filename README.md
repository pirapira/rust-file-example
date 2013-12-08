A simple practice.  How to write to and read from files in rust.

The filename is constant "./test.dat".

# 1. The program takes two integer arguments (from the command line?) not yet

1. When the file is not present, it creates the file and try to read.
1. And it writes some constant integers to the file.

Usage
-----

    % rustc file_writer.rs
    % ./file_writer
    % rustc file_reader.rs
    % ./file_reader
    90
    22
    %
