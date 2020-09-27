# Fortran Hello World!

## How to download a Fortran compiler?
You can find the actual version of compiler on this [website](https://www.fortran.com/the-fortran-company-homepage/whats-new/g95-windows-download/).

## How to compile?
| Command                       | Description                                                                                  |
|-------------------------------|----------------------------------------------------------------------------------------------|
| g95 a.f95                     | Compiles a.f95 and links it to create an executable file a.out                               |
| g95 –c b.f95                  | Compiles a.f95 into an object file named a.o                                                 |
| g95 -c a.f95 b.f95 c.f95      | Compiles multiple source files. If all goes well, object files a.o, b.o, and c.o are created |
| g95 -o main a.f95 b.f95 с.f95 | Compiles multiple source files and links them together with an executable named ‘main’       |
## License
This project is licensed with MIT License.
