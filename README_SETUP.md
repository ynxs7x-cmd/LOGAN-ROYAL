# Montagem da cena no Unity

1. Crie um chão: `GameObject > 3D Object > Plane`, escala `(10, 1, 10)`.
2. Crie o personagem: `GameObject > 3D Object > Capsule`, renomeie para `Player`.
3. Adicione `CharacterController` ao Player se ainda não estiver presente.
4. Adicione `ThirdPersonPlayerController` ao Player.
5. Crie uma câmera, marque-a como `MainCamera` e adicione `ThirdPersonCamera`.
6. Arraste o Player ao campo `Target` da câmera.
7. Arraste a Transform da câmera ao campo `Camera Transform` do controlador do Player.
8. Crie um objeto vazio `GameManager` e adicione `BattleRoyalePrototypeManager`.
9. Crie algumas caixas usando Cubes para formar cobertura e obstáculos.

O script de câmera atual é uma base simples. Controles de toque, mira, disparo, inventário, animações, rede e sistema de partidas ainda não estão implementados.
