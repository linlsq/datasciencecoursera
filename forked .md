# Add the remote, call it "datasharing":

git remote add upstream https://github.com/jtleek/datasharing

# Fetch all the branches of that remote into remote-tracking branches,
# such as datasharing/datasciencecoursera:

git fetch datasharing

# Make sure that you're on your datasciencecoursera branch:

git checkout datasciencecoursera

# Rewrite your datasciencecoursera branch so that any commits of yours that
# aren't already in datasharing/datasciencecoursera are replayed on top of that
# other branch:

git rebase datasharing/datasciencecoursera
