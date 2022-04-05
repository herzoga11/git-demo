#Demo Git Repository

This is the first file in this repository.

##Webist content

Here are the files in the website.

1. index.html

##Commands used in Section 3: Working with Git Locally

 cd development/projects/git-demo
    7  notepad++ README.md
    8  git status
    9  notepad++ README.md
   10  git status
   11  git add README.md
   12  git status
   13  git commit
   14  git commit -m "adding some ipsum"
   15  clear
   16  git status
   17  notepad++ README.md
   18  git status
   19  git commit -am "some more ipsum"
   20  git status
   21  pwd
   22  clear
   23  pwd
   24  git status
   25  clear
   26  notepad++ index.html
   27  git status
   28  git add index.html
   29  notepad++ README.md
   30  notepad++ README.md
   31  git status
   32  git add README.md
   33  get status
   34  git status
   35  git commit -m "A few changes for the website"
   36  clear
   37  notepad++ README.md
   38  notepad++ index.html
   39  git status
   40  git add .
   41  git status
   42  git commit -m "A few more changes for website."
   43  git status
   44  clear
   45  git status
   46  ls
   47  notepad++ README.md
   48  git status
   49  git add README.md
   50  git status
   51  git restore --staged README.md
   52  clear
   53  git status
   54  notepad++ README.md
   55  git restore README.md
   56  git status
   57  notepad++ README.md
   58  git log
   59  git log -help
   60  git help log
   61  git log --oneline --graph --decorate --color
   62  clear
   63  pwd
   64  git status
   65  notepad++ debug.log
   66  ls
   67  git status
   68  git add debug.log
   69  git status
   70  git commit -m "adding log file that does not belong here"
   71  git status
   72  clear
   73  git rm debug.log
   74  ls
   75  git status
   76  git commit -m "removing debug.log file"
   77  git status
   78  notepad++ info.log
   79  ls
   80  git add info.log
   81  git commit -m "adding info.log"
   82  git status
   83  clear
   84  ls
   85  rm info.log
   86  ls
   87  git status
   88  git add -u
   89  git status
   90  git commit -m "remove info.log"
   91  git status
   92  clear
   93  ls
   94  mkdir web
   95  la
   96  ls
   97  git mv index.html web
   98  cd web/
   99  ll
  100  cd ..
  101  ls
  102  git status
  103  git commit -m "moving index.html to web folder"
  104  git status
  105  notepad++ try.log
  106  mv try.log web
  107  git status
  108  git add -u
  109  git status
  110  git add web/try.log
  111  git status
  112  git commit -m "try.log moved to web"
  113  git status
  114  cd web/
  115  ls
  116  git rm try.log
  117  git status
  118  git restor --staged try.log
  119  git restore --staged try.log
  120  git status
  121  git restore try.log
  122  git status
  123  cd ..
  124  cd web
  125  git rm try.log
  126  git status
  127  git commit -m "remove try.log from web dir"
  128  git status
  129  cd ..
  130  notepad++ application.log
  131  ls
  132  git status
  133  notepad++ .gitignore
  134  ls
  135  git status
  136  ls -a
  137  git add .gitignore
  138  git status
  139  git commit -m "adding ignore file"
  140  git  history
  141  history