# Voice Signal Classification

Using deep learning techniques to detect voice signals.

The training dataset contains audio files of the following sounds and noises:
1. Background Noises
2. Bed
3. Birds
4. Cat
5. Dog
6. Down
7. Eight
8. Five
9. Four
10. Go
11. Happy
12. House
13. Left
14. Marvin
15. Nine
16. No
17. Off
18. On
19. One
20. Right
21. Seve
22. Sheila
23. Six
24. Stop
25. Three
26. Tree
27. Two
28. Up
29. Wow
30. Yes
31. Zero

## PreProcessing Tasks:
1. Calculating power spectrum of the audio samples and plotting magnitude vs frequency graph of a random voice sample.
2. Calculating Short Time Fourier Transformation by computing DFT over short over lapping windows
3. Reconstructing the signal by re-sampling

## Neural Network Model

The models contains 1,611,498 trainable parameters. The models contains an input layer followed by a several Conv1D, MaxPool1D and Dropout layers.

Lastly, after a combination of all these layers, we Flatten the output and add a Dense layer in the end.

Overall, the model acheived a training accuracy of about 90% and validation accuracy of about 80.483%


