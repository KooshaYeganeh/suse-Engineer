# suse-Engineer
Setting your SUSE Linux to Engineering Linux


## Info

**Set up your SUSE Linux workspace for your engineer's tasks with a single command and Scope**

The makers' choice for sysadmins, developers and desktop users.

[SUSE](https://www.opensuse.org/)

### Tools

- Mathematics
    - octave
    - jupyter-octave-kernel
    - octave-CSXCAD
    - pfstools-octave
    - python3-octave-kernel
    - octave-forge
    - OpenOctaveMidi
    - scilab
    - CSXCAD-matlab
    - jupyter-matlab-kernel
    - openEMS-matlab
    - python3-jupyter_imatlab_kernel
    - texlive-matlab-prettifier
    - texlive-matlab-prettifier-doc


- Finite Element Analysis
    - netgen
		
- Electronic
    - kicad
    - Fritzing
    
- CAD
    - Freecad
    - librecad


### Commands

**--config**

sudo-eng --config <area of expertise>

```
suse-eng --config electronic
```
or
```
sudo-eng --config CAD
```
**--info**

```
suse-eng --info electronic
```

```
suse-eng --info CAD
```

and more ...


## Install

```
cd /tmp && wget https://github.com/KooshaYeganeh/suse-Engineer/archive/refs/heads/main.zip && unzip main.zip && cd suse-Engineer-main && sudo mv suse-eng /usr/bin && echo "suse-eng Installed [ OK ]"
```

## Remove

```
sudo rm /usr/bin/suse-eng
```




