
![alt text](assets/logo.png "Title")

A simple сommand-line http server for static websites 🤘

## Installation

```sh
npm install -g mamont
```

## Usage

Running `mamont` without any arguments will host the current directory as a static web site on any free port. Navigating to the server will render your `index.html`, if that file exists.

```
$ mamont
```

## Usage without installation

```
$ npx mamont
```

## Options

`-p` - Make the web server accessible from the port you specified.  
`-d` -	Starting with a specific document root directory.  
`-h` -	Show help.  
`-c` - Clone page by url(Create a directory with page hostname and download page named index.html).

Example:

```
$ mamont -p 3000 -c www.npmjs.com
```