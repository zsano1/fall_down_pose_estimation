# fall_down_pose_estimation
detect whether the old are falling down using openpose and modeling
This folder includes a method that can estimate whether the old(or anyone else) fall down at home. The main steps include using openpose net to detect the joint position of human. Then the position will be modeled to analyse the condition of the old.
requirment:
logging,sys,time,math,numpy,PIL,matplotlib,cv2,pylab,tensorflow
run:
cd /home/fall_down_pose_estimation
python run.py --model=cmu --resize=432x368   (optional)
result.txt
