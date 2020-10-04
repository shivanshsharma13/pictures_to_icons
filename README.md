# Picture to Icons 

![main](./Images/main.png)

This repository is for assigning the normal image file into an icon that means .ico file. We will perform this task with python!

## Clone the project 🌀

```
git clone https://github.com/shivkaansh/pictures_to_icons.git
pip install -r requirements.txt
python main.py
drag and drop the image
Get your icon file!
```
### Error

If you come accros this error or any OS error-

`FileNotFoundError: [WinError 3] The system cannot find the path specified: 'e\\automation\\pictures_to_icons\\Images\\'`

`OSError: [WinError 123] The filename, directory name, or volume label syntax is incorrect: "& 'e:\\automation\\pictures_to_icons\\Images\\"`

I would recommend you to remove `:` from the draged file of image like-

from -  ` >> e:\automation\pictures_to_icons\Images\sublime.png `

to - `>> e\automation\pictures_to_icons\Images\sublime.png`

**NOTE** - PLease make sure that you will not be able to make all images an icon. Images like in images folder will be required!


## Contribute 👨‍💻

- If you find any error or bug, please post an issue and by chance you have a solution we are always open to pull requests. Please make sure to post issue before pull requests.

- Also if you have any update regarding the project, You are most welcome to the contribution !!