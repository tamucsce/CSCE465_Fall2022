## Course Information
- **Instructor**: Prof. Yupeng Zhang (zhangyp@tamu.edu)
- **Lectures**: MW 5:35 pm - 6:50 pm
- **Office Hour**: By appointment

## Course Description and Prerequisites

This course covers techniques in applied cryptography and their applications in machine learning and blockchain to enhance data privacy. Related cryptographic techniques include secure multiparty computations, verifiable computations and zero knowledge proofs. We will discuss their basic concepts and state-of-the-art constructions. Additionally, we will talk about how to use these techniques to construct privacy-preserving machine learning, crypto-currencies and blockchain. We will focus on efficiency and functionality constraints in practice, and discuss challenges and solutions to efficiently realize these cryptographic protocols. 

The course has no specific prerequisites. Basic knowledge of algorithms, data structures and programming is recommended.



## Textbook and Resource Materials

No textbook is required for the course. Reading materials will be posted online during the semester


## Schedule (tentative)

<table style="width: 140%">
    <tr>
        <th style="width: 5%;">Date</th>
        <th style="width: 20%;">Sections</th>
        <th style="width: 40%;">Topic & slides</th>
        <th style="width: 45%;">Readings</th>
        <th style="width: 20%;">Deadlines</th>
    </tr>
    <tr>
        <th>1/20</th>
        <th rowspan="2">Introduction</th>
        <th>Introduction and logitics</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>1/25</th>
        <th>Background on Cryptography</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>1/27</th>
        <th rowspan="7">Secure Multiparty Computation and Privacy-Preserving Machine learning</th>
        <th>Introduction to secure multiparty computation and Oblivious Transfer</th>
        <th>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>2/1</th>
        <th>Yao's Garbled circuit</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>2/3</th>
        <th>GMW protocol</th>
        <th></th>
        <th>Team Formation</th>
    </tr>
    <tr>
        <th>2/8</th>     
        <th>Malicious security and fairness</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>2/10</th>
        <th>Privacy-preserving machine learning and linear regression</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>2/15</th>
        <th>Privacy-preserving logistic regression</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>2/17</th>
        <th>Privacy-preserving neural networks</th>
        <th></th>
        <th>Proposal due</th>
    </tr>
        <tr>
        <th>2/22</th>
        <th rowspan="15">Verifiable Computation, Zero Knowledge Proof and Blockchain</th>
        <th>Introduction to verifiable computation and zero knowledge proof</th>
        <th></th>   
        <th></th>
    </tr>
    <tr>
        <th>2/24</th>
        <th>Customized solutions: RSA accumulator</th>
        <th>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>3/1</th>
        <th>Customized solutions: Bilinear accumulator</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/3</th>
        <th rowspan="2">Generic solutions:SNARK</th>
        <th rowspan="2"></th>
        <th></th>
    </tr>
    <tr>
        <th>3/8</th>
        <th></th>
    </tr>
    <tr>
        <th>3/10</th>
        <th>Midterm project presentation</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/15</th>
        <th>Midterm project presentation</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/17</th>
        <th>Introduction to blockchain and cryptocurrency</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/22</th>
        <th>Pricacy-preserving crypto-currencies</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/24</th>
        <th>Smart contract</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/29</th>
        <th>Privacy-preserving smart contract</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/31</th>
        <th rowspan="4">Generic solutions: interactive proofs
        </th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>4/5</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>4/7</th>
        <th></th>    
        <th></th>
    </tr>
    <tr>
        <th>4/12</th>
        <th></th>
        <th></th>
    </tr>
        <tr>
        <th>4/14</th>
        <th rowspan="4">Project Presentations</th>
        <th></th>
        <th></th>
        <th></th>
    </tr>
      <tr>
        <th>4/19</th>
        <th></th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>4/21</th>
        <th></th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>4/26</th>
        <th></th>
        <th></th>
        <th>Final report due 4/29</th>
    </tr>
</table>

## Grading
**Reading assignments:** 35%. Students will submit reviews for one of the reading materials every week.

**Course project:** 65%. Students will form groups and complete research projects related to the topics of the course.

## Links

**Assignments and Gradebook:** http://ecampus.tamu.edu/

## Suggested topics for projects:
### Secure Multiparty Computations

- **Privacy-preserving decision trees and random forest training and/or predictions**: apply MPC techniques to train decision tree and random forest models on encrypted data. 1. Understand decision tree and random forest. 2. Collect datasets and implement training and predictions on plaintext data. 3. Use only those computations efficiently supported by MPC, compare the accuracy to the baseline. 4. Implement the MPC protocol using existing libraries.
- **Privacy-preserving SVM training and/or predictions**: apply MPC techniques to train SVM models on encrypted data. 1. Understand SVM. 2. Collect datasets and implement training and predictions on plaintext data. 3. Use only those computations efficiently supported by MPC, compare the accuracy to the baseline. 4. Implement the MPC protocol using existing libraries.

### Zero Knowledge Proof

- **Zero knowledge proof for machine learning model predictions**: generate a proof that the predictions of a secret model on a public testing dataset reaches certain accuracy. Design efficient ZKP protocols for convolution, neural networks and common activation functions.    
- **Contingent payment on blockchain with zero knowledge proof**: design fair exchange protocols on blockchains using zero knowledge proofs.
- **Privacy-preserving smart contracts**: 1. Understand the mechanism of smart contract. 2. Find commonly used smart contracts on existing blockchains and cryptocurrencies. 3. Given general purpose ZKP, design protocols for privacy-preserving smart contracts. 4. Implement the ZKP protocol using existing libraries and optimize for those commonly used smart contracts.

### Blockchains

- **Information inference from public data on Bitcoin blockchain**: 1. Understand the public data posted on the blockchain of Bitcoin and figure out ways to download the data. 2. Repeat data analysis from existing papers. 3. Design new attacks to infer sensitive information from the public data, such as dead coins and large volume transactions and its correlations with the price of bitcoin.
- **Information inference from public data on Ethereum**: Same as bitcoin. In addition, analyze the smart contracts.
- **Scaling up blockchains**: sharding, rollup (optimistim rollup and zk rollup) etc.

## Ethics & Academic Integrity Statement and Policy

"An Aggie does not lie, cheat, or steal or tolerate those who do." For additional information, please visit: http://aggiehonor.tamu.edu.  

Upon accepting admission to Texas A&M University, a student immediately assumes a commitment to uphold the Honor Code, to accept responsibility for learning, and to follow the philosophy and rules of the Honor System. Students will be required to state their commitment on examinations, research papers, and other academic work. Ignorance of the rules does not exclude any member of the TAMU community from the requirements or the processes of the Honor System.


