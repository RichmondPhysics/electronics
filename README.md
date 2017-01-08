# 132
Source for Electronics (PHYS 216) lab manual.

----
Note by Matt Trawick, 1/8/2017:
The electronics manual and the 131 manual are coupled together, in the sense that they share some files and refer explicitely to each other.  If you want electronics to work, you need to have 131 cloned locally as well. This arose to avoid having two different versions of the same files in the two repos.  

- Because files in the 132 repository can now refer to files within the 131 repository, this means that in order to compile, the electronics and 131 repositories have to be placed in directories in the same place relative to each other.  Both of the repositories need to be cloned locally as subdirectories of a common directory:

/Lab_manuals_directory
  |-131
  |   |-StudentGuideModule1
  |   |-.git
  |
  |-electronics
      |-electronics_manual
      |-.git
    

----
