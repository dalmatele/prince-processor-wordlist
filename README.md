# prince-processor-wordlist
Lists of tokens for prince processor attack

## Introduce
- This repo includes a lot of lists of token I'm using in prince processor attack.
- I'm using this tool to generate list of password from these lists: https://github.com/hashcat/princeprocessor
    - We don't need to seperate words to uppercase and lowercase because we can use `case-permute` option as mentioning `For each word in the wordlist that begins with a letter generate a word with the opposite case of the first letter`

## Content (Updating)
- List of Vietnamese single words
- Lists of some common used words in English

## Probability of some formats

### Use special chars

| Password type | Probability | Example |
|---------------| ------------| --------|
| not have special chars | ~70% | 123456, password123|
| have one special char | ~15% | passw0rd!|
| have 2-3 special chars | ~10% | hello!@ |
| more than 3 special chars | ~5% | @Secure_P@ssw0rd# |

### Probability of special chars are using
| char | Probability | Example |
|------|-------------|---------|
| ! | ~45% | Password! |
| @ | ~18% | hello@ |
| # | ~12% | Secure#2023 |
| $ | ~10% | Money$afe |
| % | ~5% | Trust%me |
| & | ~4% | Love&Peace |
| * | ~3% | MyP@ssword* |
| ? | ~2% | GuessMe? |
| ^ | ~1% | Strong^Pass |

### Probability of passwords by length

| Length | Probability | Example |
|--------|-------------|---------|
| 10 chars | 30% | Minh1995@ |
| 11 chars | 20% | Linh2000!@ |
| 12 chars | 18% | Quang1234#abc |
| 13 chars | 12% | BichNgoc2023$ |
| 14 chars | 8% | ThanhTuan1999# |
| 15-18 chars | 5% | TieuLongNu_1997!@# |
| > 18 chars | 2% | GauYeuBong@2024!abc |

### Probability of passwords by length bases on Rockyou data

| Length | Probability | Example |
|--------|-------------|---------|
| 10 chars | 18% | Minh1995@ |
| 11 chars | 13% | Linh2000!@ |
| 12 chars | 11% | Quang1234#abc |
| 13 chars | 8% | BichNgoc2023$ |
| 14 chars | 6% | ThanhTuan1999# |
| 15-18 chars | 5% | TieuLongNu_1997!@# |
| > 18 chars | 2% | GauYeuBong@2024!abc |