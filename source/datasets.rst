.. index:: datasets, French plays, British novels, stop words
   single: Austen, Jane
   single: Brontë, Charlotte
   single: Hugo, Victor
.. _datasets:

==========
 Datasets
==========


.. code-block:: python3
    :suppress:

    import shutil
    import subprocess

    # NOTE: zip returns an exit code 12 if everything is up-to-date
    subprocess.check_call('zip -q -r -u source/datasets.zip data/french-tragedies-and-comedies/ data/french-tragedies-and-comedies-split/ data/french-tragedy data/french-tragedy-split data/french-plays data/austen-brontë data/austen-brontë-split data/stopwords/ data/british-fiction-corpus data/hugo-les-misérables data/hugo-les-misérables-original data/hugo-les-misérables-split', shell=True)



These texts are available in a compressed zip file: :download:`datasets.zip <datasets.zip>`.

British novels
==============
- A small collection of British novels provided by Jan Rybiki (``british-fiction-corpus``)
- Austen and Charlotte Brontë (``austen-brontë``)
- Austen and Charlotte Brontë (novels split into smaller parts) (``austen-brontë-split``)

French plays
============
- A selection of French Tragedies (``french-tragedy``)
- A selection of French Tragedies (split into small sections) (``french-tragedy-split``)

Les Misérables
==============
- Victor Hugo's Les Misérables (``hugo-les-misérables``)
- Victor Hugo's Les Misérables (split into small sections) (``hugo-les-misérables-split``)

Stopword lists
==============
- A French stopwords list is found in the ``stopwords`` directory.
