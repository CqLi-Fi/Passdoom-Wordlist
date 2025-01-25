# Start

> ❇️ The use of the available data and information is the sole responsibility of the users. All decisions about how and for what purpose this data will be used belong to the user.

> ❇️ The use of the open source script to achieve results by brute force methods is the sole responsibility of the user. The user bears full responsibility for how and for what purpose this script is used.

> ❇️ The current passdoom.py script is designed specifically for hash-breaking tasks. If you have other use cases in mind, such as analyzing or generating wordlist files, you'll need to handle those separately.

> ✴️ The word list files titled 'Data' contain leaked passwords that we have identified and obtained. It is recommended to check them regularly for your security.

# Execution
[![Version](https://img.shields.io/badge/Passdoom-0.0.1beta-brightgreen.svg?maxAge=259200)]()
```bash
pip install requests rich alive-progress
```

```bash
python3 passdoom.py
```

```bash
python3 passdoom.py hash.txt
```

# Usage Areas

Structurally, its use in these areas was tested and it was found that it needed to be improved for some targets.
```bash
✔️ Email systems (Gmail, Hotmail, Yandex)
✔️ Social media platforms (İnstagram, Twitter)  
✔️ FTP Servers
✔️ Wifi
🟠 Crypto Wallets
🟡 PhpMyAdmin
✔️ CPanel
✔️ Wordpress
✔️ MD5
✔️ SHA1
```

# Passdoom

> The "wordlist" data within the project offers a comprehensive range of password combinations automatically generated using advanced encryption and security techniques. These combinations serve as a critical resource for identifying potential vulnerabilities, testing password strength, and conducting in-depth attack simulations. The wordlist data supports a robust password-cracking process, enabling users to enhance their security levels while proactively identifying and mitigating potential threats. Moreover, this data significantly demonstrates detection capabilities, revealing security weaknesses with high precision.

## Creating an Encryption Combination

#### Potential Password Combination

```bash
A = Animal Name / Everyday Item / Hobby
B = Work / Sport / Team / Special Day / Date
C = Important Person / Character / Celebrity
D = Numbers / Special Characters
N = Username (let's take Jessica as an example)
```

| Salt    | Format   | Password                     |
| :-------- | :------- | :--------------------------  |
| `⚪ 1`|`N + B + D + C`|🔑 Jessica1992*Barca.       |
| `⚪ 2`|`C + D + N + A + B`|🔑 Barca/JessicaCat1992 |
| `⚪ 3`|`N + A + B + C + D`|🔑 JessicaCat1992Barca. |
| `⚪ 4`|`D + N`|🔑 155664jessica                    |
| `⚪ 5`|`B + N + D`|🔑 1995Jessica*                 |


#### Total Combination Calculation
This calculation reflects the amount of password combinations generated from a single “username” or “definition”.
```bash
1. (User Name Options)
2. (Animal/Hobby Options)
3. (Date/Event Options)
4. (Important Person / Celebrity Options) 
5. (Special Character Options)

X. Total Combinations = 100 × 30 × 30 × 30 × 50 × 20 × 10
Z. Total Combination  = 3.000.000
```

#### Bulk Diversification
A combination of infinite language options with limited options such as special characters, usernames, etc. leads to some pretty big results.

```bash
X. Total Combinations = 100 × 30 × 30 × 30 × 50 × 20 × 10
Z. Total Combination  = 3.000.000
P. Language Options   = 500 Million
```

#### Wordlist Paths
Use your preferred word list with the url structure without the need to download and get rid of the burden.

```bash
Raw[EN] : raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/english.txt
Raw[TR] : raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/turkish.txt
|-------: raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/turkish2.txt
Raw[FTP]: raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/ftp.txt
Raw[NUM]: raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/numbers.txt
Raw[DAT]: raw.githubusercontent.com/CqLi-Fi/Passdoom-Wordlist/refs/heads/main/Wordlist/data11_2024.txt
```

# Donate 🎉

We gladly accept your crypto donations! 💖 If you want to support us, you can use the button below.

[![Donate with USDT](https://img.shields.io/badge/Donate-USDT-26A17B?logo=tether&logoColor=white&style=for-the-badge)](https://etherscan.io/address/0xf0d4c8708b4ceee73da1dd8c972527779d4a21b8)
