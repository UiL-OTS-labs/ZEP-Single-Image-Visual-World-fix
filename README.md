#Experiment:
Single Image Visual World

#Description:
Purpose of this experiment is to record participant's eye-movements
while he/she is listening to a spoken utterance and looking at a 
screen displaying a semi-realistic scene. For each trial a scene 
is displayed and an utterance relating to the scene is played. 
Participant's task is to carefully look and listen. Self-paced. 
Output: Eye-Tracking data as collected by the eye-tracker.

#Pseudorandomisation
Current pseudorandomisation rules:
* First item must be a filler item.
* The maximum number of subsequent non-filler items is 3.
* The maximum number of subsequent same type non-filler items is 2.
You can test the pseudorandomisation by running
 zep test_pseudorandomisation.zp

#Regions of interest
You can make regions of interest selectable (i.e. equivalent with a button) by setting
 `SELECT_ITEMS_BY_MOUSE = true;`
in defs.zm

You can highlight the regions of interest (default configured to overlap with pictures) by setting
 `SHOW_REGION_OF_INTEREST = true;`
in defs.zm. This allows you to double check if they are what you expect them too be.

#Screencaptures for postprocessing
To generate pictures of the screen for region-of-interest selection run
 zep quick_show_and_save_pictures.zp
This will output pictures (PNG) in 
 `./data/visworldx/img/`
 You might need to change the name of the directories based on your postprocessing of choice.

#Author:

#Client:
  
#Supervisor:

#References:
Huettig, F., Rommers, J., Meyer, A.S. (2011).
Using the visual world paradigm to study language processing: 
a review and critical evaluation.
Acta Psychologica.

#DISCLAIMER

This experiment script is released under the terms of the GNU General Public
License (see http://www.gnu.org/licenses/gpl-2.0.html). It is distributed in
the hope that it will be useful, but with absolutely no warranty. It is your
responsibility to carefully study and test the script before using it with 
real participants.
