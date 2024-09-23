# Pong DQN 

An implementation of a Deep Q-Network (DQN) agent that learns to play Atari Pong using reinforcement learning.

**Based on**: [OpenAIPong-DQN](https://github.com/bhctsntrk/OpenAIPong-DQN)

### Files

- **`Pong_DQN.ipynb`**: Jupyter Notebook containing the code for training, evaluating the agent, and visualizing the CNN outputs.
- **`requirements.txt`**: List of required Python packages.
- **`saved_models/`**:
  - **`pong-cnn-860.pkl`**: Trained model weights after 860 episodes.
- **`assets/video_recordings/`**:
  - **`rl-video-episode-846.mp4`**: Video of the agent achieving a high score.

### Usage

1. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Notebook**

   Open `Pong_DQN.ipynb` in Jupyter Notebook or JupyterLab and run the cells to train the agent, load the pre-trained model, or visualize the CNN outputs.

### Results

- The agent demonstrates high proficiency in playing Pong after training.
- A gameplay video is available in the `assets/video_recordings/` folder.
- The notebook includes an implementation for visualizing the CNN outputs, providing insights into what the agent has learned.
