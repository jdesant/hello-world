# hello-world
hello world repository
github.com/jdesant
git filter-repo --commit-callback '
commit.committer_date += datetime.timedelta(hours=<23>) if commit.committer_date else None
commit.author_date += datetime.timedelta(hours=<23>) if commit.author_date else None
'
