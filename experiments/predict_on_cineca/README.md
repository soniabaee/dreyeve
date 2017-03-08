Code to run predictions of all sequences on cineca.

* `move_dreyeve_of_to_cineca.py` script to move all optical flow data
to cineca, in order to use it to make predictions.

Usage: `python move_dreyeve_of_to_cineca.py --host <cineca_host> --user <username> --password <password>`

* `predict_dreyeve_sequence.py` script that calls prediction on all frames of a sequence.

Usage: `python predict_dreyeve_sequence.py --seq <sequence_number> --pred_dir <prediction_dir>`