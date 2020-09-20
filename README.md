# Realtime driver drowsiness detection system
Project for realtime driver drowsiness detection. It used already trained CNN present in models/ directory to detect if both eyes are closed or not and based upon scoring criteria a threshold has been set if scores becomes higher than that then alarm starts playing.
It will show in realtime if eyes are open or closed, and score for each category as soon as score in closed category becomes gretaer than already set threshold it will start to play alarm.

# Requirements

Requirements of the project can be downloaded using requirements.txt file. Run pip3 install -r requirements.txt (Python 3)
 
# Usage

python3 driver_drowsiness.py 
