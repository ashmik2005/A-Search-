# A-Search- 
/*
 * State Space:- An 8X8 matrix with any arrangement of n<=8 queens
 * Initial State:- No queens on the board(i.e., all entries are null)
 * 				0 0 0 0 0 0 0 0
 *				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * 				0 0 0 0 0 0 0 0
 * Transition Operator:- Add a new queen in an empty row
 * Goal state:- 8 Queens placed on the board such that all queens are in non-attacking position
 * For example,
 * 				0 0 Q 0 0 0 0 0
 * 				0 0 0 0 0 0 Q 0
 * 				0 0 0 0 0 0 0 Q
 * 				Q 0 0 0 0 0 0 0
 * 				0 0 0 Q 0 0 0 0
 * 				0 0 0 0 0 0 Q 0
 * 				0 0 0 0 Q 0 0 0
 * 				0 Q 0 0 0 0 0 0
 * Heuristic:- Number of queens that attack each other
 *
 * Submitted by:- Ashmik Harinkhede
 * Roll no:- 1801068
 * Btech 2nd Year CSE
 */
/* 

In A* algorithm at every step we choose the next state which has the lowest cost . The solution obtained by A* Search Algorithm is always optimal 

*/
