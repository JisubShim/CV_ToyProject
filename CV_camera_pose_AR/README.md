# CV_camera_pose_AR
내 카메라(CV_video_recorder)를 캘리브레이션한 결과를 이용해 카메라의 자세를 알아내고, 영상에 간단한 AR 물체(직사각형)를 표시하기

#### Camera pose estimation
- 카메라의 자세 획득  

CV_calibration_&_distortion_correction으로 camera calibration 결과 얻기  

![스크린샷 2024-04-13 015341](https://github.com/JisubShim/CV_Practice/assets/118372554/ee172573-82b7-48d6-96d3-37bb46123a94)  
<br>
- 결과를 코드에 적용  

![스크린샷 2024-04-13 020928](https://github.com/JisubShim/CV_Practice/assets/118372554/1c856f3e-e2c7-4d7c-9ce7-72a504f57182)  

#### AR object visualization
- AR 물체 표시  

체스보드 가운데 파란색 직사각형을 출력  

![스크린샷 2024-04-13 015614](https://github.com/JisubShim/CV_Practice/assets/118372554/8ae4ec8c-0d38-44b7-bd32-c585abcd9bf0)  

