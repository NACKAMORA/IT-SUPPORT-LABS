# Linux User Creation and Permission Assignment

## Problem
A new staff user needs an account with administrator privileges.

## Environment
Parrot OS Virtual Machine

## Steps Taken
1. Created a new user using `sudo adduser support`
2. Added user to sudo group using `sudo usermod -aG sudo support1`
3. Switched to the new user account
4. Verified admin privileges using `sudo whoami`

## Solution
The user account was successfully created and granted administrator access.

## Screenshot
![User Creation Screenshot]
(linux_create_user.png)
