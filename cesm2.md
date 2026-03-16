
# Instructions for installing CESM2 (as described in [1])

Follow these steps to install CESM2 based on the official documentation:

1. Clone the CESM2 repo and navigate into the sandbox directory:
```
git clone -b release-cesm2.2.2 https://github.com/ESCOMP/CESM.git my_cesm_sandbox
cd my_cesm_sandbox
```

3. Check out the required external components:
```
./manage_externals/checkout_externals
```

5. Navigate to the CIME scripts directory:
```
cd my_cesm_sandbox/cime/scripts
```

7. Create a new case (replace $USER with your username):
```
./create_newcase --case /scratch/midway3/$USER/cases/b.e20.B1850.f19_g17.test --compset B1850 --res f19_g17
```

9. Enter the newly created case directory:
```
cd /scratch/midway3/$USER/cases/b.e20.B1850.f19_g17.test
```

11. Build the case:
```
./case.build
```

12. Submit the case:
```
./case.submit
```

Reference

[1] [CESM2 Installation Guide](https://escomp.github.io/CESM/versions/cesm2.2/html/introduction.html). 
