# woekaliprovider #

Simple kali-vm provider for Windows.

## Requirements ##
- Windows target
- Linux-like OS for deployment

## Role Variables ##

Available variables are:
- ``` kali_version ``` version or release
- ```
	vm_provider:
	  name: 
	  ext:
```   virtual machine provider: { vbox,ova } or { vm,7z }

## Dependencies ##

None.

## Example Playbook ##

```
- hosts: all
  roles:
	- kaliprovider
```

## License ##
MIT / BSD
