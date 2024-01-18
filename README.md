# LSF example code
This is the exmaple code which runs the minimap2 alignment using our docker images which is run by singularity on NGS cluster. 
User would need basic docker knowledge to read the code

# How to use

  All modification should be made to `main.lsf`

1. Define the directory containing your data, don't put "/" at the end
  e.g. `input_dir="/data/home/grp-sunhao/zx/example/np.human.fastq"`

2. Update the LSF parameters on top of the files, read the comment in detail

3. Submit the job on head nodes using `bash run.sh`

4. You should see the some "paf","err", "out" files in the your current working directory.
