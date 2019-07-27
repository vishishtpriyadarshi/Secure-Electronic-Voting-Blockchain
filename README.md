# Secure-Electronic-Voting-Blockchain
## Idea
We plan to build and deploy a blockchain for storing the voter's records using the Azure Blockchain Workbench. The blockchain will involve a smart contract that handles creating, retrieving, updating and deleting voter's records and also allow a voter for candidate depending upon his constituency.

## Workflow
1. **Add Voters:** Considering the population statistics, Admin will feed the data into the system and will be automatically divided into various age groups(i.e. >= 18 and < 18).
Then eligible voters get separated from the non-eligible ones.
Using this every time before election we can automatically add people to the Voter List and none is left out.

2. **Add Contestants:** Divide the country into different constitutencies in order wise,i.e., first sort them in states , then districts and then constituencies. After that allow the contestants to register, by entering their bio-data and the promises made by them in previous elections (if available). Then using database, we will retrieve their attendance in the Houses and number of cases filed against them (if available), and categorise the cases to different categories.

3. **Remote Voting:** Allow the voters to vote from anywhere to their constituency by connecting such voters internally with their registered constituency.

4. **Making the Decision:** Using the data entered by the contestants and database maintained, we can display a list of points like *Attendance in the House*, *Criminal Cases Recorded*, *Promises Fulfilled*, ... to help voters make the correct decision.

5. **Live Vote Counting:** Make a Live Vote Bar which will be visible to the voters as they vote, regarding the contestants leading in the election(pertaining to their constituency). This will help to declare the Winner Party as soon as Voting Process has ended.

6. **Automatic Verification of Candidates:** By linking the biometric data of voters with their accounts(via Aadhar Card), we can automatically verify the right voter. We can use IoT devices like camera to extract the data like type of iris as the voters is about to vote. This will make the process reliable.

7. **Overcome EVM Hacking:** A voter at first logs into the system. He can achieve this by importing his data from the Blockchain since he is already registered. A fixed amount of ethers is also credited to allow himw to vote only **once**. On casting the vote, he signs the transaction with it's digital signature. On signing the transaction, the transaction is published to the network and is mined by the Booths. Since the Blockchain is secure and transparent, and a voter need not to visit booth to cast votes, the accusations like *EVM Hacking* and *Booth Hijacking* is dealt with.

## Team - BIT LORDS

### Indian Institute of Technology Guwahati

- VISHISHT PRIYADARSHI
- SAMIKSHA SACHDEVA
- ROHAN MODI
