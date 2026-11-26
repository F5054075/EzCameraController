This is a very rudimentary camera controller with a group of events and functions that can be called to manipulate the camera.

These events and functions include:

Smooth moving the camera to a position:

(MUST DETATCH THE PLAYER CAMERA FIRST BEFORE MOVING IT)

<img width="218" height="154" alt="image" src="https://github.com/user-attachments/assets/39a23675-437d-4f9c-bcd9-c3967a260064" />

Takes in the inputs of the new position and how long it takes to get there.

----------------------------------------------------------------------------------------------------------------------------------------------------

Smooth Rotating the camera to a new rotation:

(MUST DETATCH THE PLAYER CAMERA FIRST BEFORE MOVING IT)

<img width="157" height="171" alt="image" src="https://github.com/user-attachments/assets/33723783-86ce-435f-a987-d8c2b397e203" />

Takes in the inputs of the rotation to rotate to and how long it takes.

----------------------------------------------------------------------------------------------------------------------------------------------------

Camera shake:

has events for all shake profiles.

<img width="192" height="150" alt="image" src="https://github.com/user-attachments/assets/370bae67-42b5-4aaf-9b02-dd0b203f732e" />

<img width="172" height="138" alt="image" src="https://github.com/user-attachments/assets/b68b3b09-066e-4b73-8ac8-9a4d372ec36e" />

<img width="134" height="138" alt="image" src="https://github.com/user-attachments/assets/20bba6da-9db4-4b57-9fe1-c848c7e8a974" />

<img width="152" height="106" alt="image" src="https://github.com/user-attachments/assets/d2481ba7-ef51-4b5f-8525-6f4b95b37b74" />

Takes in the inputs of the duration of the shake and the scale of the shake.

----------------------------------------------------------------------------------------------------------------------------------------------------

Rotate player spring arm:

<img width="150" height="100" alt="image" src="https://github.com/user-attachments/assets/5864116d-058c-472f-9440-46988d3a5edb" />

Takes in the input for the new rotation


----------------------------------------------------------------------------------------------------------------------------------------------------

Detach camera:

detaches player camera from its spring arm. 

<img width="198" height="105" alt="image" src="https://github.com/user-attachments/assets/b742e930-5881-4785-b690-6af871b47875" />

----------------------------------------------------------------------------------------------------------------------------------------------------

Attach camera to spring Arm:

reattaches the player camera to its spring arm.

<img width="179" height="60" alt="image" src="https://github.com/user-attachments/assets/bccc141b-f7d7-4b88-ba6f-ba19fd29a48c" />

----------------------------------------------------------------------------------------------------------------------------------------------------

Teleport camera to pos:

<img width="224" height="129" alt="image" src="https://github.com/user-attachments/assets/dd1b24bf-0906-4bed-90ee-2b855f3d8e25" />

Takes the input of the position to move the camera to.

----------------------------------------------------------------------------------------------------------------------------------------------------

Rotate camera:

<img width="180" height="141" alt="image" src="https://github.com/user-attachments/assets/6d592081-35f1-4f2f-b3a9-e398dbf29fcf" />

rotates the current camera to a new rotation.

----------------------------------------------------------------------------------------------------------------------------------------------------

Toggle constantly look at the player:

camera will now just follow the player.

<img width="225" height="74" alt="image" src="https://github.com/user-attachments/assets/397620c5-5979-49a4-8c7f-0f4573db6c51" />

----------------------------------------------------------------------------------------------------------------------------------------------------

Turntable camera:

will switch to a new camera then rotate around a point then changes to a new camera.

<img width="339" height="300" alt="image" src="https://github.com/user-attachments/assets/3138c179-c25a-45d4-aea8-3672d0932103" />

Takes inputs of turntable camera object which is an object included in the plugin, the amount of rotations the camera completes per second, how long 
to rotate for, weather to change back to the player camera , the camera to switch to if not and weather to disable the players inputs while it spins.

----------------------------------------------------------------------------------------------------------------------------------------------------

Change back to player character:

changes back to the player characters camera.

<img width="284" height="101" alt="image" src="https://github.com/user-attachments/assets/c6b994cb-27fe-4afb-91bc-b0f90a004079" />

----------------------------------------------------------------------------------------------------------------------------------------------------

Change to new camera:

changes the current camera.

<img width="211" height="120" alt="image" src="https://github.com/user-attachments/assets/a5caf092-13c0-4ef3-b4d2-cb971b1f5b6c" />

takes input of new camera component to change to.
