(1) Download the `BiocDockerOnGCE launch script`_ to your local machine.
.. sidebar:: Details

     This script will create virtual machine on Google Cloud Platform with a locked down network (only port 22 open).  Your local machine will securely connect to the VM via an ssh tunnel.

(2) Run the script on your local machine.  After about 5-10 minutes your browser should redirect to RStudioServer's sign-in page.

.. code:: bash

  ./bioconductorRStudioGCE.sh

(3) Log into RStudio.

.. code:: bash

  username: rstudio
  password: rstudio

(4) Upload ``client_secrets.json``. From the RStudio *Files Pane* click on the "Upload" button.
