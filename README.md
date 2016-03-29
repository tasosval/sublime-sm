# Sample Manager package for Sublime Text 3

Provides syntax highlighting for the VGL language (`.rpf` files) and the structure.txt file of Sample Manager, a LIMS (Laboratory Information Management System) from Thermo Scientific

## Installation

**Using Sublime Package Control** (recommended): If you have installed [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install the Sample Manager Language package via the `Package Control: Install Package` menu item (shortcut: **CTRL+SHIFT+P**). Search for `Sample Manager` in the list.

**Without Git:** Download the latest source zip from [github](https://github.com/tasosval/sublime-sm/archive/master.zip) and extract the files to your Sublime Text "Packages" directory, into a new directory named *sublime-sm*.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/tasosval/sublime-sm.git sublime-sm

You can access the "Packages" directory through the menu in `Preferences` > `Browse Packages...`

## Features

### VGL language scripts

.rpf file highlighting works for about 80% of the reserved keywords have been implemented, which should represent about 95% of the code you will come up with. More to come.


#### Snippets
| Snippet | Description
|-------------|-----------------|
| global      | get a global variable |
| if          | basic if statement block |
| ifelse      | if..else block |
| increment | increment identity column |
| pop | pop a snap shot from the stack |
| push | Push a snap shot of the current table_name onto the stack |
| repeat | repeat..until block |
| routine | routine definition |
| strip | strip whitespace from string |
| while | while..do block |

### Structure.txt files

structure.txt file highlighting works for the specific DSL. Inline SQL queries specific to databases should have some basic highlighting but don't expect a full SQL query package
