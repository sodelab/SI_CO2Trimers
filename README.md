# SI

Jesus Ruiz, Kyle Misa, Arabi Seshappan, Murat Keceli, and Olaseni 
Sode, 'Exploring the anharmonic vibrational structure of CO2 trimers' 
Supporting Information

--------------------------------------------------------------------------------

Directory structure

```
project
│   README.md
│
└───barrel
│   └───coord
│   │       NC_TRANS
│   │       barrel.xyz
│   │       barrel.zmat
│   │
│   └───vci
│       │   vci-1.txt
│       │   vci-2.txt
│       │   vci-3.txt
│       │   vci-4.txt
│       │   vci-5.txt
│       │
│       └───max1
│       └───max2
│       └───max3
│       └───max4
│       └───max5
│
└───cyclic
    └───coord
    │       NC_TRANS
    │       cyclic.xyz
    │       cyclic.zmat
    │
    └───vci
        │   vci-1.txt
        │   vci-2.txt
        │   vci-3.txt
        │   vci-4.txt
        │   vci-5.txt
        │
        └───max1
        └───max2
        └───max3
        └───max4
        └───max5
```

--------------------------------------------------------------------------------

coordinate transformation file required for the NITROGEN vibrational
structure routines; a linear transformation coefficients are included in 
the file in space delimited lines for each row of [T t], according to the 
following equation,

\vec{q}' = {\bf T} \vec{q} + \vec{t}.

NC_TRANS

--------------------------------------------------------------------------------

cartesian coordinates of the trimer structures 

*.xyz

--------------------------------------------------------------------------------

z-matrix coordinates of the trimer structures

*.zmat

--------------------------------------------------------------------------------

list of VCI energy levels at different approximations according to the
VCI-(k) method

vci-?.txt

--------------------------------------------------------------------------------

list of VCI coefficients, in paratheses, for each VCI energy level with 
respect to the VSCF wavefunctions

VCI_MODES*.dat

--------------------------------------------------------------------------------
