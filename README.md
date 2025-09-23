# HTAM--Zhou-yifan-2025
MY PERSONAL DOCUMENTATION OF THE COURSE [HOW THINGS ARE MADE] IN TONGJI

# 3D SCANNING EXPERIMENT(S)

## Preliminary experiment
In the HTAM class, we attempted to use Revo for scanning the cucumbers and the iPad's camera to do face scanning. The point cloud scanning by Revo was relatively fine, but some displacements occurred during the experiments in class; the iPad camera's scanning accuracy was not high and it was prone to deviation, but when used in the coarse model state, it had achieved a relatively satisfactory result.

![image during classes, scanning hulu](IMAGES/126a311a96a59399c0f872aab2f276f3.jpg)
image during classes, scanning hulu

![image during classes, Saverio doing face-scanning](IMAGES/126a311a96a59399c0f872aab2f276f3.jpg)
image during classes, Saverio doing face-scanning

## SOFTWARE & EQUIPMENTS USED
I went to the fablab and used the Revo scanner. The accompanying software was installed on my laptop. The object I scanned was this grey plush little shark. (I wasn't sure about the reflection on the plush surface, so I was quite worried that something might go wrong during the scanning process.)

![an image of the scanned object](IMAGES/b035562e8b9405cb295313f4e4cd3967.jpg)
an image of the scanned object

## SCANNING PROCESS
### DATE：2025-9-19
#### GOAL
·Using the handheld scanner from Revo to perform the scan. I prefer the level of detail achieved by the scanner, so I went to the fablab.

#### PROCESS
First, I attempted to use the manual turntable instead of the automatic one (actually because I didn't know how to connect the automatic turntable... ) However, the model has many flaws and misalignments.

[an image of USING THE MANUAL TURNTABLE](IMAGES/ddaf83b516bfc966c979b7b629c8d3d7.jpg)

Saverio told us that the white dots on the automatic turntable are used to position the scanner. Therefore, compared to handheld scanning and manual turntable scanning, using the automatic turntable will result in higher accuracy.
At first, I tried to complete the part that couldn't be scanned by simply holding up the shark and placing the bottom surface directly in front of the scanner. However, this would cause the scanner to lose its positioning.Then, we changed the position of the small shark and conducted a second scan - this was because in a single scan, certain parts might be missed due to the placement angle, although the turntable had rotated 360 degrees; multiple scans could complete the scanning of the entire object and obtain multiple different 3D models. By combining the two models from different angles, we finally obtained a scanning model with fewer flaws.

[the bottom of the shark](IMAGES/9aad80bf3a672a6837d286d40097dac6.jpg)

[scanning from another position](IMAGES/563e481ea521ca3c08088352972a0a72.jpg)

#### RESULT
After obtaining the individual model, I used the mesh construction feature in Revo to convert the point cloud into a mesh and then merged them. Thus, I obtained a rough shark scanning model - but due to the surface material, there were many bumpy and uneven marks on it, along with some small holes and unnecessary overlapping parts - I need to deal with these issues.

YOU CAN SEE SOME OVERLAPPING PARTS HERE [The imported model after being loaded into Blender](IMAGES/deebacf55a7307f4602cfab04bd9bc61.jpg)

---

## PROCESSING

### DATE：2025-9-20
#### GOALS
The original software had built-in functions such as "one-click processing", "hole filling", and "smoothing", and it could also simplify the mesh to reduce the number of model faces. However, I was still not satisfied with the result after such processing, so I hoped to further refine it using Blender.

#### REFINING PROCESS
First, I selected and deleted all the redundant parts. Then, I applied the "smooth" effect of the sculpting mode to the surface of the shark. At the same time, I removed the redundant labels and smoothed out the bottom of the shark to facilitate printing.

[A before-and-after comparison picture](b0b43d5148ead0c0b4ef4a2c2ba6dc6a.jpg)
