Project 2 Documentation

This project is inspired by some chasing games that I played when I was young. I found that socket.io could achieve multiplayer games and send positions to the server. I want to design a game with different players, so I made this game.
The design decision of using p5.play is because this is a game, and it has different moving functions and objects to let me control. P5 play also provides me with animations. Mouse control is also easily inserted into objects. The server side is very basic, and if I have more time, I would love to research more about the client id to identify different players.
The most difficult part is how to control the fly between two players. The fly is controlled by mouse positions with randomness, but when I have two users both mouse positions should be equally influenced. So, I choose to use the server sending mouse positions, so that multiplayers' mouse position should control the fly. The play testing is also very hard for me, I only have one mouse, so I have to use different web pages to test, but I am not sure about the testing pieces, I hope I could find another way to test it. 
I realized that a game should have multiple layers of tests. Even though I had many self tests, I found that was not enough. Different platforms also influenced the result and design decisions. I also need to add the window resized function to make the game responsive. 
Here is the project link and the code. https://glitch.com/edit/#!/gelatinous-bronze-beryllium
https://github.com/doveliyuchen/Project_2


