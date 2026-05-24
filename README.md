
-- Script de Teste de Velocidade
local player = game.Players.LocalPlayer

if player and player.Character and player.Character:FindFirstChild("Humanoid") then
    -- Altera a velocidade padrão (que costuma ser 16) para 50
    player.Character.Humanoid.WalkSpeed = 50
    print("Script carregado com sucesso! Velocidade alterada para 50.")
else
    print("Erro: Personagem nao encontrado na memoria do jogo.")
end
