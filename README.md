# Secure-Electronic-Voting-Blockchain
## Idea
We plan to build and deploy a blockchain for storing the voter's records using the *Azure Blockchain Workbench*. The blockchain will involve a smart contract that handles creating, retrieving, updating and deleting voter's records and also allow a voter to vote for *only one* candidate depending upon his constituency.

## Workflow
1. **Add Voters:** Considering the population statistics, Admin will feed the data into the system and will be automatically divided into various age groups(i.e. >= 18 and < 18).
Then eligible voters get separated from the non-eligible ones.
Using this every time before election we can automatically add people to the Voter List and none is left out.

2. **Add Contestants:** Divide the country into different constitutencies in order wise,i.e., first sort them in states and then constituencies. After that allow the contestants to register, by entering their bio-data and the promises made by them in previous elections (if available). Then using database, we will retrieve their attendance in the Houses and number of cases filed against them (if available), and categorise the cases to different categories.
Here Admin will approve that the data entered by the contestants is valid or not and if anything is found wrong then they may be debarred from the process.

3. **Remote Voting:** Allow the voters to vote from anywhere to their constituency by connecting such voters internally with their *registered constituency*.

4. **Making the Decision:** Using the data entered by the contestants and database maintained, we can display a list of points like *Attendance in the House*, *Criminal Cases Recorded*, *Promises Fulfilled*, ... to help voters make the correct decision.

5. **Live Vote Counting:** As the voters vote for their candidates, *Live Vote Counting* will be running in the background. As soon as the voting period is over, the votes will be accumulated from entire country/state, and the result can be displayed in a short interval of time.

6. **Automatic Verification of Candidates:** By linking the biometric data of voters with their accounts(via Aadhar Card), we can automatically verify the right voter. We can use *IoT devices* like camera to extract the data like type of iris or fingerprint scanner, as the voter is about to vote. This will make the process reliable.

7. **Overcoming EVM Hacking:** A voter at first logs into the system provided by Electoral Commission of India. He can achieve this by importing his data from the Blockchain since he has already registered. A fixed amount of ethers is also credited to allow himw to vote **only once**. On casting the vote, he signs the transaction with it's digital signature. On signing the transaction, the transaction is published to the network and is mined by the Booths. Since the Blockchain is secure and transparent, and once data entered in the system can't be changed, the accusations like *EVM Hacking* is dealt with.

## Team - BIT LORDS

### Indian Institute of Technology Guwahati

- VISHISHT PRIYADARSHI
- SAMIKSHA SACHDEVA
- ROHAN MODI
