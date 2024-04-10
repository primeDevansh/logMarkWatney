# logMarkWatney
Git/GitHub activity log & description of the experiments I perform with various technical features. By experiments I refer to the coding & various technical experiments I perform. So, below are the 2 sections of this page, logging and experimenting.

# <font color = 'red'>Log</font>

### update1_23.Mar.24 > Repo Naming Disaster!

Oh, no! What the duck! I named this repository as 'ExperimentalR**ee**po' instead of 'ExperimentalRepo'. C'mon Devansh!!! So many typos and you'll end up in JailHub! :p

### update2_06.Apr.24 > Repo Renaming

I am going rename this repo as well. Firstly, I am planning to use this as my GitHub and Git log report more than experimenting with features. Again, I will not stop experimenting! __In fact, no one should ever stop experimenting!__ Cheers! Oh, God! For how many more days do I have to remain single!?

### update3_08.Apr.24 > My Own Blog

For a long time, I've been pondering over the thought of starting my own blog. I tried many sites such as WordPress and Blogger but coudln't satisfy myself for some or the other reason. Now that I know of the GitHub pages' Jekyll thing, I'd be rolling out my own website very soon. Stay tuned! (if anyone is there, xd).

# <font color = 'red'>Experiments</font>

### exp1_23.Mar.24 > Can GitHub Accept Photo and Video Data?

Tried uploading a photo to GH to see if I can use it (a pvt local repo) for photo backup. __Oh, yes! I can__ but then I found on Google that no matter what you upload, you get a storage limit of 500MB. I was disheartened to know that. If it had unlimited storage for code files (like files having an extension .cpp, .java, etc.) then I could've just changed the extension of almost all my photo files to .cpp or anything like that to upload on GH and save on my local storage. I might be wrong in some technicalities like, the way in which things are pushed to GH might change the structure of the file that could lead to a change in the image file or even a corruption.

### exp2_23.Mar.24 > What About a Large Video?

Also tried adding a video file and this is how I came across Git-lfs. Learned it today! Twas nice! xd!

### exp3_06.Apr.24 > Renaming Repos and Directos

First things first, 'directos' means 'directories', idk if this shorto would work xd! Wait, coming to the point, today I am trying to rename git repositories and trying to pull them to local git directory as well. I tweaked (ofc, the name) a repository today but couldn't pull the same to local. Since both the local and the remote were in sync, I deleted the local and re-cloned the remote. It worked! Will surely try more to get a proper way. In the way I even changed a core setting of my machine (got this from [here](https://stackoverflow.com/questions/11183788/in-a-git-repository-how-to-properly-rename-a-directory)).

```bash
git config core.ignorecase true
```

And, never forget to visit [this](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository) page.

### exp4_07.Apr.24 > Writing Markdown Files The 'Correct' Way!

Today, I'd be learning the proper way to write .md files. Till now, I was using **p**-tags for paragraphs, **b**-tags for bold, **a**-tags for hyperlinks and many more old, HTML-fashioned way of doing stuff. From now on, I'd be following the conventional way to write a .md file plus, I'd be correcting most of the README files that I've written so far - slowly ofc. To get going, I'd be starting with this README.md itself.

This is the [guide](https://www.inflectra.com/Support/KnowledgeBase/KB725.aspx) that taught me some of the basics of writing a MARKDOWN file the correct way!

### exp05_07.Apr.24 > Can I Have Another Git Repository Inside an Existing Repository?

Oh, yes! I can have one more git repository under an already existing one! And it is done through [submodules](https://git-scm.com/book/en/v2Git-Tools-Submodules#:~:text=Submodules%20allow%20you%20to%20keep,and%20keep%20your%20commits%20separate.).