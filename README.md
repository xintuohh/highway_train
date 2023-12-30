# highway_train
Used for highway environment testing
First create a python virtual environment:

python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

To train from scratch:

python main.py
To test model:

python main.py --mode test --actor_model ppo_actor.pth
To train with existing actor/critic models:

python main.py --actor_model ppo_actor.pth --critic_model ppo_critic.pth
