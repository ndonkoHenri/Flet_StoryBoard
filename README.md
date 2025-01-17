# Flet StoryBoard
Flet StoryBoard is a python library that have an easy to use tools for building graphical interfaces based on python `flet` library. Powerful interfaces with simple usability.
You can use these tools with only two main and simple functions!

## Goal 🏁
My goal is to allow programmers to focus on the back-end, and build the front-end using just a simple easy-to-use window without any front-end coding require.

## installation ⬇️
- Python > 3.7

For install:
> `pip install Flet-StoryBoard`

for Upgrade:
> `pip install Flet-StoryBoard --upgrade`

if there was anything wrong, and it's not upgrading properly, you should uninstall this package and reinstall it:
> `pip uninstall Flet_StoryBoard` To uninstall

## Little Peek

<img width="1500" alt="Screenshot 2023-04-26 at 12 17 33 PM" src="https://user-images.githubusercontent.com/86029286/234530619-004e0eca-d2b3-47ad-94fe-37ef5ae0fa68.png">

## What's new on `Flet_StoryBoard` `1.0` 🎉
- ReSupport custom widgets with flet.
- Multiple pages support.
- New Suggestions
- New way to load the StoryBoard on your app.
- The ability to add external `flet` controls inside the StoryBoard.
- New Feature called `Smart suggestions`. It gets your goal then suggest things based on it.
- Support templates. A template is a file contain pre-set props for all StoryBoard's widgets, like fonts and default text color. - soon -
- ReBuild the architecture of the library.
* Please read the docs to know more about library usage. [docs page](https://github.com/SKbarbon/Flet_StoryBoard/wiki)
* if there is any another issues not fixed yet, please create an issue here: [issues page](https://github.com/SKbarbon/Flet_StoryBoard/issues)


## usage & examples 🤝
There is a very simple docs here about library usage.
[docs page](https://github.com/SKbarbon/Flet_StoryBoard/wiki)

### create/edit your own StoryBoard
```cmd
python3 -m Flet_StoryBoard.edit myUI.fletsb
```
It will edit the existing one or create a new one if not.

### load a StoryBoard
To load your StoryBoard on your app, you can do this example code:

```python
from Flet_StoryBoard import LoadStoryBoard, StoryBoard

def main (storyBoard:StoryBoard):
    pass

LoadStoryBoard(target_function=main, storyboard_file_path="myUI.fletsb")
```

To know more about the `StoryBoard` class, follow the [docs page](https://github.com/SKbarbon/Flet_StoryBoard/wiki) .

## Coming Soon 🔜
- add custom non-built-in `flet` widgets. like `ColorPicker` and `AudioPlayer` widgets.
