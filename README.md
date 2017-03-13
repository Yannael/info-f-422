## INFO-F-422

This page contains the material for the hands-on classes of ULB [INFO-F-422](http://uv.ulb.ac.be/course/view.php?id=59893).

## Getting ready with R notebooks

The use of the notebooks requires to install:

* Jupyter Notebooks, see installation instructions [here](http://jupyter.org/install.html). The simplest way is to rely on Anaconda. The `jupyter` program is in the `bin`folder of anaconda. Add the folder to your PATH. 
* The IRkernel, see installation instructions [here](https://github.com/IRkernel/IRkernel). NB: You may need to restart R after Jupyter installation in order to be able to install IRkernel. 

Once installed, clone this repository and start jupyter notebook:

```
git clone https://github.com/Yannael/info-f-422
cd info-f-422
jupyter notebook
```

## Troubleshooting

* Windows: If you have the error 'Failed to create Anaconda menus", try installing from the latest zip archive at [https://repo.continuum.io/archive/.winzip](https://repo.continuum.io/archive/.winzip).

* In case of dead kernel, look at the error message in your terminal and see if you have packages missing. Make sure to upgrade to the latest R version. 



