# 💻 SIC/XE Machine Simulator

## 👨‍💻 Author
[Geon Lee](https://github.com/)

## 🤔 What is **SIC/XE** Machhine?
* [SIC Machine](https://en.wikipedia.org/wiki/Simplified_Instructional_Computer)'s e**X**ension **E**dition
* you can read the article about [SIC/XE](https://en.wikipedia.org/wiki/SIC/XE) on wikipedia

## 💫 Function
* Control Section
* Addressing Mode (Flag bit)
	* Direct Addressing Mode
	* Indirect Addressing Mode
	* Simple Addressing Mode
	* Immediate Addressing Mode
	* Relative Addressing Mode
		* Program Counter (PC Register)
		* Base	(Base Register)
* Extended Instruction (4bit Instruction)
* External Symbol Reference & Define

## 👨‍🏫 Usage
```shell
$ make
$ ./${studentID}.out
sicsim>
```

## ⌨ Command
* h[elp]
* d[ir]
* q[uit]
* hi[story]
* du[mp] [start, end]
* e[dit] address, value
* f[ill] start, end, value
* reset
* opcode mnemonic
* opcodelist
* assemble filename
* type filename
* symbol