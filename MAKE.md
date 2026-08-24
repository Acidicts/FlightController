# Make — Quickstart (Just the Steps)

## 1. Install

**Windows**
```
choco install make
```
(no choco? install it from https://chocolatey.org/install, then run the command above)

Or via winget:
```
winget install GnuWin32.Make
```

**macOS**
```
xcode-select --install
```
(installs make along with dev tools)

Or via Homebrew:
```
brew install make
```

**Linux (Debian/Ubuntu)**
```
sudo apt update && sudo apt install make
```

**Linux (Fedora/RHEL)**
```
sudo dnf install make
```

## 2. Check it's installed
```
make --version
```
If you see a version number, you're done with setup.

## 3. Running Make

**Run make in your software/ folder:**
```
make
```
