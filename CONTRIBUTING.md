# To Contritube:
 ##### First of all make sure Hugo is installed on your machine.
       hugo version
 ##### If not installed then see [this](https://gohugo.io/getting-started/installing)
 ##### Note: If you are using linux then it might already be available in your package manager, so you can install it from there. Eg: sudo pacman -S hugo (For arch).
 #### Step0: Make a new branch with your username and checkout that.
      git branch yourUserName
      git checkout yourUserName
 #### Step1: Go to the 'content/' folder:
 #### Step2: Make a new 'file.md' where "file" should be a number but not clash with the ones already present.
 #### Contents of the file:
     ---
     title: "<The joke that you want to write>."
     ---
 #### Note:You can see the other files to get an idea.
 
 #### Step 3: Write your name in the [CONTRIBUTORS.md](CONTRIBUTORS.md) in the format 
      [Your Name](your github profile link)
 #### Finally run "hugo" in the root directory of the project and let it build.
