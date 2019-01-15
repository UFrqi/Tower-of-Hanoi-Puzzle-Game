# Tower-of-Hanoi-Puzzle-Game
Variation of the classic 3 peg Tower of Hanoi Puzzle, consisting of 4 pegs (stools), and an adjustable amount of rings(cheeses). Also implements a recursive algorithm to solve the puzzle in an optimal number of steps, for any number of rings.

Can be played in the console (shell) using console_controller, or can use gui_controller to play using the gui.

Here it is in the Console controller:
![console_game](https://user-images.githubusercontent.com/40809349/43600007-6eae7284-9657-11e8-968f-1f9876d1305d.PNG)

Here is the game in the gui_controller:
The start
![gui_start](https://user-images.githubusercontent.com/40809349/43599987-5766b992-9657-11e8-8291-9ea037287ab1.PNG)
The ending
![gui_end](https://user-images.githubusercontent.com/40809349/43599906-0860e944-9657-11e8-98e9-3d757c2e31d6.PNG)


If you wish to change the number of cheeses or the number of stools in the game, under "if __name__ == "__main__":"
Change the parameters in the following code “gui = GUIController(6, 4, 1024, 320, 20)”  in gui_controller.py. The first parameter alters the number of rings (cheeses), the second alters the number of pegs (stools). The remaining three parameters visually alter the gui, modifying the height, width, and thickness of the rings respectively.  

The tour class uses a recursive algorithm to solve the puzzle with any number of cheeses on 4 stools in the fewest number of steps.

Here is the tour class solving the puzzle:
![tour_start](https://user-images.githubusercontent.com/40809349/43600070-98012a8c-9657-11e8-98a3-facda5f32236.PNG)

![tour_end](https://user-images.githubusercontent.com/40809349/43600035-7cfaa39e-9657-11e8-8849-615e1fdeadac.PNG)


