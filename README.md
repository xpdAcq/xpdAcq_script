* General workflow for using user support scripts

  1. Copy and paste the desired script to your working directory.
     Preferably under `xpdUser/userScripts`.

  2. After enter `xpdui` and get to the ipython session, run the
     script with interactive mode (-i option):

     ```
     %run -i userScripts/<script_name.py>
     ```

  3. Open the script and follow the `Example` section in the scan
     plan doc string and execute it.


* All the script in this repo are tested in the simulation mode
  before updating, howeve, please help us report issue when actual
  instruments.
