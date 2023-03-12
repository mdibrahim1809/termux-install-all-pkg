# termux-install-all-pkg
#Download all packages of termux in one key

#step 1 ---
     $apt update && apt upgrade -y

#step 2 ---
     $pkg update && pkg upgrade -y
#step 3 --- 
     $pkg install python git -y
#step 4 -- for install in termux ---
     $git clone https://github.com/mdibrahim1809/termux-install-all-pkg/
#step 5 ---
     $chmod +x install.py
#step 6 ---
     $python install.py
#your packages are starting to install...
