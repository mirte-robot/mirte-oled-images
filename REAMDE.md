Continas two folders: animations, and images. Images should be png format with 128x64. Animations should have name: <name>/<name>_x.png where x is integer starting from 0.

Use: 
$ rosservice call /zoef/set_right_image "{type: 'image', value: 'zoef_logo'}"
$ rosservice call /zoef/set_right_image "{type: 'animation', value: 'eye'}"

Current images are created with https://www.pixilart.com/
