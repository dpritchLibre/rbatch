
## rbatch - a convenience wrapper for submitting R jobs through the Slurm scheduling system ##

#### Early stages of of ``rbatch`` developement ####

Some goals of ``rbatch`` functionality

1. Remove the need for a script in order to submit an ``R`` job to the ``Slurm``
   schedule
   
2. Handle some boilerplate code automatically, e.g. naming the ``.out`` and
   ``.Rout`` files
   
3. Provide an easy way for options that tend to be the same for every submitted
   job to be permanently saved and reused

4. Create scripts for you for when you do want them

5. Convenient interface for some of the frequently used ``Slurm`` options

6. Interface for ``Slurm`` interactive mode?
