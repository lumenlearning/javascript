# Client Directory Formatting

*A mostly reasonable approach to the structure & conventions of the client directory*

## Table of Contents
	
	1. [Structure Overview](#structure-overview)
	1. [Actions](#actions)
	1. [Components](#components)
	1. [Stores](#stores)

## Structure Over

	```
	client:
		|
		L Directory: 'actions'
		| |
		|	L Directory: Ex: 'ActionName'
		|		|
		|		L File: 'index.js'
		|
		L Directory: 'components'
		| |
		| L Directory: Ex: 'ComponentName'
		|		|
		|		L Directory: 'css'
		|		|	|
		|		|	L File: 'style.js'
		|		|	
		|		L Directory: 'subcomponents'
		|		|		|
		|		|		L Directory: Ex: 'ComponentName'
		|		|				|
		|		|				L File: 'index.jsx'
		|		|
		|		L File: 'index.jsx'
		|
		L Directory: 'stores'
		| |
		| L Directory: Ex: 'StoreName'
		|   |
		|   L File: 'index.js'
	```

**[⬆ back to top](#table-of-contents)**

## Actions


**[⬆ back to top](#table-of-contents)**

## Components


**[⬆ back to top](#table-of-contents)**

## Stores


**[⬆ back to top](#table-of-contents)**