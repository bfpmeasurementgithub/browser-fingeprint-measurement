# browser-fingeprint-measurement
This project is the open-source code for the paper. Because of user privacy and company legal policy, we can show part of the analysis code. Also, we can not show the dataset. We remove the data pipeline and build rule parts in the open-source code. We public part of the final analysis code because the code has different conditions for the various features, and we show one feature as a demo. Besides, We also removed some functions and replaced some static numbers with fake values to prevent the attacker know the rule about that.

## How to run the code
Because we remove the actual dataset, we can note how to restructure the new dataset and run our code.
Like _timestamp,_id,device_id,ip,bfp
In the test.csv, we need five columns; each has the feature shown in our note. 

## The purpose of each file
### compare_analysis
We analyze the different browser fingerprint features between attackers and benign users. Also, we analyze the attacker features between different companies.

### bot_tool
We show part of the rule on how we parse the bot tools (Using the original name), and we analyze the source of the bot tools.

### probe_attack
We analyze how attackers use probe attacks. 

### None_rate
The file is a preview data process. Because 'None' value is an essential data which we need to understand. Thus we need to ensure whether the user blocks the data or we didn't receive the data, or we received the data, but the data is empty. 

### k_l
How we caculate k_l value.

### feature_in_period
We analyze how attacker and benign user browser fingerprints changed over time.

### bot
We analyze the bot style in the different features.

### attack_type
We analyze the attacker strategy in different attack types.

### attack_speed
We analyze the attack speed in different attack tools.

### attack_example_show
We track the attacker's behavior; We analyze how the attacker modifies the browser fingerprint. 

### attack_account_example_show
We track the attacker's behavior; We analyze how the attacker uses the stolen account information. 

### asn_bfp_entropy.ipynb
We analyze the entropy and other feature of IP and ASN.
