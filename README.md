# PS5-webcam-linux
Use the PS5 camera as a webcam on linux.
# Instructions
Make sure to clone with submodules, like so:

```git clone --recurse-submodules https://github.com/petergerasimov/PS5-webcam-linux.git ```

Install dependencies:

```sudo pip3 install --pre pyusb```
```sudo apt install v4l-utils```
```sudo pip3 install camset```

Then run:

```sudo python3 ps5eye_init.py```

Finally, open camset and set Exposure Auto to 0.
