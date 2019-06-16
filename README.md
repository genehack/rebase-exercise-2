# Rebase exercise two

Rebase the `my-feature` branch onto the tip of the `master` branch.

Note that this time you should have to resolve a merge conflict during
the rebase! Explore what happens if you `git rebase --abort`. Does
picking one side of the conflict versus the other produce different
results?

Your final commit graph should look like this:

```
* f3671b4 - (HEAD -> my-feature) C
* 7ebc3ce - B (3 seconds ago)
* 720cb51 - A (3 seconds ago)
* 3348afd - (master) G
* 9d07566 - F
* 28e0f84 - E
* 767de60 - D
* e29a1f7 - Initial commit

```

(Note that your SHAs will be different.)
