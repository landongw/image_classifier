THIS RUNS THE TRAINER FOR CARDS:

python /Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/retrain.py --bottleneck_dir=/Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/bottlenecks --how_many_working_steps 500 --model_dir=/Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/inception --output_graph=/Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/retrained_graph.pb --output_labels=/Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/retrained_labels.txt --image_dir=/Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/playing_cards


THIS RUNS THE IMAGE CLASSIFIER FOR CARDS:

python /Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/label_image.py /Users/landonwiedenman/Documents/development_projects/landongw/tensorflow_work/image_classifier/test_images/tree.jpeg


DOCS:

https://www.tensorflow.org/tutorials/image_recognition