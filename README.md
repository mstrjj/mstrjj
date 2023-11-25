--Notificação-Som  
notificação local = Instance.new("Som")
notificação.Parent = game:GetService("SoundService")
notificação.SoundId = "rbxassetid://9086208751"
notificação.Volume = 10

game.StarterGui:SetCore("EnviarNotificação", {
      Ícone = "http://www.roblox.com/asset/?id=15464020601";
      Título = "Centro Domadic",
      Text = "ðŸ”ƒCarregando...ðŸ”ƒ";
})
espere (2)
game.StarterGui:SetCore("EnviarNotificação", {
      Ícone = "http://www.roblox.com/asset/?id=15464020601";
      Título = "Centro Domadic",
      Text = "âœ…Completoâœ…";
notificação:Reproduzir()
})
loadstring(Game:HttpGetAsync("https://raw.githubusercontent.com/Domadicoof/Domadicoof/6558457225552ee9794be3d6c2a0d4739babe4b6/Domadic%20Hub%20ScrObf.lua"))()
