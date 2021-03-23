speed = 100 --16 is default

function onPlayerRespawned(character)
	wait(1) --loading delay
	local player = game.Players:GetPlayerFromCharacter(character)
	local human = character:findFirstChild("Humanoid")
	if player ~= nil and human ~= nil then
		human.WalkSpeed = speed
	end
end

game.Workspace.ChildAdded:connect(onPlayerRespawned)
