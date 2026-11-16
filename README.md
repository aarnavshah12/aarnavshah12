<a href="https://aarnavshah.vercel.app"><img src="./profile-header.svg" alt="Aarnav Shah — computer vision, robots, and things I wanted to exist." width="100%" /></a>

<p align="center">
  <a href="https://aarnavshah.vercel.app"><b>Website ↗</b></a> &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/aarnav-shah-a120042b1/">LinkedIn</a> &nbsp; · &nbsp;
  <a href="https://www.youtube.com/watch?v=1jhJQZQAS4U">Watch a build</a>
</p>

I'm Aarnav, a computer engineering student at **Waterloo**. I build things that use cameras to understand the world, then do something with what they see. Sometimes that's a basketball coach. Sometimes it's a robot arm that plays Connect 4 and talks trash.

I've worked on vision models and auto-labeling at **Roboflow**, ML research for redox flow batteries at **Waterloo's van der Heijden Lab**, and real-time voice agents at **Ally Solutions**. These days, I'm also working on humanoid manipulation and autonomous navigation with **WATonomous**.

### A few things I've built

<table>
<tr>
<td width="50%">
<a href="https://github.com/aarnavshah12/connect4-robot"><img src="https://raw.githubusercontent.com/aarnavshah12/connect4-robot/main/docs/images/connect4-robot.webp" alt="My Connect 4 robot arm and physical board" width="100%" /></a>
</td>
<td width="50%">
<h3>A robot with a competitive streak</h3>
<p>It watches the board, picks a move, drops a chip, and talks trash. The original build uses minimax; the <a href="https://github.com/aarnavshah12/connect4-robot/tree/pytorch-self-play">PyTorch branch</a> adds a learned board reader and a policy trained through self-play, with PPO and neural MCTS.</p>
<p><a href="https://github.com/aarnavshah12/connect4-robot"><b>Code ↗</b></a> · <a href="https://www.youtube.com/watch?v=1jhJQZQAS4U">Watch it play</a> · <a href="https://roboflow.com/blog/building-a-physical-ai-that-plays-connect-4">Build notes</a></p>
</td>
</tr>
</table>

| Project | The idea |
| :--- | :--- |
| **[Shot Tracker](https://github.com/aarnavshah12/shot-tracker)** | Turn a phone recording of a basketball session into makes, misses, shot arcs, and release mechanics. RF-DETR + pose estimation, processed locally. |
| **[Package Track](https://github.com/aarnavshah12/Package-Track)** | Give an old iPhone a job: spot deliveries and open an ESP32 porch lockbox after cloud verification. Includes a live dashboard and photo notifications. |
| **[Tabula](https://github.com/aarnavshah12/Tabula)** · team project | Go from a breadboard photo to a KiCad schematic and routed PCB, using OpenCV, component detection, and Gemini-assisted netlists. |
| **[Gesture Chess](https://github.com/aarnavshah12/Gesture-Chess)** | Play chess by pointing and pinching in front of a webcam. Python, OpenCV, MediaPipe, Pygame, and a minimax opponent. |
| **[AutoDoc](https://github.com/aarnavshah12/AutoDoc)** · team project | A VS Code extension for generating code comments and documentation without leaving the editor. |

### What I work with

| | Tools & methods |
| :--- | :--- |
| **Languages** | Python · C++ · JavaScript · SQL · Swift |
| **ML & vision** | PyTorch · scikit-learn · RF-DETR · OpenCV · Roboflow · Core ML · MediaPipe |
| **Learning & evaluation** | Vision-language models · PPO · neural MCTS · Optuna · SHAP |
| **Robotics & hardware** | ROS 2 · NVIDIA Isaac Sim · Gazebo · ESP32 · Raspberry Pi · UDP · SPI |
| **Apps & tooling** | FastAPI · React · Node.js · WebSockets · Git · Docker · Slurm · KiCad |

### Research & writing

I co-authored **[A Machine Learning-Driven Modelling Framework for Predicting Redox Flow Battery Performance](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7193854)** (2026 preprint), using neural-network surrogates to predict battery performance from simulation data.

I've also published **50+ computer vision guides and demos** through my work with Roboflow. I like writing up the build process: the model, the wiring, and what happened when I tried it. You can find the projects, articles, and more about me on **[my website](https://aarnavshah.vercel.app)**.
