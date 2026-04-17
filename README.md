# Alice UPC Unfolding
To setup this repo locally, do

`git clone https://github.com/rolavick/AliceUnfolding.git`


To run UnfoldJpsiuMid.ipynb with local .venv jupyter notebook do

`.venv.Python313/bin/jupyter notebook UnfoldJpsiMid/UnfoldJpsiMid.ipynb `

# For git-alergic people
If you want to update your local repo with whatever is origin (upstream) do

`git pull`

If you have some local changes which prevent from updating do

`git pull --rebase`

If you want to simply forget your local changes and just start from the origin do

`git fetch origin main`

`git reset --hard origin/main`

If you want to put upstream your changes do

`git status`

to see your changes

`git add .`

to add all your changes to the commit (or instead . just put the files names)

`git commit -m "blabla"`

to commit and append a message

`git pull --rebase`

to merge your changes with origin

`git push origin main`

to publish your changes for the rest of the team
