# IC-Gate


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
