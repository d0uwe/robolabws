# Intentions
The workstation can be used for any computationally intense project or homework assignment but is mainly designed to be a rapid prototyping machine. This means that you can easily develop your software after which you offload it to some cloud provider. You can get a user account without sudo rights on this machine 

To get a user account you can send an application to the following email address: `douwe@dutchnaoteam.nl` and make sure it includes the following information:

* Your full name and those of your partners (if applicable) 
* Education (AI, CS, etc..)
* Education level (Bachelor/Master)
* Honours Project (Yes/No)
* Project Description 
    * Abstract
    * Timeframe (when you expect to start and finish)
    * Required resources
    * Required software
    
When you need access to the robolab, contact A.Visser@uva.nl with the following information:
* studentnummer
* passnummer


# Hardware Specifications
* Cpu: Intel E5-2640 v4 (10 cores/20 threads)
* Memory: 64 GB DDR4 
* GPU: NVidia 1080 Ti (12 GB)

# Software
* NVidia driver 384
* cuda-9.0 (with cudnn 7.0.3)

To add precompiled software (for instance cuda) to your own environment add the following lines to your `~/.bashrc` file:

For libraries:
```
export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:/usr/local/cuda-9.0/lib64
```

For executables:
```
export PATH=${PATH}:/usr/local/cuda/bin
```

