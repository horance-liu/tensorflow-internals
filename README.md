# TensorFlow Internals.

It is open source ebook about TensorFlow kernel and implementation mechanism, including programming model, computation graph, distributed training for machine learning.

## Downloads

You can obtain full latex source files of TensorFlow Internals from [https://gitlab.com/horance/tensorflow-internals](https://gitlab.com/horance/tensorflow-internals)

## Install Tex

You should install full texlive packages.

- Ubuntu     

```bash
$ sudo apt-get install texlive-full
```

- MacOS

Download [MacTeX.pkg](http://tug.org/mactex/), and install it.

- Windowns
      
Download [CTEX-full](http://www.ctex.org/CTeXDownload), and install it.

## Install Missing Fonts

Then you should install some missing chinese fonts. Please download missing fonts from Gitlab.

```
$ git clone https://gitlab.com/horance/fonts.git
```

Then install all missing fonts.

- Ubuntu

```bash
$ sudo cp fonts/* /usr/local/share/fonts
$ sudo fc-cache
```

- MacOS 
    
Import all missing fonts into fontbook, then cache all fonts.

```bash
$ sudo fc-cache
```

- Windows
 
Copy the all missing fonts into C:/WINDOWS/Fonts, then cache all fonts.

```bash
$ fc-cache
```

## Build

```bash
$ make
```

if you happen to Error begin with `?`, then press `R`(not `r`) and `Enter` to continue.

## Preview PDF

- Mac OSX

```bash
$ open output/tensorflow-internals.pdf
```

- Ubuntu

```bash
$ okular output/tensorflow-internals.pdf
```

if no okular installed, please install it.

```bash
$ sudo apt-get install okular
```

- Windows

open the file from directory `tensorflow-internals/output`.

## License

[MIT License](http://opensource.org/licenses/mit-license.html) 

