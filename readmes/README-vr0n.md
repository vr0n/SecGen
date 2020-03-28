# vr0n's README for SecGen

## Summary
The goal is to tweak the original SecGen project for my own personal goals. Changes will be noted here.

## Changes
- Original SecGen: Inlucded "attack_vm" to create a minimal kali image for ctf challenges.
- Update: All instances of "attack_vm" have been removed for two reasons: 1) The kali image was throwing an error on newer Debian machines. 2) This version of the project assumes a participant is bringing their preferred VM/machine for ctf challenges.

- Original SecGen: Required "huffman" Gem. 
- Update: No evident reason to retain this and it caused errors on newer versions of Debian

- Original SecGen: READMEs were in home directory
- Update: Created a reasmes directory because there were so many README\*s already.

- Original SecGen: Had a scenario named 'that_escalated_quickly'
- Update: No clue why, but vagrant struggles with system names of a certain length, so I renamed this scenario to 'escalation' to avoid import errors..
