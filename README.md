local Player = game.Players.LocalPlayer
local PlaceIdD = game.PlaceId
local Ready = false

if PlaceIdD == 6284583030  then
	loadstring(game:HttpGet"https://www.scriptblox.com/raw/SAZA-HUB_496")()
	print("Bank (Z)")
	print("Collection (C)")
	print("Dark Matter(V)")
	print("Enchant (B)")
	print("Fuse (N)")
	print("Golden (M)")
	print("Merchant (L)")
	print("Rainbow (K)")
	print("Upgrades (J)")
	print("Mastery (P)")
	
	Player:GetMouse().KeyDown:Connect(function(Key)
		if Key == "z" and Ready == false then
			Player.PlayerGui.Bank.Enabled = true
		else
			if Key == "c" and Ready == false then
				Player.PlayerGui.Collection.Enabled = true
			else
				if Key == "v" and Ready == false then
					Player.PlayerGui.DarkMatter.Enabled = true
				else
					if Key == "b" and Ready == false then
						Player.PlayerGui.EnchantPets.Enabled = true
					else
						if Key == "n" and Ready == false then
							Player.PlayerGui.FusePets.Enabled = true
						else
							if Key == "m" and Ready == false then
								Player.PlayerGui.Golden.Enabled = true
							else
								if Key == "l" and Ready == false then
									Player.PlayerGui.Merchant.Enabled = true
								else
									if Key == "k" and Ready == false then
										Player.PlayerGui.Rainbow.Enabled = true
									else
										if Key == "j" and Ready == false then
											Player.PlayerGui.Upgrades.Enabled = true
										else
											if Key == "p" and Ready == false then
												Player.PlayerGui.Mastery.Enabled = true
											end
										end
									end
								end
							end
						end
					end
				end
			end
		end
	end)
else
	if PlaceIdD == 5024793931 then
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
	else
		if PlaceIdD == 4954752502 then
			while wait() do
				if game.Players.LocalPlayer.PlayerGui.StatusBar.TextLabel.Text == "0:10" then
					game.Players.LocalPlayer.Character:MoveTo(game.Workspace.GlobalLeaderboard.Position)
				end
			end
		end
	end
end
