---
{"dg-publish":true,"permalink":"/tools/google-mediapipe/","tags":["computer-vision"],"noteIcon":"2","updated":"2024-06-05T17:08:14.513+05:30"}
---


## [Google Mediapipe](https://ai.google.dev/edge/mediapipe/solutions/)

---

## Face Detection

I am not very impressed…the library was not able to detect all the faces. This is a sample output…

As is clearly visible only about (4/10) faces are detected.

![Pasted image 20240605162707.png](/img/user/%F0%9F%93%81%20Assets/Pasted%20image%2020240605162707.png)

**Although** tweaking the parameters in the options seems to produce better results : 

![Pasted image 20240605165609.png](/img/user/%F0%9F%93%81%20Assets/Pasted%20image%2020240605165609.png)

Lowering the `min_detection_confidence to 0.2` resulted in a better output : 

![Pasted image 20240605165552.png](/img/user/%F0%9F%93%81%20Assets/Pasted%20image%2020240605165552.png)

*Still not all faces are detected (8/10).*
