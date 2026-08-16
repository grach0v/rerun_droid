# Droid Rerun

Little experiments with droid, rerun and data augmentation.  
Main idea, draw on the frames trajectory and point of the next gripper interaction.  
This is very cheap and easy operation for already collected data.  
Can be used for training VLMs (System 1) to predict which object to interact with.  
Can also be used for training VLAs (System 2) to follow grounded information.  

## Example

<video src="https://raw.githubusercontent.com/grach0v/rerun_droid/main/media/example.mp4" controls muted loop playsinline width="100%"></video>

(if the player does not show up, open [media/example.mp4](media/example.mp4))

# Running

```
uv sync 
``` 

Run `src/experiments.ipynb`. Why notebook? I was experimenting :)  
After you downloaded and processed data you can also visualize it with rerun or host it with rerun server.

Open all processed recordings in the desktop viewer:

```bash
uv run rerun dataset/rrd/*.rrd
```

Open a single episode:

```bash
uv run rerun dataset/rrd/episode-000000-*.rrd
```
