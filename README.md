# Compile G09 Easy

Gaussian 09 is a general purpose computational chemistry software package. It has been widely used and can been learned eas
ily.

But it is difficult to compile G09 from source codes for reasons listed below:

* fortran compiler official recommended is pgf77, a paid software;
* shell scripts for compiling was writted by csh, a terrible shell with horrible and inconsistent syntax;
* most C programs used during the compilation of g09 was writted by ancient c language, hard read and likely to error if you compile them with modern C compiler.

The purpose of this project is to reproduce the implementation script and program with bash and modern c language.