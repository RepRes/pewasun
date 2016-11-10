## Reproducible Research in Networking.

Please fill in the following [form](https://docs.google.com/forms/d/1Zt5Wk94j6wBZRqU20gJKuqb8TN-V_Id2D7SnC3J_kFM/prefill), and create a strucutre as described below. You can either send us an archive of your contribution or give us a link to a repository that we can fork.

The architecture of each directory is/should be as follows:

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
> - INSTALLATION (should contain installation procedures, dependencies, ... anything requied to run the code. It can be linked to scripts subdirectory)
> - USAGE and EXAMPLE (can be linked to the usage and script subdirectories)
> - SRC (should be linked to the source code subdirectory)

The **scripts** directory should contain:
> - readme.md file which explains the content of the directory
> - for example, scripts to easily install and setup the __experimentations__
> - for example, scripts to download and install a virtual machine containing all the necessary tools or a docker image
> - scripts to post-process the results and to generate figures


The **usage** directory should contain:
> - readme.md file which explains the content of the directory
> - all the necessary scripts, compilation flags and directions to reproduce, with accuracy, the results described in the publication


## Side Notes

The code hosted in this repository is copyrighted by their respective authors. 

If you want to host your cade in this repository to promote Reproducible Research especially in Networking, please do not hesitate to drop us an email, open an issue or send us a pull request. 

If you have any suggestion or want to take part of this action related to Reproducible Research, do not hesitate to contact us. 

