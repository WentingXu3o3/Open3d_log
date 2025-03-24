# Open3d_log

For a GPU-enabled Ubuntu system, glxgears and xeyes can be successfully X11 forwarded to Macbook but failed with open3d.

<img width="565" alt="Screenshot 2025-03-17 at 22 32 10" src="https://github.com/user-attachments/assets/076f91fc-9323-4fbc-af2b-0e0b0f9f16da" />


change the export display to your mac display and run:

<img width="447" alt="Screenshot 2025-03-17 at 23 30 31" src="https://github.com/user-attachments/assets/bd4f38d5-de1f-4dfb-93f4-b537bd0ba2d7" />

```
MyMac ~ % glxinfo | grep "OpenGL version"
OpenGL version string: 2.1 INTEL-23.0.22
```



Also, I tried with GNOME for virtual display of Ubuntu Server
Make sure "XEYES" and "glxgears" can work first with the right display port.
![Screenshot 2025-03-24 at 16 08 35](https://github.com/user-attachments/assets/135fdedf-33ba-4067-ba58-738a4fb19215)

![Screenshot 2025-03-24 at 16 07 24](https://github.com/user-attachments/assets/e5c718ff-db0f-4ded-b27c-1a4ff7511728)
