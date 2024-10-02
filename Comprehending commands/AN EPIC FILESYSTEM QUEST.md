# AN EPIC FILESYSTEM QUEST
it was a very good challenge..but very lengthyy.i solved by using ls ,cd ,cat commands..found difficulty where i had to find the file
without using cd ..TOTALL PERSEVERANCE INDEED!!  
``` bash
                                                                                                                                                     Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ cat /
cat: /: Is a directory
hacker@commands~an-epic-filesystem-quest:/$ ls /
WHISPER  challenge  flag  lib32   media  opt   run   sys  var
bin      dev        home  lib64   mnt    proc  sbin  tmp
boot     etc        lib   libx32  nix    root  srv   usr
hacker@commands~an-epic-filesystem-quest:/$ ls -a /
.           WHISPER  challenge  flag  lib32   media  opt   run   sys  var
..          bin      dev        home  lib64   mnt    proc  sbin  tmp
.dockerenv  boot     etc        lib   libx32  nix    root  srv   usr
hacker@commands~an-epic-filesystem-quest:/$ cat /whisper
cat: /whisper: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cat /WHISPER
Lucky listing!
The next clue is in: /usr/share/doc/libqt5gui5

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd  /usr/share/doc/libqt5gui5
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ ls  /usr/share/doc/libqt5gui5
NOTE  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ cat  /usr/share/doc/libqt5gui5
cat: /usr/share/doc/libqt5gui5: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ cat /NOTE
cat: /NOTE: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ cat /changelog.Debian.gz
cat: /changelog.Debian.gz: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ ls
NOTE  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ cat
 NOTE
Tubular find!
The next clue is in: /usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libqt5gui5$ cd
/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ ls -a
.               include.htm      scc.htm     stdout.htm
..              index.htm        scrc.htm    stl.htm
.CLUE           large_pages.htm  sdel.htm    stop_switch.htm
ar_exclude.htm  list_tech.htm    sfx.htm     stx.htm
ar_include.htm  method.htm       shared.htm  style.css
ar_no.htm       output_dir.htm   sni.htm     type.htm
bb.htm          overwrite.htm    sns.htm     update.htm
bs.htm          password.htm     spf.htm     volume.htm
charset.htm     recurse.htm      ssc.htm     working_dir.htm
exclude.htm     sa.htm           stdin.htm   yes.htm
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ cat CLUE
cat: CLUE: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ cat .CLUE
Great sleuthing!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/STIX/SizeOneSym

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ ls /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/STIX/SizeOneSym
Bold  CUE-TRAPPED  Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ cat  /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/STIX/SizeOneSym/CUE-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/share/icons/ubuntu-mono-light

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/p7zip/DOC/MANUAL/cmdline/switches$ cd  /usr/share/icons/ubuntu-mono-light
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls
INSIGHT  animations  categories        index.theme  places  stock
actions  apps        icon-theme.cache  mimes        status
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ cat INSIGHT
Tubular find!
The next clue is in: /usr/share/javascript/three/examples/jsm/renderers
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls  /usr/share/javascript/three/examples/jsm/renderers
CSS2DRenderer.d.ts       RaytracingRenderer.js
CSS2DRenderer.js         SECRET
CSS3DRenderer.d.ts       SVGRenderer.d.ts
CSS3DRenderer.js         SVGRenderer.js
Projector.d.ts           WebGLDeferredRenderer.d.ts
Projector.js             WebGLDeferredRenderer.js
RaytracingRenderer.d.ts
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ cat  /usr/share/javascript/three/examples/jsm/renderers/SECRET
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/Documentation/sphinx
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls /opt/linux/linux-5.4/Documentation/sphinx
HINT           kernel_include.py  kfigure.py        requirements.txt
automarkup.py  kerneldoc.py       load_config.py    rstFlatTable.py
cdomain.py     kernellog.py       parse-headers.pl
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls /opt/linux/linux-5.4/Documentation/sphinx/HINT
/opt/linux/linux-5.4/Documentation/sphinx/HINT
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ cat /opt/linux/linux-5.4/Documentation/sphinx/HINT
Lucky listing!
The next clue is in: /usr/share/javascript/mathjax/unpacked/localization/pt-br

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special /usr/share/javascript/mathjax/unpacked/localization/pt-brunpacked/localization/pt-br /usr/share/javascript/mathjax/unpacked/localization/pt-brunpacked/localization/pt-brization/pt-br
/usr/share/javascript/mathjax/unpacked/localization/pt-br:
.  ..  .NUGGET  FontWarnings.js  HTML-CSS.js  HelpDialog.js  MathML.js  MathMenu.js  TeX.js  pt-br.js

/usr/share/javascript/mathjax/unpacked/localization/pt-br:
.  ..  .NUGGET  FontWarnings.js  HTML-CSS.js  HelpDialog.js  MathML.js  MathMenu.js  TeX.js  pt-br.js

/usr/share/javascript/mathjax/unpacked/localization/pt-br:
.  ..  .NUGGET  FontWarnings.js  HTML-CSS.js  HelpDialog.js  MathML.js  MathMenu.js  TeX.js  pt-br.js
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls -a  /usr/share/javascript/mathjax/unpacked/localization/pt-br
.  ..  .NUGGET  FontWarnings.js  HTML-CSS.js  HelpDialog.js  MathML.js  MathMenu.js  TeX.js  pt-br.js
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ cat  /usr/share/javascript/mathjax/unpacked/localization/pt-br/.NUGGET
Lucky listing!
The next clue is in: /usr/share/doc/git/contrib

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ ls  /usr/share/doc/git/contrib
README         contacts          examples          git-shell-commands   persistent-https   stats                     update-unicode
TRACE-TRAPPED  coverage-diff.sh  fast-import       hg-to-git            remote-helpers     subtree                   vscode
buildsystems   credential        git-jump          hooks                remotes2config.sh  svn-fe                    workdir
coccinelle     diff-highlight    git-resurrect.sh  long-running-filter  rerere-train.sh    thunderbird-patch-inline
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$ cat  /usr/share/doc/git/contrib/TRACE-TRAPPED
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{A2fTa4TgMPy934dwIc_dDqHysx6.dljM4QDL1MjN0czW}
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/ubuntu-mono-light$
```

https://unix.stackexchange.com/questions/285809/change-directory-without-using-cd
