# Illustrator setup

How I've setup Illustrator scripts etc.


## Scripts

I want to have Illustrator scripts in version control. Here's how to do it:

*I have my git repository at `~/code/personal/illustrator`, you should change
the commands to match your setup.*

Open terminal, and run following commands

```bash
cd /Applications/Adobe Illustrator CC 2014/Presets.localized/en_US/
mv Scripts ~/code/personal/illustrator
ln -s ~/code/personal/illustrator/Scripts Scripts
```

That will link Scripts folder which illustrator searches scripts for, to your
git repository.


After operation, restart Illustrator.
