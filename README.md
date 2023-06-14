# KittenPixel's Personal Portfolio

As this is my Personal Portfolio I will first explain how I got into programming when I was about 11 I got into programming and made my first roblox game, my friends loved it now that im 13 I can make more advanced stuff, and my most advanced game so far was a core game I went through self teaching stuff and it took 2 months to finish the core game. I have made the core game when I was younger and a remake is being worked on this is some of the code thats in the remake ```
local Sounds = game.Workspace:WaitForChild("sounds")
local Values = game.Workspace:WaitForChild("Values")
local Screen = game.Workspace:WaitForChild("Total")

local Reactor = game.Workspace:WaitForChild("Reactor"):WaitForChild("Components")

script.Parent.TextButton.MouseButton1Down:Connect(function()
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
	end
	script.Parent.Frame.Visible = false
	script.Parent.Parent.Frame2.Visible = true
	script.Parent.Parent.Frame2.Frame2.TextLabel.Text = "Core Initalizing!"
	Values.startup.Value = true
	Sounds.AStart:Play()
	wait(1.5)
	Sounds.corestartup:Play()
	Sounds.corestartup2:Play()
	wait(6.5)
	game.Workspace.sounds.AlarmAhh:Play()
	wait(6.5)
	Reactor.Beam.Beam.BeamHolders.Beam.Enabled=true
	Reactor.Beam.Beam.BeamHolders.MainBeam.Enabled=true
	Reactor.Beam.Beam.BeamHolders.Unstable.Enabled=true
	wait(5)
	game.ReplicatedStorage.Announcement:FireAllClients("Stablizer Beam instituted. Powerlasers coming online.")
	script.Parent.Frame.TextLabel.Text = "Powerlasers coming online."
	wait(6)
	Screen.TopPanel.Data.Stabilizers.A.Color = Color3.new(0.415686, 1, 0.34902)
	Screen.TopPanel.Data.Stabilizers.B.Color = Color3.new(0.415686, 1, 0.34902)
	Screen.TopPanel.Data.Stabilizers.C.Color = Color3.new(0.415686, 1, 0.34902)
	Screen.TopPanel.Data.Stabilizers.D.Color = Color3.new(0.415686, 1, 0.34902)
	Reactor.StabilizerA.Model.AssemblyA["7"].Beam.Enabled = true
	Reactor.StabilizerB.Model.AssemblyA["7"].Beam.Enabled = true
	Reactor.StabilizerC.Model.AssemblyA["7"].Beam.Enabled = true
	Reactor.StabilizerD.Model.AssemblyA["7"].Beam.Enabled = true
	Reactor.Core.Root.Centre.Create.Enabled = true
	Reactor.Core.Root.Centre.TrailElectricityBlur.Enabled = true
	Reactor.Core.Root.Centre.TrailElectricityBlur2.Enabled = true
	wait(2)
	wait(3)
	game.ReplicatedStorage.Announcement:FireAllClients("Core sync successful.")
	script.Parent.Parent.Frame2.Frame2.TextLabel.Text = "Core Online!"
	game.Workspace.sounds.LightsON:Play()
	for i,v in pairs(script.Parent.Parent.Parent.Parent.Lights:GetChildren()) do
		if v.Name == "dwd" then
			v.PointLight.Enabled = true
		end
		if v.Name == "1" then
			if v:FindFirstChild("MeshPart") then
				for i,x in pairs(v:GetChildren()) do
					for i,z in pairs(x:GetChildren()) do
						z.PointLight.Enabled = true	
					end
				end
			else
				v.Part.SpotLight.Enabled = true
			end

		end
	end
	wait(6)
	game.Workspace.sounds.corestartup2:Stop()
end)``` Its the core startup. Here is the old one so yall can see what it was https://www.roblox.com/games/8228365129/Astral-Science-Energy-Research-Space-Station I have also taken advantage over the years to learn more and I am willing to go through what ever training it takes to join new game projects, or show of my work in real time, if I forgot something what do I do go straight the the dev forms I like to see if someone posted on it first if they didn't do it myself because it makes me learn more by doing it my self.
