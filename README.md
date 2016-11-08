## Reproducible Research in Networking.

Please before sending us your code fill the following [forms](https://docs.google.com/forms/d/1Zt5Wk94j6wBZRqU20gJKuqb8TN-V_Id2D7SnC3J_kFM/prefill)

The architecture of each directory is/should be as follow:

```bash
repository_name
├── readme.md
├── scripts
    ├── readme.md
    ├── post_process_config.sh
    └── pre_process_config.sh    
├── src
    ├── readme.md
    ├── file1.c    
    └── file2.c
└── usage
    ├── readme.md
    ├── launch_exemple.sh 
    ├── output_exemple.jpg 
    └── output_exemple.dat    
```


The **readme.md** file  (preferably in markdown format) in the repository should contain the following details:
> - AUTHORS
> - LICENSE
> - SHORT NAME OF THE CODE (for easy reference)
> - TITLE OF THE PUBLICATION
> - SYNOPSIS (what is the code doing in one paragraph)
> - DESCRIPTION (detailled description of the code)
> - INSTALLATION (should contains installation procedures, dependencies, ... anything needed to run the code, can be linked to scripts sub directory)
> - USAGE and EXAMPLE (can be linke to the usage/script subdirectory)
> - SRC (should link to the source code subdirectory)

The **scripts** directory should contain:
> - readme.md file which will explain the content of the directory
> - This directory should contains some scripts for example to easily install and setup the __simulations__ and to easily process the results. 
> - It should provide for example a script to download and install a virtual machine containing all the necessary tools or to a docker image.
> - It should also provide a script to post process the results and to generate the figures.


The **usage** directory should contain:
> - readme.md file which will explain the content of the directory
> - This directory should contains all the necessary scripts, compilation flags and directions to reproduce exactly the results described in the publication. 


## Side Notes

The code hosted in this repository is copyrighted by their respective authors. 

If you want to host your cade in this repository to promote Reproducible Research especially in Networking, please do not hesitate to drop us an email, open an issue or send us a pull request. 

If you have any suggestion or want to be part of this action related to Reproducible Research do not hesitate to contact us. 

