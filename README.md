```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jspricke/moveit_studio_upstream_buildfarm/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_moveit_studio_upstream_buildfarm.list
echo "yaml https://raw.githubusercontent.com/jspricke/moveit_studio_upstream_buildfarm/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_moveit_studio_upstream_buildfarm.list
```
