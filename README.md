# AVT-Subject-Rating-Analysis

This repository includes the data for the paper mentioned below.

In `subjective_scores` you can find raw scores of conducted subjective quality assesment tests.
E.g. `subjective_scores/AVT-VQDB-UHD-1/test_1_per_user.csv` has the following structure:

```
video_name,user1,user2,user3,user4,user5,user6,user7,user8,user9,user10,user11,user12,user13,user14,user15,user16,user17,user18,user19,user20,user21,user22,user23,user24,user25,user26,user27,user28,user29
american_football_harmonic_200kbps_360p_59.94fps_h264.mp4,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1
american_football_harmonic_750kbps_360p_59.94fps_h264.mp4,2,4,3,2,2,2,4,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,3,1,2,1,2,1,3
...
```
`video_name` is the video filename of the stimulus in the test, and the columns `user{1...}` are the individual ratings of the participants.
All other included tests follow the same scheme.

In the folder `subject_rating_analysis` the results of the performed subject analysis can be found.
E.g. for `borer_et_al/AVT-VQDB-UHD-1/test_1_per_user_silvio_bias.csv`, the format is as follows:

```
q,r,scale
1.0700075588660802,1.0823290823253133,0.12489789689135404
0.45962271815332234,1.0678309794517085,0.09621309000574679
...
```
For the notation, we refer to the paper.


## Acknowledgments :book:
If you use this software in your research, please include a link to the repository and reference one of the following paper.


```bibtex
@inproceedings{rao2025subject,
  title={A Large-Scale Evaluation of Subject Rating Behaviour in Visual Quality Assessment Studies},
  author={Rakesh Rao Ramachandra Rao and Steve Göring and Stephan Fremerey and Dominik Keller and Alexander Raake},
  note={under review}
}
```