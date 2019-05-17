* Application-Logic-View architecture
    * Application: The closest to metal layer
        * Handles Devices, OS communications, game loop, shutdown and runtime
    * Logic: The logic that makes a game a game
        * Handles Game state, physics, events, commands
    * View: User interactions
        * 3D scene, audio, input captures
    * All 3 divisions require a process manager each indeed to handle continuous changes with asynchronousness
    
* Multiplayer games and how they can be made though AI agents that are presented a game view similar to human players
    * May need exta stimulus interpreters for the AI to actually reach to a decision after getting all the stimuli

* Remote game view and remote game logic
    * Authoritative server and remote game logic that work similarly
    * Remote logic differs slowly in terms that it needs to account for predicting the response from the authoritative server and account for correction if the predictions came out to be slightly off.

* Direct3D VS OpenGL
    * Design philosophy of DirectX - If it can be done on hardware, do it on hardware, if not then do it on software

* DirectSound, FMod, WWise, RAD Tools (radgametools.com), Miles (most favourable for sounds)

* DirectInput or ...
    * Works with the same code for even the weirdest devices
    
Much more will be covered later
