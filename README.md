# KittenPixel's Personal Portfolio

As this is my Personal Portfolio I will first explain how I got into programming when I was about 11 I got into programming and made my first roblox game, my friends loved it now that im 13 I can make more advanced stuff, and my most advanced game so far was a core game I went through self teaching stuff and it took 2 months to finish the core game. I have made the core game when I was younger and a remake is being worked on this is some of the code thats in the remake

 ```
game.ReplicatedStorage.Announcement:FireAllClients("Initalizing Reactor Startup.")
	game.Workspace.sounds.LightsOFF:Play()
	for i,v in pairs(script.Parent.Parent.Parent.Parent.Lights:GetChildren()) do
		if v.Name == "dwd" then
			v.PointLight.Enabled = false
		end
		if v.Name == "1" then
			if v:FindFirstChild("MeshPart") then
				for i,x in pairs(v:GetChildren()) do
					for i,z in pairs(x:GetChildren()) do
						z.PointLight.Enabled = false	
					end
				end
			else
				v.Part.SpotLight.Enabled = false
			end
			
		end
	end```

Its the core startup. Here is the old one so yall can see what it was https://www.roblox.com/games/8228365129/Astral-Science-Energy-Research-Space-Station I have also taken advantage over the years to learn more and I am willing to go through what ever training it takes to join new game projects, or show of my work in real time, if I forgot something what do I do go straight the the dev forms I like to see if someone posted on it first if they didn't do it myself because it makes me learn more by doing it my self.
