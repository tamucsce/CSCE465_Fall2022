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

<table style="width: 100%">
    <tr>
        <th style="width: 5%;">Date</th>
      <th style="width: 10%;">Sections</th>
      <th style="width: 40%;">Topic & slides</th>
      <th style="width: 45%;">Readings</th>
      <th style="width: 20%;">Deadlines</th>
    </tr>
    <tr>
        <th>8/27</th>
        <th>Introduction</th>
        <th>Introduction and logitics
        <a href="https://drive.google.com/file/d/1HiljvmS8NvDTvhAOPo2pvuBgaL4gsLFG/view?usp=sharing">(Slides)</a>
        </th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>8/29</th>
        <th rowspan="5">Secure Multiparty Computation and Privacy-Preserving Machine learning</th>
        <th>Introduction to secure multiparty computation and Yao's Garbled circuit <a href="https://drive.google.com/file/d/1trzqA6NTaTmFOI9uTNOSzqqHkrnQSJYS/view?usp=sharing">(Slides)</a></th>
        <th>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=GjhvJxelIVQ">Yao's Garbled Circuit</a></li>
            <li><a href="https://www.iacr.org/archive/eurocrypt2015/90560204/90560204.pdf"> Half Gates</a></li>
          </ul>        
        </th>
        <th></th>
    </tr>
    <tr>
        <th>9/3</th>
        <th>GMW protocol <a href="https://drive.google.com/file/d/13s3_bEbFSw2kFvEONg29qEmnK7P825o9/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://www.youtube.com/watch?v=4YwvZaA9IEg">GMW protocol</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>9/5</th>     
        <th>Malicious security and fairness <a href="https://drive.google.com/file/d/1LJzZfzekNV8ZjXl7HeiUfp5O2s_D7Jbv/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2008/049.pdf">Cut and choose</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>9/10</th>
        <th>Privacy-preserving linear regression  <a href="https://drive.google.com/file/d/1tR6o-6PUuhkJpkwHxrCt7yEJe5EaBWix/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2017/396.pdf">SecureML</a></li></th>
        <th>Team Formation</th>
    </tr>
    <tr>
        <th>9/12</th>
        <th>Privacy-preserving logistic regression and neural networks <a href="https://drive.google.com/file/d/1T0ZwuKZVTlv2UdWB8L_ist-goJd2yV7p/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://encrypto.de/papers/DSZ15.pdf">ABY framework</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>9/17</th>
        <th rowspan="8">Searchable Encryptions</th>
        <th>Introduction to searchable encryption <a href="https://drive.google.com/file/d/1nSK9XpXYarH9NrTnJSK-lN6ubxkT7vQS/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2006/210.pdf">Searchable Symmetric Encryption</th>
        <th></th>
    </tr>
    <tr>
        <th>9/19</th>
        <th>Dynamic searchable encryption <a href="https://drive.google.com/file/d/1Bny__LTjQczr1KzoziBO2MAoC-W5kXVv/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2012/530.pdf">Dynamic searchable encryption</th>
        <th></th>
    </tr>
    <tr>
        <th>9/24</th>
        <th rowspan="4">No class due to travel</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th >9/26</th>
        <th></th>
        <th >project proposal due</th>
    </tr>
    <tr></tr>
    <tr></tr>
    <tr>
        <th>10/1</th>
        <th>Forward and backward security <a href="https://drive.google.com/file/d/1knDspu2KrWfAyweYlihX6S__RlDSrcVQ/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2013/832.pdf">Dynamic SSE with forward security</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>10/3</th>
        <th>Attacks to searchable encrytion <a href="https://drive.google.com/file/d/1aO5xcwpiiKdsuY7B_l5qPEGssBOgKEMe/view?usp=sharing">(Slides)</a></th>
        <th>
            <li><a href="https://www.ndss-symposium.org/wp-content/uploads/2017/09/06_1.pdf">Inference Attack</a></li>
            <li><a href="https://eprint.iacr.org/2016/718.pdf">Leakage Abuse Attack</a></li>
            <li><a href="https://eprint.iacr.org/2016/172.pdf">File Injection Attack</a></li>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>10/8</th>
        <th rowspan="12">Verifiable Computation, Zero Knowledge Proof and Blockchain</th>
        <th>Introduction to verifiable computation and zero knowledge proof <a href="https://drive.google.com/file/d/1C9f7DbPvlTGPtDfDUNgBsULeZBOToGsS/view?usp=sharing">(Slides)</a></th>
        <th>
            <li><a href="https://people.eecs.berkeley.edu/~raluca/cs261-f15/readings/merkle.pdf">Merkle Hash Tree</a></li>
        </th>   
        <th></th>
    </tr>
    <tr>
        <th>10/10</th>
        <th>Customized solutions: RSA accumulator <a href="https://drive.google.com/file/d/14EWsD5CfsWwtPRccqjlNeNBDnlDCxW4M/view?usp=sharing">(Slides)</a></th>
        <th>
            <li><a href="https://cs.brown.edu/people/alysyans/papers/camlys02.pdf">RSA Accumulator</a></li>
            <li><a href="https://user.eng.umd.edu/~cpap/published/cpap-rt-nikos-08.pdf">Authenticated Hash Tables</a></li>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>10/15</th>
        <th>Customized solutions: Bilinear accumulator <a href="https://drive.google.com/file/d/16SUBTkup7b_1yBc09K7Vr2O2jY5t6E_6/view?usp=sharing">(Slides)</a></th>
        <th>
            <li><a href="https://eprint.iacr.org/2010/455.pdf">Bilinear Accumulator</a></li>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>10/17</th>
        <th rowspan="2">Generic solutions:SNARK <a href="https://drive.google.com/file/d/1_Hp99zYupcEPJ0UWQOyk4FIpFg-7grBm/view?usp=sharing">(Slides 1)</a> <a href="https://drive.google.com/file/d/16B6N5o8-PwKgu3eVHs0TIrnKRCgVcgou/view?usp=sharing">(Slides 2)</a></th>
        <th rowspan="2"> 
            <li><a href="https://eprint.iacr.org/2013/279.pdf">SNARK</a></li>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>10/22</th>
        <th></th>
    </tr>
    <tr>
        <th>10/24</th>
        <th>Introduction to blockchain, cryptocurrency and smart contract <a href="https://drive.google.com/file/d/1oyMfwKpcegzXqtJRWBlthhTLUJ_3uk1m/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://bitcoin.org/bitcoin.pdf">Bitcoin</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>10/29</th>
        <th>Midterm project presentation</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>10/31</th>
        <th>Pricacy-preserving crypto-currencies <a href="https://drive.google.com/file/d/18uDvDpP9skpRwyR_s-l4SCQehG68Q9xD/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf">Zcash</a></li></th>
        <th>Progress Report Due</th>
    </tr>
    <tr>
        <th>11/5</th>
        <th>Privacy-preserving smart contract <a href="https://drive.google.com/file/d/1D6kharNcLjjcBn6E6BpXvzwphpNxogna/view?usp=sharing">(Slides)</a></th>
        <th><li><a href="https://eprint.iacr.org/2015/675.pdf">Hawk</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>11/7</th>
        <th rowspan="3">Generic solutions: interactive proof
        <a href="https://drive.google.com/file/d/1fRzExfJuSwB5vUPtOtRK07rApsadKA-7/view?usp=sharing">(Slides 1 sumcheck)</a>
            <a href="https://drive.google.com/file/d/1NIg9XJEQ74cjD1kUXLBbsp1oglZ1EtKj/view?usp=sharing">(Slides 2 GKR)</a>
            <a href="https://drive.google.com/file/d/1KTy4fkmtiTT4OZg0GhFMGVeiiZ9FiKY4/view?usp=sharing">(Slides 3 Polynomial commitment)</a>
        </th>
        <th rowspan="2"><li><a href="https://eprint.iacr.org/2013/351.pdf">Time-Optimal Interactive Proofs for Circuit Evaluation</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>11/12</th>
        <th></th>
    </tr>
    <tr>
        <th>11/14</th>
        <th><li><a href="https://eprint.iacr.org/2011/587.pdf">Polynomial delegation</a></li></th>    
        <th></th>
    </tr>  
    <tr>
        <th>11/19</th>
        <th rowspan="5">Project Presentations</th>
        <th></th>
        <th></th>
        <th></th>
    </tr>
      <tr>
        <th>11/21</th>
        <th></th>
        <th></th>
        <th></th>
    </tr> 
    <tr>
        <th>11/26</th>
        <th></th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>11/28</th>
        <th>No class, Thanksgiving</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>12/3</th>
        <th></th>
        <th></th>
        <th>Final report due</th>
    </tr>
</table>

## Grading
**Reading assignments:** 35%. Students will submit reviews for one of the reading materials every week.
**Course project:** 65%. Students will form groups and complete research projects related to the topics of the course.

## Links

**Assignments and Gradebook:** http://ecampus.tamu.edu/

## Suggested topics for projects:

## Ethics & Academic Integrity Statement and Policy

"An Aggie does not lie, cheat, or steal or tolerate those who do." For additional information, please visit: http://aggiehonor.tamu.edu.  

Upon accepting admission to Texas A&M University, a student immediately assumes a commitment to uphold the Honor Code, to accept responsibility for learning, and to follow the philosophy and rules of the Honor System. Students will be required to state their commitment on examinations, research papers, and other academic work. Ignorance of the rules does not exclude any member of the TAMU community from the requirements or the processes of the Honor System.


