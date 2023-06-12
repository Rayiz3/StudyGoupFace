# StudyGroupFace
small face image dataset of Studygroup

What I used for image dataset is character-face-image dataset that is extracted from Webtoon **'Studygroup'**.  
📖 https://www.webtoons.com/en/action/study-group/list?title_no=3595

Since there is no Webtoon image dataset provided with one series, I crawled from the desired Webtoon series and made face-image dataset by running opencv face estimation model.

For charactor face recognition, **lbpcascade_animeface** was used as the pretrained model.

You can freely access with opensource repository 📔 https://github.com/nagadomi/lbpcascade_animeface  

The estimation is targeted on the 200 episodes of the series, and 2,500 meaningful images are finally obtained.
Following those process, character-face-image dataset **StudyGroup** is made with size of 2,500 images.

The size of dataset is not large enough since the number of episodes revealed is not many to extract large amount of face data.
