# BoxAI Coach

**Real-Time AI Form & Technique Coach for Shadow Boxing and Calisthenics**

A smart, low-cost AI coaching system that works with only a laptop webcam. It provides instant, objective feedback on form and technique for 6 movements (3 boxing + 3 calisthenics) and saves full joint data for future self-learning.

**Course:** CSIS 4260 (Winter 2026)  
**Student:** Munshi Alimushwan (300383063)  
**Faculty:** Nikhil Bhardwaj

---

## Key Features

- Real-time pose estimation using **MediaPipe Pose** (33 landmarks)
- Intelligent Director: only gives commands when form is correct
- Movement-specific analysis:
  - **Boxing**: Guard height, distance, facing angle, arm extension
  - **Calisthenics**: Joint angles, depth, body alignment
- Dynamic coach-style instructions with realistic combos
- External JSON configuration system (easy to extend)
- Full session data saving (raw landmarks) for self-learning
- Detailed post-session analytics with graphs and scores

---

## Technologies Used

- Python 3
- MediaPipe Pose
- OpenCV
- NumPy + Pandas + Matplotlib
- External JSON configs for movements

