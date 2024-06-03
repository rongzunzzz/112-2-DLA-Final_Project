# 112-2-DLA-Final_Project
This is the final project of "Deep Learning and its applications" course of NTU.

### Members
- 資管四 吳欣紘
- 資管四 鄭至鈞
- 資管四 黃戎僔
- 資管四 陳亮妤

### Main Tasks
We have built some deep learning models for trash/recycle classification. The practical usage of these models is to correctly classify the dumps in order to generate re-use values and turn garbage into gold with great speed, instead of human effort, which is the main challenge of trash classification in Taiwan.

#### Main models
- Pretrained ResNet50 model
- Pretrained VGG16 model
- Self-defined CNN model
- ResNet50 +  Self-Defined Fully-Connected Layer Model


## GitHub Link
https://github.com/rongzunzzz/112-2-DLA-Final_Project

## How to execute the code(MacOS)
### Colab(Suggested)
Remember to modify the correct data file path to get the data properly.
### Local
Create a virtual environment under the current directory.
```
python3 -m venv .venv
```

Activate the environment.
```
. .venv/bin/activate
```

Install required python packages.
```
pip install -r requirements.txt
```

Finally, select the activated python3 environment as the notebook kernel and run the code.
