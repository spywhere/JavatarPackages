Javatar Packages default repository
===============

Javatar Packages repository for Javatar plugin for both Sublime and Atom

### Create your own Javatar Packages
 1. Clone or Download JavatarDoclet repository
 2. Compile all JavatarDoclet source code
 3. Modify `makefile` to suit your package
 4. Run `make` command with your source codes in current directory

*Make sure you already in Development Channel

### Add your own Javatar Packages to this repository
 1. Fork this repository
 2. Copy your Javatar Packages to `packages` folder
 3. Add your package informations into `javatar_packages.json` file
 4. Submit a pull request

 *Example of package informations*

```
{
	// A package name (should be exactly same as inside .javatar-packages file)
	"name": "Java Standard Edition 7",
	// Estimated file size of the package
	"filesize": "1.4MB",
	// A package file name (without extension)
	"filename": "JavaSE7",
	// Hash checksum (can be generated using Packages Manager... > Package Tools... > Generate SHA-256 Hash from URL)
	"hash": "82c6b0d184a45d3ee1e15e38237a366ff6242f3bfee224113b13c787316df9dd",
	// Conflict packages name (check if any package starts with these keywords)
	"conflict": ["Java Standard Edition"]
}
```
