.. Kashgari documentation master file, created by
   sphinx-quickstart on Fri May 17 14:59:15 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. mdinclude:: main.md


.. toctree::
    :hidden:
    :maxdepth: 0

    main


.. toctree::
    :hidden:
    :maxdepth: 1
    :caption: Tutorial

    tutorial/language_embedding
    tutorial/text_classification_model
    tutorial/sequence_labeling_model

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Advanced use

   tutorial/customize_multi_output_model
   tutorial/deal_with_numeric_features
   tutorial/tensorflow_serving.md

.. toctree::
  :hidden:
  :maxdepth: 2
  :caption: API

  corpus
  api
  CONTRIBUTING
  CHANGELOG