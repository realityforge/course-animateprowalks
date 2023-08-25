# Coursework for "Animate a Professional Looking Walk in Autodesk Maya"

This contains the project used in the course [Animate a Professional Looking Walk in Autodesk Maya](https://www.udemy.com/course/animateprowalks/).

# Rig

The rig is Breath Of The Wild version of Zelda (FanArt) from Christoph Schoch available [here](https://drive.google.com/drive/u/0/folders/12u-ZkOxzoO8DUzqfcoOFmFbgV-uJcB64)

# Red 9 Studio Pack Tools

The Red 9 Studio Pack Tools are used for mirroring poses in this project. You need to install the Python3 version of this project that is available from [markj3d/Red9_StudioPack_Python3](https://github.com/markj3d/Red9_StudioPack_Python3). A [YouTube Tutorial](https://www.youtube.com/watch?v=26GfTXKm_ZU) exists to guide you through this process.

However the basic process is to download the archive, extract to maya script directory, and rename the root directory to Red9 and then add the following snippet to your `userSetup.py`

```python
import Red9

Red9.start()
```

Then run the python script `vendor/Red9_Config/selection_script.py` and configure the mirrormap `model.mirrorMap`

# Tween Machine

The [TweenMachine](https://github.com/The-Maize/tweenMachine) plugin is also used in project to create breakdown poses.

To install download the [tweenMachine.py](https://github.com/The-Maize/tweenMachine/blob/master/python/tweenMachine.py) script and add it to a Maya script directory and add the following snippet to your `userSetup.py`

```python
import tweenMachine

tweenMachine.start()
```

# Results

https://github.com/realityforge/course-animateprowalks/assets/11840/a1218a23-e574-4459-aa5f-5fc4303d5d1b

