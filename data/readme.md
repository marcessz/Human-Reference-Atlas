This folder contains the raw and the preprocessed data files that are required for the visualizations:
 * The [asct+b](./asct+b) folder contains the ASCT+B tables, i.e., the raw data of the organs in JSON format
 * The following visualizations are based on the v1.1 release of the ASCT+B tables:
    * The `human_atlas` is a JSON file which contains the nodes and edges for the visualization of the human atlas (all the organs are included)
    * The `human_atlas_f` contains data for the visualization for the female organs
    * The `human_atlas_m` contains data for the visualization for the male organs
    * The files that end with `_c` are the "corected versions": lung vasculature is connected to "Respiratory System" and the "wall of uterine tube" is removed from the first layer
 * The following vosializations are based on the v1.2 release of the ASCT+B tables
    * The file called `male_wing_viz_v12.json` contains the data and config of the visualization of the male body
    * The file called `female_wing_viz_v12.json` contains the data and config of the visualization of the female body
