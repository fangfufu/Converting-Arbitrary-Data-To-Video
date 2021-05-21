# Converting-Arbitrary-Data-To-Video
Two shell scripts for converting arbitrary files into video format. 

## Introduction
This set of shell scripts allows the user to convert an arbitary file into a video file, and vice versa. They were originally from [Matlab-Data-Video-Converter](https://github.com/fangfufu/Matlab-Data-Video-Converter), however I think it makes sense to create a new repository to encourage discussion. 

A certain organisation used to allow users to upload unlimited photo at high quality, they have decided to discontinue such service on 1 June 2021. Storing platform specific document on this organisation's document platform used to not count toward the quota. They have decided to make platform specific documents count toward the quota on 1 June 2021. This eliminated the loophole which [allowed unlimited storage](https://github.com/stewartmcgown/uds). 

## How to use
To convert from a file to a video:

    ./file2mp4.sh $FILENAME $VIDEONAME.mp4
    
To convert from a video to a file:

    ./mp42file.sh $VIDEONAME.mp4 $FILENAME
