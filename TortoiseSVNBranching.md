# Branching and Merging with TortoiseSVN

## Branch

- Right click project root in `Windows Explorer > TortoiseSVN > Branch/Tag`
- Enter the branch label in the `To URL` box. For example `[[trunk_url]]/branches/1.1`
- Choose `Head revision`
- Check `Switch working copy`
- Click `OK`
- Now you have trunk and branch

## Merge Trunk with Branch

 - Right click project root in `Windows Explorer > TortoiseSVN > Merge`
 - Choose `Merge a range of revisions`
 - In `URL to merge from` choose your `trunk`
 - Choose `Merge Depth` to `Working copy`
 - Click `Next`, then the `Test merge` button. This will highlight any conflicts
 - Click `Merge` and resolve if any conflicts
 - Now the changes done in trunk after branching has merged into branch
 - You may perform an `Update` then `Commit`

## Merge Branch with Trunk

 - Switch working copy by right clicking project root in `Windows Explorer > TortoiseSVN > Switch`
 - Switch url to the `trunk`
 - Click `OK`
 - Right click project root in `Windows Explorer > TortoiseSVN > Merge`
 - Choose `Reintegrate a branch` then `Next`
 - In `From URL` choose your branch then `Next`
 - Choose `Merge Depth` to `Working copy`
 - Click `Test merge` button. This will highlight any conflicts
 - Click `Merge`
 - Now the changes of branch are merged into trunk
 - You may perform an `Update` then `Commit`
