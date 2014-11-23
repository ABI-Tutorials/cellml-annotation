.. _annotationTutorialIndex:

================================
CellML Model Annotation Tutorial
================================

We are currently interested in annotating entities in `CellML <http://cellml.org/>`_ models with biological information using OpenCOR as per :ref:`these instructions <OpenCOR-annotateACellmlElement>` (as used in the earlier tutorials). We will be annotating existing models from the repository and so you will always be working with *public* workspaces.

The basic sequence to follow in working on annotating models is given below. Things work easier if you either work on separate workspaces at the same time or work together in annotating a single model. If some of these steps don't make sense, maybe go back and look through the previous tutorials, :ref:`PMR documentation <abi-pmr2-index>`, or :ref:`OpenCOR documentation <OpenCOR-index>` again. If it still doesn't make sense, let me know that I need to improve the documentation (or better yet, once your work it out let me know how the documentation could be improved/corrected).

#. Decide on a model to annotate and locate its workspace.
#. Make sure the workspace you want to work with is in the google spreadsheet and that your name(s) is noted for that workspace.
#. :term:`Clone` the workspace to your local storage.
#. Add some biological annotations to the model

   #. extract the biological entities from the journal articles
   #. find the corresponding entities in the CellML model using the :ref:`OpenCOR CellML Annotation view <OpenCOR-plugin-cellmlannotationview>` (usually ``component`` or ``variable`` elements) 
   #. create the annotation
   
      * usually the ``bio:isVersionOf`` qualifier
      * search for the most appropriate term(s) to add
      * its ok to add a few terms and then we can refine later if needed
      
   #. save often in OpenCOR
   #. :ref:`commit changes <cellmlrepositorytutorial-hg>` to your local copy of the Mercurial repository often
   #. and repeat...
   
#. :ref:`push changes <cellmlrepositorytutorial-hg>` back to the repository.
#. Make sure the model being annotated is being :ref:`indexed by the repository <tutorialOpenCOR-annotation>`.

We will evaluate how well this process is working during regular meetings, which will also provide an opportunity to review the annotations being made. So don't worry about getting things perfect first time - it is better to be getting annotations into the models and the changes recorded in the history of the workspace.