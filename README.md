# Week 1 Linux Hands-on Lab

## Tasks Completed

1. Created the `~/cloud-devops/week1` directory.
2. Created `notes.txt`.
3. Added text to `notes.txt`.
4. Created the `scripts` directory.
5. Moved `notes.txt` into `scripts/`.
6. Searched for `notes.txt` using `find`.
7. Found a running process and identified its PID.

## Commands Used

```bash
mkdir -p ~/cloud-devops/week1
touch ~/cloud-devops/week1/notes.txt
echo "Week 1 Linux Hands-on Lab" > ~/cloud-devops/week1/notes.txt
mkdir ~/cloud-devops/week1/scripts
mv ~/cloud-devops/week1/notes.txt ~/cloud-devops/week1/scripts/
find ~/cloud-devops/week1 -name "notes.txt"
ps
pgrep -a bash
