# Dolphin-Spirit-Ocean-Mission-VR
VR Modf for Dolphin Spirit: Ocean Mission 

<img width="683" height="1024" alt="DolphinSpiritOcean Mission" src="https://github.com/user-attachments/assets/1cf37dce-fec5-4a39-9309-4c4f04ae1990" />


DOLPHIN VR  -  VR mod (Unity 2021.3, Mono x64, URP, BepInEx 5)
=============================================================
Version 0.1.5 (test build)

Install
-
unzip to game folder, only tested with virtual desktop XR

CONTROLS (the VR controllers are the game's GAMEPAD - its own pad controls and button prompts)
-
  Left stick ............ left stick (walk / swim) 
  
  Right stick ......... right stick (camera)
       swimming: up = RT (swim up), down = LT (swim down)
       first person: left / right turns you, up / down = d-pad up / down
       
  HOLD LEFT GRIP ........ the left stick is the D-PAD (up / down / left / right)
  
  X + Y together ........ Start (pause)
  
  HOLD RIGHT STICK CLICK  **switch FIRST / THIRD PERSON** (0.6 s)
  
  Left grip + X ......... third person: game camera / follow behind the diver
  
  Both stick clicks ..... re-centre the view
  
  Hold both stick clicks 1.2 s ... VR SETTINGS MENU (stick up/down choose, left/right change, A toggle, B close)
  
  Every button can be changed in the config ([Controls.Pad]). The game's rumble goes to your controllers.

VIEW
-
  * Third person (default): you are where the game camera is, your view turns with it (right stick).
  * First person: you are the diver's eyes (head hidden) and the DIVER'S HANDS FOLLOW YOUR CONTROLLERS.
      walking: the left stick walks where you LOOK, the right stick turns you.
      swimming: the same - the left stick swims where you LOOK, the right stick turns you.
  * The interaction prompts (talk / take / look ...) float by your RIGHT controller.
  * The d-pad HUD (codex / camera / map icons) sits on your LEFT controller, the whistle / dolphin / sonar button
    hints under it.
  * PHOTO CAMERA: when you use the camera, its picture (viewfinder + HUD) is a screen in your LEFT HAND. Hold it like a
    real camera: it looks from your eyes through the screen (or where the left controller points - AimMode) and moves
    with your hand; the right stick turns you. Take the photo with the game's button as usual.
    Size / position / reach in the VR settings menu ("Photo camera") or [PhotoCamera] in the config.
  * Menus, codex, map, photo previews, pause: the game's picture on a screen in front of you.
    In play the HUD floats in front of you (its black parts see-through).
  * Dialogues / cut-scenes: you see from the game camera.

Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
