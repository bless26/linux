# linux

FILE-OPEN:

Syntax:

int open (const char* Path, int flags [, int mode ]);

Parameters

Path : path to file which you want to use

flags :

O_RDONLY: read only

O_WRONLY: write only

O_RDWR: read and write

O_CREAT: create file if it doesn’t exist

O_EXCL: prevent creation if it already exists

FILE-READ:

Syntax:

size_t read (int fd, void* buf, size_t cnt);

Parameters

fd: file descripter

buf: buffer to read data from

cnt: length of buffer

FILE-WRITE:

Syntax:

size_t write (int fd, void* buf, size_t cnt);

Parameters

fd: file descripter

buf: buffer to write data to

cnt: length of

FILE-CLOSE:

Syntax:

int close(int fd);

Parameter

fd :file descriptor
