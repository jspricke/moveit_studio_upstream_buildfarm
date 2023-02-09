```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jspricke/moveit_studio_upstream_buildfarm/sid-debian/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_moveit_studio_upstream_buildfarm.list
echo "yaml https://raw.githubusercontent.com/jspricke/moveit_studio_upstream_buildfarm/sid-debian/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_moveit_studio_upstream_buildfarm.list
```
