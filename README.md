# Palletron system repository

* Properly create your ROS2 workspace.

* Download this repository in the `src` folder.

* Inside the `palletron_system` folder, use the `gitman` to download all the repositories at once.
```bash
gitman install
```

* Run `rosdep` to install the dependencies.
```bash
rosdep install -i --from-path src --rosdistro humble -y
```

* Build it!
```bash
colcon build
```