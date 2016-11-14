---
layout: default
title:  '3. R Notebooks'
---

# <a name="begin"></a> Notebooks

Start an R project in the git repository:

* In RStudio, _File_ -> _New project..._
* Choose _Existing Directory_, and select your project working directory
<br />


#### :computer: Add a data file to an appropriate place in your working directory.
Use a data file of your own, or this example dataset: [bryceveg.R](http://ecology.msu.montana.edu/labdsv/R/labs/lab1/bryceveg.R) (see [dataset description](http://www.davidzeleny.net/anadat-r/doku.php/en:data:bryce) for more info on this dataset)
<details markdown="1">
<summary>:key: Click to see hints</summary>
* A suitable location could be e.g. `[your_project]/data/raw/1992-01-01/`
</details>
<br />

#### :computer: Create a new R Notebook
<details markdown="1">
<summary>:key: Click to see hints</summary>
* File -> ...
* **FIX!!**
</details>
<br />



#### :computer: Add code to notebook to read in the dataset
<details markdown="1">
<summary>:key: Click to see hints</summary>
* Add this to the notebook:...
* **FIX!!**
</details>
<br />



#### :computer: Add code to do some analysis and plots of the data
<details markdown="1">
<summary>:key: Click to see hints</summary>
* Add...
* **FIX!!**
</details>
<br />

#### :computer: Make git ignore html output from R notebooks, and commit the notebook
The html output files are big and generated automatically when the notebook file is saved, so it's not necessary to have it in the repository
<details markdown="1">
<summary>:key: Click to see hints</summary>
* Add `*.nb.html` to .gitignore
* Decide if you want to add and commit the dataset file to the repository, or not
* Commit and push
* _You might have noticed that there is support for git in RStudio – check this out and play around with it_
</details>
<br />


### Extra

#### :computer: Break out some code and put it in a separate .R file in an appropriate place

#### :computer: Call the external code from the notebook
