# Editing HUD for Garry's mod

You would need to add this script to a .lua file in the Garry's Mod garrysmod/lua/autorun directory and restart the game to see the changes take effect. 

This script uses the hook.Add function to add a hook to the HUDPaint event, which is called whenever the game's HUD is being drawn. In the hook function, it uses the surface.SetDrawColor function to set the draw color to pink (RGB value 255, 192, 203) and the surface.DrawRect function to draw a rectangle that covers the entire screen, effectively painting over the game's HUD with the pink color.
