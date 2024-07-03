# IC-Gate

## How to RUN

This repo relies on the RecStudio library. Please follow the instructions below to install and run the code.
```bash
git clone https://github.com/XuHwang/IC-Gate.git
cd IC-Gate/
git submodule init
git submodule update --remote --branch multi-domain-multi-task
```


To run MMOE, the following steps are required:

1. Install the required packages:  
    ```bash
    conda env create -f RecStudio/environment.yml
    ```

2. Add recstudio to PYTHONPATH:
    ```bash
    PYTHONPATH=./RecStudio
    ```

3. Run
    ```bash
    python main.py -m MMoE -d kuairand --batch_size 1024 --eval_batch_size 512 --split_mode entry
    ```
