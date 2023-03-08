# Sheep-and-Aliens

This is a VR project created as a part of a homework assignment for a course. The objective of the project is to create a magnifying lens and implement a two-handed grabbing system in VR. 

## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Features

Part 1: Magnifying Lens

The project is based on the tutorial for creating a magnifying lens, which has been adapted for VR. Instead of animation, the object is made grabbable and attached to the hand. A trigger collider is used to detect if the object is near a hand. The field of view (FOV) of the VR camera cannot be changed, so the "zoom" effect is achieved using render textures.

A rendering layer is used to make an object visible only through the magnifying lens. The project includes one such hidden object, which is marked clearly to indicate its location.

The image on the lens is relative to the viewing angle rather than the orientation of the lens itself. The camera does not rotate with the lens, and instead, the user can see straight through it.
