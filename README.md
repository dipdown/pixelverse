# BotPXLV

## Installation
1. Clone the repository: `git clone https://github.com/gvoze32/botpxlv.git`
2. Navigate to the project directory: `cd botpxlv`
3. Install node dependencies: `npm i`
4. Install py dependencies: `pip install requests beautifulsoup4`

## Usage
1. Run domains getter `python3 get_domains.py`
2. Run the script: `node index.js`
3. Follow the prompts to input the referral code, and the number of referrals you want to generate.
4. The script will then proceed to register users with randomly generated email addresses and refer them using the provided referral code.

## Additional Notes
- Adjust the delay between requests (`setTimeout`) according to your needs and service limitations to avoid rate-limiting or bans
