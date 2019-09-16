MyBands

![Image of MyBands APp](main.png)

Preparation: Download 8 images of your favorite bands. Rename to [Band Name].jpg (or.png)

1) Create new Master/Detail Universal Project (No CoreData)

2) Delete label on DetailViewController

3) Add UIImage to DetailViewController

   - View Mode: Aspect Fit
   - Create Outlet, Name: productImageView
   - Select Detail icon 
     ![alt text](format.png "layout")
   - Select Editor > Resolve Auto Layout Issues > Reset to Suggested Constraints
   
4)Create New Group named Images and add the images you downloaded during preparation

5)Follow Instructions in Comments on [MasterViewController.swift](https://raw.githubusercontent.com/ioscourse/MyFavBands/master/MyFavBands/MasterViewController.swift)

6)Follow Instructions in Comments on [DetailViewController.swift](https://raw.githubusercontent.com/ioscourse/MyFavBands/master/MyFavBands/DetailViewController.swift)

7)Compile & Run (Command + R)

Done!
