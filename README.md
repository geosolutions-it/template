# template
Template repository for GeoSolutions's projetcs

To copy label from this repository to another use the tool linked below:

https://github.com/jvandemo/copy-github-labels-cli

This requires Node.JS to be installed.

Note: If some labels already exists in the new repository, you will get "Unknown label: failed (Validation Failed)" messages. To prevent this, remove all the labels from the new repository before copying the labels.

Example:

copy-github-labels -t 123456789 geosolutions-it/repo-template geosolutions-it/new_repo
