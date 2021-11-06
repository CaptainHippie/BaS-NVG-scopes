===========BOOMSTICKS AND SHARPSTICKS NVG scopes======
Adds three types of nightvision to three existing BaS scopes with toggle key
IMPORTANT : Current BaS already has a NVG scope function, which requires Beef's shader based NVGS.
This addon is ONLY for those who don't like Beef's NVGs or DX8/DX9 users who can't use it
Currently only supports 16:9 (you can still run this on other ratios but it'll look weird)

1. There are three NVG scopes in Bas, with three different NVG effects
	1PN93-4 Night Sight - cheap one
	1PN93-1 Night Sight - Mid end
	PN-23 Night Sight - the best one
2. You can toggle the NVG with a keybind currently set as the semicolon ";" (I was trying to avoid keybind 
	conflicts because there are a lot of them in anomaly)
	You can change the key in by editing the script, just change DIK_SEMICOLON in the line
		local switch = DIK_keys.DIK_SEMICOLON
		to something else by looking at the DIK keys table
3. And yes, this supports alternate aim sights
4. I also included fixed shaders for r1 to prevent crashing for DX8 users(I didnt do it, it was posted on discord,
	and idk why it wasn't included in the last BaS update)

Changelog:
update 2: Added NVG turning on/off sounds within BaS
update 1: Fixed a bug where it allowed other scopes to have the NVG effect

Credits:
xcvb, LVutner
SD and Maid for testing and advice
Night vision revision for the ppe files