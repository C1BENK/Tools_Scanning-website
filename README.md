pembuat/dev/credits : C1B_ENK
use in a safe place
The creator is not responsible for anything the user does.

# Scan dasar
python advanced_scanner.py https://example.com

# Scan dengan depth lebih dalam
python advanced_scanner.py https://example.com -d 3 -t 15

# Scan dengan output file
python advanced_scanner.py https://example.com -o results.json

# Scan dengan timeout custom
python advanced_scanner.py https://example.com -T 20


pkg update && pkg upgrade -y
pkg install python git clang make pkg-config -y
#optionals that are often useful
pkg install openssl libxml2 libxslt -y

install all at once

pip install requests beautifulsoup4 dnspython tldextract fake-useragent lxml html5lib cssselect python-dateutil