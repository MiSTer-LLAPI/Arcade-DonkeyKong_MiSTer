LLAPI Note : 

1. Place the rbf core file in a folder named _LLAPI/cores/
2. Place the MRAs files in _LLAPI/_Arcade/
3. Dont forget to enable LLAPI in the core OSD (this has to be done for each MRA for now)
4. Play !

In order to play with 2 players you need to insert 2 coins at least and press START2P button.
This button has been mapped to the LEFT shoulder button (SNES controller used as a reference)

---------------------------------------------------------------------------------
-- 
-- Arcade: Donkey Kong port to MiSTer by Sorgelig
-- 18 April 2018
-- 
---------------------------------------------------------------------------------
-- 
-- dkong Copyright (c) 2003 - 2004 Katsumi Degawa
-- T80   Copyright (c) 2001-2002 Daniel Wallner (jesus@opencores.org) All rights reserved
-- T48   Copyright (c) 2004, Arnim Laeuger (arniml@opencores.org) All rights reserved
-- 
---------------------------------------------------------------------------------
-- 
-- Support screen and controls rotation on HDMI output.
-- Only controls are rotated on VGA output.
-- 
-- 
-- Keyboard inputs :
--
--   F1          : Coin + Start 1P
--   F2          : Coin + Start 2P
--   UP,DOWN,LEFT,RIGHT arrows : Movements
--   SPACE       : Jump
--
-- Joystick support.
-- 
-- High score save/load - To save your scores use the 'Save Settings' option in the OSD.
-- * Warning: For Donkey Kong 3 (bootleg) Scores are only loaded when core starts, using reset will return scores to factory settings *
--
---------------------------------------------------------------------------------

                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the
correct ROMs.

To simplify the process .mra files are provided in the releases folder, that
specifies the required ROMs with checksums. The ROMs .zip filename refers to the
corresponding file of the M.A.M.E. project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for
information on how to setup and use the environment.

Quickreference for folders and file placement:

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip
