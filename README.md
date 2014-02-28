# [IHearU](http://www.thecgeinc.org/iHearU_3.html) - Phase 1 Git Repository

## Project Description

**IHearU - Learn Collaborate Volunteer**

IhearU Design Links: [Home](http://www.thecgeinc.org/iHearU_3.html) [About](http://www.thecgeinc.org/About__iHearU.html) [Learn](http://www.thecgeinc.org/iHearU__Learn.html) [Collaborate](http://www.thecgeinc.org/iHearU__Collaborate.html)

## Team Members

**Mentor:** Zune Nguyen


Example: Person 1
youremail@email.com *please put the email you check*

Kang Won Jun 
wonjunka@usc.edu

Dongyang Chen
dyc5828@gmail.com

Erin Wolfe
erinkwol@usc.edu

Leland Coontz
leland.coontz.iv@gmail.com

Annalise Mantz
amantz@usc.edu

Chong-Shu
chongshu@usc.edu

Cristian Hernandez
cbhernan@usc.edu

Saurabh Poddar
spoddar@usc.edu

Chase Mitchell
cbmitche@usc.edu

Mandy Cheong
mycheong@usc.edu

### Groups

#### [PM]()
Annalise Mantz, Erin Wolfe

Leland Coontz **Asst PM*

#### [LA + UX]()
Mandy Cheong **Group Leader**

Jared Blake, Won Jun Kang, Olivia Tranfo, Chong Shu

#### [GRAPHICS]()
Jared Blake **Group Leader**

Leland Coontz, Dongyang Chen, Erin Wolfe, Olivia Tranfo

#### [CONTENT]()
Saurabj Poddar **Group Leader**

Leland Coontz, Katherine Hu, Annalise Mantz, Chase Mitchell, Nicholas Cox, Mandy Cheong

#### [DATA ARCHITECTURE]()
Dongyang Chen **Group Leader**

Cristian Hernandez, Cheong Shu, Won Jun Kang, Katherine Hu

#### [QA LEADS]()
Chase Mitchell **Group Leader**

Nicholcas Cox, Cristian Hernandez, Saurabh Poddar


#### [HTML PROD]()
Olivia Tranfo **Group Leader**

Mandy Cheong, Saurabh Poddar, Jared Blake, Leland Coontz, Karthrine Hu, Erin Wolfe, Annalise Mantz, Chase Mitchel

#### [DEV PROD]()
Cristian Hernandez **Group Leader**

Dongyang Chen, Chong Shu, Nicholas Cox, Won Jun Kang

## Git Commands


### Create a New Repo

Initialize the repository:

```bash
git init
```

Add GitHub origin:

```bash
git remote add origin https://github.com/erinkwolfe/IHearU.git
```

### Check Remote

Remote Status:

```bash
git remote -v
```

### Push to GitHub

Check status of repository, all changed files will be in red:

```bash
git status
```

Add all files to staging area:

```bash
git add -A
```

Check status of repository, all files added should be in green:

```bash
git status
```

Commit to changes, add descriptive commit message:

```bash
git commit -m 'commitMessage'
```

Push to GitHub repo:

```bash
git push -u origin branchName
```

*only need* `-u origin branchName` *on first push.*

### Pull from GitHub

```bash
git pull -u origin branchName
```

*only need* `-u origin branchName` *on first pull.*

### Replace local repo with Github Repo
*This will delete all local file changes*

Fetch GitHub master:

```bash
git fetch origin master
```

Reset local with master:

```bash
git reset --hard origin/master
```
