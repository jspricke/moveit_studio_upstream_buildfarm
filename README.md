# GitHub Actions based buildfarm for upstream dependencies of MoveIt Studio

Test

Stop building upstream dependencies from source for MoveIt Studio on Ubuntu 22.04.

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/tylerjw/moveit_studio_upstream_buildfarm/jammy-humble/ ./" \
            | sudo tee /etc/apt/sources.list.d/moveit-humble.list
```
