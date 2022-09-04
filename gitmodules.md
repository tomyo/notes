#Working with submodules

1. Add submodule

    `git add submodule <https://git-project-url>`
  
2. Adjust `.gitmodules` and add the `branch` you want from the submodule repo.

    `i.e. branch = v1`
  
3. Update submodules with

    `git submodule update --init --recursive --remote --rebase`
    
   * Or as part of the pull command:

    `git pull --recurse-submodules=yes --rebase`  (untested)
    
    
