# Resetting MacBook Pro Touchbar
Reset frozen Touch Bar on MacBook Pro

Save AppleScript code as an application (.app) and add it to Applications.
Drop it to the Dock (optionally) for a faster access.

# AppleScript
tell application "System Events"
tell process "Touch Bar agent" to quit
delay 1
tell process "ControlStrip" to quit
end tell

