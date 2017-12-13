# Python-HeadFirstSeries

**Python-HeadFirstSeries** contains my Python codes based on the examples from the book "**Head First Python**" by "**Paul Berry**"

## About

This repository contains some Python modules that can be downloaded from **Github** or from **PyPi** (Python Package Index)

### Prerequisites

You should have **Python 3** installed on your system in order to use these modules.
Download the latest version of Python 3 from here

```
https://www.python.org/
```

### Modules

List of my Python modules

* **pylist_nester** : A simple module to print nested lists with indentations.
	
	Available Versions : 

	[Latest]

	**v1.3.0 - pylist_nester**

		Update log for v1.3.0
			- Indentations can now be turned on and off as per user's choice

	[Older Versions]

	**v1.2.0 - pylist_nester**

		Update log for v1.2.0
			- Level is now a default argument with initial value 0
						 
	**v1.1.0 - pylist_nester**
						 
		 Update log for v1.1.0
			- Renamed to **pylist_nester**
			- Fixed import errors due to '-' in the module name
			- Added code to indent lists present at a deeper level (makes output look more appealing)

	**v1.0.0 - hf-nester**

			- A simple printer of nested lists

## Downloading and Installation

Install using **PIP** (PIP Installs Packages)
```
sudo pip install pylist_nester
```

To upgrade to a newer version
```
sudo pip install pylist_nester --upgrade
```
**OR**

Install **manually** after downloading zip or tar.gz

Change directory to the extracted zip or tar.gz folder
```
cd package_name/
```

Install the module in your copy of python
```
sudo python setup.py install
```

## GitHub Link to all versions of all modules
	
	Download from (https://github.com/Shashank9830/Python-HeadFirstSeries/releases)

### Test the module

Launch python shell
```
python
```

Try importing the newly installed module

For example :- pylist_nester

```
import pylist_nester
```

If you see the shell move to next line without error then you have successfully installed the module.

## Namespaces

While using a function from the module make sure to include the namespace, otherwise you'll get a *NameError*

For example :- *print_lol()* function in *pylist_nester* module

Incorrect way
```
print_lol()	#Direct use
```

Correct way
```
pylist_nester.print_lol()	#Using namespace
```

## Versioning

We use [SemVer](http://semver.org/) for versioning.
For the versions available, see the [tags on this repository](https://github.com/shashank9830/Python-HeadFirstSeries/tags). 

## Authors

* **Shashank Singh** - *Initial work* - [shashank9830](https://github.com/shashank9830)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details