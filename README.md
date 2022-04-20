# Predicting Loose-fitting Garment Deformations Using Bone-driven Motion Networks

This repository contains the data used for training the networks in Predicting Loose-fitting Garment Deformations Using Bone-driven Motion Networks.

In each of npz files, there are 3 keys:

- pose: [clip_length, 52, 3]  the rotation vector of joints
- trans: [clip_length, 3] the translation of body
- sim_res: [clip_length, vert_num, 3] the simulation result of each frame

The garment template is provided in `template.obj` in each folder.
