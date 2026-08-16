# Droid Rerun

Little experiments with droid, rerun and data augmentation.  
Main idea, draw on the frames trajectory and point of the next gripper interaction.  
This is very cheap and easy operation for already collected data.  
Can be used for training VLMs (System 1) to predict which object to interact with.  
Can also be used for training VLAs (System 2) to follow grounded information.  

# Running

```
uv sync 
``` 

Run `src/experiments.ipynb`. Why notebook? I was experimenting :)  
After you downloaded and processed data you can also visualize it with rerun or host it with rerun server.

```

```