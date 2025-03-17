# Open3d_log

For a GPU-enabled Ubuntu system, glxgears and xeyes can be successfully X11 forwarded to Macbook but failed with open3d.

<img width="565" alt="Screenshot 2025-03-17 at 22 32 10" src="https://github.com/user-attachments/assets/076f91fc-9323-4fbc-af2b-0e0b0f9f16da" />


change the export display to your mac display and run:

<img width="447" alt="Screenshot 2025-03-17 at 23 30 31" src="https://github.com/user-attachments/assets/bd4f38d5-de1f-4dfb-93f4-b537bd0ba2d7" />

```
MyMac ~ % glxinfo | grep "OpenGL version"
OpenGL version string: 2.1 INTEL-23.0.22
```
