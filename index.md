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
        <th style="width: 40%;">Topic</th>
        <th style="width: 45%;">Readings</th>
        <th style="width: 20%;">Deadline</th>
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
        <th rowspan="8">Secure Multiparty Computation and Privacy-Preserving Machine learning</th>
        <th>Introduction to secure multiparty computation and Oblivious Transfer</th>
        <th><a href="https://en.wikipedia.org/wiki/Oblivious_transfer#:~:text=In%20cryptography%2C%20an%20oblivious%20transfer,if%20any)%20has%20been%20transferred">Wikipedia</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>2/1</th>
        <th>Yao's Garbled circuit</th>
        <th>
        <ul>
            <li><a href="https://www.peteresnyder.com/static/papers/Peter_Snyder_-_Garbled_Circuits_WCP_2_column.pdf"> Yao's Garbled circuits</a></li>
            <li><a href="https://www.youtube.com/watch?v=GjhvJxelIVQ">Youtube tutorial</a></li>
            <li><a href="https://www.iacr.org/archive/eurocrypt2015/90560204/90560204.pdf">Half gates</a></li>
        </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>2/3</th>
        <th>GMW protocol</th>
        <th><a href="https://www.youtube.com/watch?v=4YwvZaA9IEg">Youtube tutorial</a></th>
        <th>Team Formation</th>
    </tr>
    <tr>
        <th>2/8</th>     
        <th>Malicious security and fairness</th>
        <th><a href="https://eprint.iacr.org/2008/049.pdf">Cut and choose</a></th>
        <th></th>
    </tr>
    <tr>
        <th>2/10</th>
        <th>Privacy-preserving machine learning and linear regression</th>
        <th><a href="https://eprint.iacr.org/2017/396.pdf">SecureML</a></th>
        <th></th>
    </tr>
    <tr>
        <th>2/15</th>
        <th></th>
        <th><a href="https://eprint.iacr.org/2018/403.pdf">ABY3: A Mixed Protocol Framework for Machine Learning</a></th>
        <th></th>
    </tr>
    <tr>
        <th>2/17</th>
        <th></th>
        <th><a href="https://people.eecs.berkeley.edu/~wzheng/helen_ieeesp.pdf">Helen: Maliciously Secure Coopetitive Learning for Linear Models</a></th>
        <th></th>
    </tr>
    <tr>
        <th>2/22</th>
        <th>Privacy-preserving logistic regression and neural networks</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>2/24</th>
        <th rowspan="15">Verifiable Computation, Zero Knowledge Proof and Blockchain</th>
        <th>Introduction to verifiable computation and zero knowledge proof</th>
        <th>
            <a href="https://people.eecs.berkeley.edu/~raluca/cs261-f15/readings/merkle.pdf">Merkle Hash Tree</a>
        </th>
        <th>Proposal due 2/25</th>
    </tr>
    <tr>
        <th>3/1</th>
        <th>Introduction to blockchain and cryptocurrency</th>
        <th>
        <a href="https://bitcoin.org/bitcoin.pdf">Bitcoin</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>3/3</th>
        <th>Pricacy-preserving crypto-currencies</th>
        <th>
            <ul>
            <li><a href="https://cseweb.ucsd.edu/~smeiklejohn/files/imc13.pdf">Inference attacks on Bitcoin</a></li>
            <li><a href="http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf">Zcash</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>3/8</th>
        <th>Customized solutions: RSA accumulators</th>
        <th>
        <a href="https://cs.brown.edu/people/alysyans/papers/camlys02.pdf">RSA Accumulator</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>3/10</th>
        <th>Customized solutions: Bilinear accumulators</th>
        <th>
        <a href="https://eprint.iacr.org/2010/455.pdf">Bilinear Accumulator</a>
        </th>
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
        <th>Midterm project presentation </th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/22</th>
        <th rowspan="2">Generic solutions:SNARK</th>
        <th rowspan="2"><a href="https://eprint.iacr.org/2013/279.pdf">SNARK</a></th>
        <th></th>
    </tr>
    <tr>
        <th>3/24</th>
        <th></th>
    </tr>
    <tr>
        <th>3/29</th>
        <th>Smart contract</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>3/31</th>
        <th>Privacy-preserving smart contract</th>
        <th><a href="https://eprint.iacr.org/2015/675.pdf">Hawk</a></th>
        <th></th>
    </tr>
    <tr>
        <th>4/5</th>
        <th>Security of Bitcoin Cash -- by Yu Shen</th>
        <th><li><a href="https://eprint.iacr.org/2021/143.pdf">The Bitcoin Cash Backbone Protocol</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>4/7</th>
        <th rowspan="3">Generic solutions: interactive proofs</th>
        <th rowspan="3">
            <ul>
                <li><a href="https://link.springer.com/content/pdf/10.1007%2F978-3-642-40084-1_5.pdf">Time-Optimal Interactive Proofs for Circuit Evaluation</a></li>
                <li><a href="https://eprint.iacr.org/2011/587.pdf">Polynomial delegation</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>4/12</th>   
        <th></th>
    </tr>
    <tr>
        <th>4/14</th>
        <th></th>
    </tr>
     <tr>
        <th>4/19</th>
        <th rowspan="3">Final Project Presentations</th>
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
        <th>Final report due 5/2</th>
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
- **Privacy-preserving alternating direction method of multipliers (ADMM)**: apply MPC techniques to train models on encrypted data using ditributed training algorithms (such as ADMM). 1. Understand ADMM. 2. Collect datasets and implement training and predictions on plaintext data. 3. Use only those computations efficiently supported by MPC, compare the accuracy to the baseline. 4. Implement the MPC protocol.

### Zero Knowledge Proof

- **Zero knowledge proof for machine learning model predictions**: generate a proof that the predictions of a secret model on a public testing dataset reaches certain accuracy. Design efficient ZKP protocols for convolution, neural networks and common activation functions.    
- **Contingent payment on blockchain with zero knowledge proof**: design fair exchange protocols on blockchains using zero knowledge proofs.
- **Privacy-preserving smart contracts**: 1. Understand the mechanism of smart contract. 2. Find commonly used smart contracts on existing blockchains and cryptocurrencies. 3. Given general purpose ZKP, design protocols for privacy-preserving smart contracts. 4. Implement the ZKP protocol using existing libraries and optimize for those commonly used smart contracts.

### Blockchains

- **Information inference from public data on Bitcoin blockchain**: 1. Understand the public data posted on the blockchain of Bitcoin and figure out ways to download the data. 2. Repeat data analysis from existing papers. 3. Design new attacks to infer sensitive information from the public data, such as dead coins and large volume transactions and its correlations with the price of bitcoin.
- **Information inference from public data on Ethereum**: Same as bitcoin. In addition, analyze the smart contracts.
- **Scaling up blockchains**: sharding, rollup (optimistim rollup and zk rollup) etc. Understand zk-rollup and its relationship to zero knowledge proofs. Survey existing protocols and challenges.

## Ethics & Academic Integrity Statement and Policy

"An Aggie does not lie, cheat, or steal or tolerate those who do." For additional information, please visit: http://aggiehonor.tamu.edu.  

Upon accepting admission to Texas A&M University, a student immediately assumes a commitment to uphold the Honor Code, to accept responsibility for learning, and to follow the philosophy and rules of the Honor System. Students will be required to state their commitment on examinations, research papers, and other academic work. Ignorance of the rules does not exclude any member of the TAMU community from the requirements or the processes of the Honor System.


