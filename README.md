# 2022 Robot Code

## Run

1. Connect to WPILib via USB cable or network
2. Verify connection on DriverStation
3. Ctrl + Shift + P, `WPILib: Build Robot Code`
4. Ctrl + SHift + P, `WPILib: Deploy Robot Code`

## Troubleshooting

1. Reclone but delete `.gradle`, `.vscode`, and `.wpilib`
2. Rebuild everything from scratch
    1. Create a new project with the Arcade Drive example (without Desktop Support)
    2. Ctlrl + Shift + P, `Manage Vendor Libraries`, `Install new library (online)`, `https://software-metadata.revrobotics.com/REVLib.json`
    3. Copy paste over Robot.cpp
