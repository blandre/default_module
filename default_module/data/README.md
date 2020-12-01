# Dealing with datasets

Code in this submodule is responsible for collecting data from files, datasets, or external sources, cleaning, preprocessing, and returning it to the parent module. If the parent module needs to make any changes to the data, these changes should probably have already been made here.

Code that transforms data should ideally be made in a pipeline format, so that if any other modules need any part of it, code can be reused.