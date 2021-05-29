# Handy-Functions

This is simply a repository for storage of some useful PowerShell Functions and Scripts created by [Andy Syrewicze](https://www.andyontech.com)

## List of Functions

### Start-Pomodoro

The Start-Pomodoro Function is a Pomodoro timer designed to run within PowerShell. By Default the timer follows the standard Pomodoro best practice of a 25 minute work window followed by a 5 minute break. 

Also included is a check for the [Burnt-Toast PowerShell Module](https://www.powershellgallery.com/packages/BurntToast/0.7.0) that can be called to present Toast Notifications in Windows once the Pomodoro Timer is Done

**NOTE**: By default the function will ask what task you'll be working on and then write that string to the .txt file you define. Make sure to set this varible in the function!
