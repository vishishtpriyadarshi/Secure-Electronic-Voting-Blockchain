# Secure-Electronic-Voting-Blockchain
## Idea
We plan to build and deploy a blockchain for storing the voter's records using the *Azure Blockchain Workbench*. The blockchain will involve a smart contract that handles creating, retrieving, updating, and deleting voter's records. Also, it'll allow a voter to vote *only once*. 

## Workflow
1. **Add Voters:** Considering the population statistics(using Aadhar), Admin will feed the data into the system which will be automatically divided into two age groups(i.e, >= 18 and < 18).
Then eligible voters get separated from the non-eligible ones.
Using this every time before the election, we can automatically add people to the Voter's List, and none is left out. As a result, e-voter id is also generated automatically for a non-registered voter.

2. **Add Contestants:** Divide the country into different constituencies order-wise, i.e, first sort them in states and then constituencies.Then allow the contestants to register, by entering their bio-data and the promises made by them in previous elections. Then using the database, we will retrieve their attendance in the Houses and number of cases filed against them (if available), and categorize the cases into different categories.
Here Admin will check the validity of data entered by candidates and if found invalid, may debar them.

3. **Remote Voting:** Allow the voters to vote from anywhere to their constituency by connecting such voters internally with their *registered constituency*.

4. **Making the Decision:** Using the data entered by the contestants and database maintained, we can display a list of points like *Attendance in the House*, *Criminal Cases Recorded*, *Promises Fulfilled*, etc. to help voters make the correct decision.

5. **Live Vote Counting:** As the voters vote, *Live Vote Counting* will be running in the background(not visible to voters). As soon as the voting period is over, the votes will be accumulated from the entire country/state, and the result can be displayed in a short interval of time. Also, we can find the various statistical percentages like percentage of citizens voted, etc.

6. **Automatic Verification of Candidates:** By linking the biometric data of voters with their accounts(via Aadhar), we can automatically verify the right voter. We can use *IoT devices* like a camera to extract the data like type of iris or fingerprint scanner, which will make the process more reliable and reduce human labour.

7. **Overcoming EVM Hacking:** A voter at first logs into the system provided by Electoral Commission of India. He can achieve this by importing his data from the Blockchain since he has already registered. A fixed amount of ethers is also credited to allow him to vote **only once**. On casting a vote, he signs the transaction with it's *Digital Signature* or *Blind Signature*. On signing the transaction, the transaction is published to the network and is mined by the Booths. Since the Blockchain is secure and transparent, and once data entered in the system can't be changed, the accusations like *EVM Hacking* is dealt with.

## Team - BIT LORDS

### IIT Guwahati

- VISHISHT PRIYADARSHI
- SAMIKSHA SACHDEVA
- ROHAN MODI
