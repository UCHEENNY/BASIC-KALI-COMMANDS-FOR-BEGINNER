# BASIC-KALI-COMMANDS-FOR-BEGINNER
🚀 Mastering the Basics of Kali Linux 💻

Whether you're diving into cybersecurity or just starting out with Linux, knowing your way around the terminal is essential.

I've put together a simple guide with basic Kali Linux commands that every beginner should know — perfect for building confidence in the command line!

🛠️ From system updates to file management, networking, and monitoring — it's all here.

📌 Save it, share it, and tag someone who’s starting their cybersecurity journey!

#KaliLinux #Cybersecurity #LinuxForBeginners #TechTips #Infosec #LinuxCommands #TerminalSkills #EthicalHacking #InfoSecCommunity


🔧 System Update & Upgrade

Sudo apt update  ( Refresh package list)

Sudo apt upgrade ( Install available updates )

Sudo apt update && sudo apt upgrade -y.  (Do both automatically )

📁 File and Directory Management

ls.      (List files in current directory)

ls -l   ( List with details)

ls -a  ( Include hidden files)

cd foldername  ( Change directory)

cd ..  (Go back one level)

cd ~  (Go to home directory) 

mkdir foldername  (Make a new directory)

rm filename  (Remove a file)

rm -r foldername ( Remove a directory and contents)

cp file1 file2 (Copy file1 to file2 )

mv file1 file2 ( Move or rename file1 to file2) 

📝 Working with Files

touch file.txt  (Create an empty file)
cat file.txt      ( View file content )

nano file.txt  ( Edit file in terminal)

head file.txt  ( View first 10 lines)

tail file.txt.    (View last 10 lines) 

🔍 Searching

find . -name file.txt ( Find file in current directory)

grep "text" filename.txt ( Search for text in file) 

🔐 User and Permissions

whoami ( Show current user)

sudo command ( Run command as superuser)

chmod 755 file  (Change permissions) 

chown user:group file (Change ownership) 


📦 Package Management

sudo apt install packagename ( Install package )

sudo apt remove packagename (Remove package)

apt list --installed ( List installed packages )



🌐 Networking

ip a ( Show IP address )

ping google.com ( Check internet connectivity )

ping 8.8.8.8 ( Check google dns for connectivity)

ifconfig  (Sometimes installed via: sudo apt install net-tools)

 netstat -tuln ( Show listening ports )



📊 System Monitoring

top.         (Live system processes)

df -h.      ( Disk space usage )

free -m  ( RAM usage)

 
💡 Useful Tips

• Press TAB to autocomplete.

• Press Ctrl + C to stop a command

• Use man command to read manual, e.g., man ls.

