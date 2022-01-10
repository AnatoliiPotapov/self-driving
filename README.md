# Self Driving experiments with Carla

For now you can run Carla in manual control mode.
To do this run:
```bash
bash carla/run_server.sh

cd carla/client
poetry shell
poetry install
python manual_control.py
```