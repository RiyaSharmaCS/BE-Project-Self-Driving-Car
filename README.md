# Self driving car for GSOC 2017

## File structure

```bash
+-- rasp-pi
|   +-- collect_data
|   |   +-- <data collections modules>
|   +-- +-- client.py
|   |
|   +-- preprocess
|   |   +-- data_preprocess.py, merge_and_prep.py
|   +-- +-- server.py
|   |
|   +-- selfdrive
|   |   +-- <self driving modules>
|   |   ...
```

## Collect data

  + Drive the car around the track and collect driving data
    Read README.md of: ./raspi-pi/collect_data


## Preprocess

  + Preprocess the train to be consumped by the model
    Read README.md of: ./server/preprocess


## Train

  + Train the model
    Read README.md of: ./selfdrive


## Test

### On Simulation

  + Test results of pre-trained model on simulation
    Read README.md of: ./selfdrive

### In Real-time

  + Test results of pre-trained model in real time
    Read README.md of: ./rasp-pi
    Read README.md of: ./server

