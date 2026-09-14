# Festival Visitor Guide

## Student Information

- Name: Riyaj Uddin
- Course and section: CSC350 Honors
- Date: 09/13/2026

## Repository Evidence

- Current branch: * main
- Personal Homework 2 GitHub URL: [\[Repository URL\]](https://github.com/rizzUmahadi/csc350-hw2-independent)

- Starting `git status`: On branch main
nothing to commit, working tree clean

- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: Brooklyn Innovation and Culture Festival
- Location: BMCC Campus, New York City
- Intended audience: Students, families, local community members, and technology enthusiasts
- Theme: A celebration of creativity, technology, culture, and community innovation.

## Prediction Before the First Commit

1. Where does the saved change currently live?

   The saved change currently lives in my local working directory on my computer.

2. Has it been staged or committed?

   No. The change has only been saved in the file and has not been staged or committed yet.

## Arrival Information

- Transit or parking: Visitors can take the subway or bus to reach the BMCC campus. Visitors who drive should use a nearby public parking garage.
- Entrance or meeting location: Visitors should meet at the main entrance of BMCC before entering the festival area.

## Accessibility Information

1. The festival location should provide accessible entrances, elevators, and accessible restrooms for visitors with mobility needs.
2. Visitors who need additional assistance or accommodations should contact festival staff at the main entrance.

## Visitor Reminder

Keep personal belongings secure, follow festival staff instructions, stay aware of your surroundings, and arrive early to allow enough time to find the entrance.

## GitHub Verification

Verified on GitHub by Riyaj Uddin.

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | [ID] | `docs: personalize festival visitor guide` |
| Visitor access information | [ID] | `docs: add visitor access information` |
| GitHub verification | [ID] | `docs: verify independent homework on GitHub` |
| Final reflection | [ID] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   Saving a file stores the changes on my local computer. Committing a file records those changes in Git's history with a commit message. A saved change can still be changed, but a commit creates a checkpoint that Git can track.

2. What is the difference between `git diff` and `git diff --staged`?

   git diff shows changes that I have made but have not staged yet. git diff --staged shows changes that I have already staged with git add and that are ready to be committed.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   The sentence was added directly on GitHub, which changed the remote repository. My local repository did not automatically receive the remote change, so the sentence did not appear locally until I ran git pull.

4. What did `-u` accomplish in `git push -u origin main`?

   The -u option sets the upstream branch for my local main branch to the remote origin/main branch. This allows future git push and git pull commands to work without specifying the remote and branch every time.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   
   The evidence includes a clean working tree from git status, matching commit history between the local repository and GitHub, and the latest commit appearing on both repositories. The local main branch should also show that it is up to date with origin/main.

