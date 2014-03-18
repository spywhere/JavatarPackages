Javatar Packages default repository
===============

Javatar Packages repository for Javatar plugin for both Sublime and Atom

### Create your own Javatar Packages
 1. Clone or Download JavatarDoclet repository
 2. Compile all JavatarDoclet source code
 3. Modify `makefile` to suit your package
 4. Run `make` command with your source codes in current directory

### Add your own Javatar Packages to this repository
 1. Fork this repository
 2. Copy your Javatar Packages to `packages` folder
 3. Add your package informations into `javatar_packages.json` file
 4. Submit a pull request
 
 *Example of package informations*
 
```
{
	// A package name (should be exactly same as inside Javatar Packages)
	"name": "Java SE7",
	// Details of the package (specify estimated file size is recommended)
	"details": "Java Standard Edition 7 packages (~1.4MB)",
	// A package file name (without extension)
	"file": "JavaSE7",
	// Hash checksum (can be generated using Development Section... > Generate SHA-256 Hash from URL)
	"hash": "e97b9b411575c73cf8561022ec007b6402ba86be365d4da825c01ce1fd9ad3e0"
}
```