# bovw: https://gurus.pyimagesearch.com/lessons/visualizing-words-in-a-codebook/

1) python index_features.py --dataset bovwimg --features-db output/myfeatures.hdf5

2) python cluster_features.py --features-db output/myfeatures.hdf5 --codebook output/myvocab.cpickle --clusters 60 --percentage 0.45

3) python visualize_centers.py --dataset bovwimg --features-db output/myfeatures.hdf5 --codebook output/myvocab.cpickle --output output/vw_vis
