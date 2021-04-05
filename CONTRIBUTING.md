# To Contritube:
 ##### First of all fork this repo and make sure 'Hugo' is installed on your machine.
       hugo version
 ##### If not installed then see [this](https://gohugo.io/getting-started/installing)
 ##### NOTE: If you are using LINUX then it might already be available in your package manager, so you can install it from there.  Eg: sudo pacman -S hugo (For arch).
 #### Step 0: Make a new branch with your username and checkout that.
      git branch yourUserName
      git checkout yourUserName
 #### Step 1: Go to the 'content/' folder:
 #### Step 2: Make a new 'file.md' where "file" should be a number but not clash with the ones already present.
 #### Contents of the file:
     ---
     title: "<The joke that you want to write>."
     ---
 #### Note:You can see the other files to get an idea.
 
 #### Step 3: Write your name in the [CONTRIBUTORS.md](CONTRIBUTORS.md) in the format 
      [Your Name](your github profile link)
 #### Step 4: Run "hugo" in the root directory of the project and let it build.
      hugo
 #### Step 5: Now, you can do a pull request.
