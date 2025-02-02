- __Convert from the [e-prime fMRI version](http://people.qc.cuny.edu/Faculty/Jin.Fan/Pages/Downloads.aspx) ([Fan et al., 2005](https://www.sciencedirect.com/science/article/abs/pii/S1053811905000984?via%3Dihub)).__
Changes including:

	* simplify the instruction
	- in original e-prime version:
	- "Welcome to Attention Experiment\nPress a button to continue. \n\nPress and hold all 5 buttons to contact Technologist."
	- " \nInstruction\n\nPlease press left point finger when the cental arrowhead points left and press right pointing finger when the central arrowhead poin" &_ 
				"ts right.\n\n\nPress any button if you are ready.. "
	- in current version:
	- "Please press left point finger when the cental arrowhead points left \n \nand press right pointing finger when the central arrowhead poin right"
   
	* using norm (Normalized) as the representation units to addapt easily to differen size of screens.

    
| field | original e-prime version | current version |
|:----------------|:----------------|:----------------|
| win size | (640, 480) | full screen |
| intro text size | 16 | 0.08 |
| fixation text size | 18 | 0.08 |
| text font | Arial & Bold | DejaVu Sans [the default of python] |
| cue image size|  | (0.00002 * win_width, 0.000035 * win_height) |
| target image size |  | (win_width * 0.00025, win_height * 0.0006) |
| Report after experiment | None | RT & ACC |



- __About the experiment: <img width="1026" alt="image" src="https://github.com/XiaoqianXiao/ANT/assets/23469096/2a61a9dd-310b-4312-b785-b48431838c30">__

	- 3 cue conditions (no cue/center cue/spatial cue) * 2 target conditions(congruent/incongruent)
	- each trail: cue -> fixation-> target -> fixation, fixations on the screen during the whole trail- each run: 38 trials
	- 6 runs in total
   	
- __Resources for existing ANT scripts__
  * Please note that all the followings are for Fan et al., 2002
	- https://github.com/baekgaard/ant
	- https://github.com/a-hurst/ANT
	- https://github.com/coneco-lab/modified-ant
