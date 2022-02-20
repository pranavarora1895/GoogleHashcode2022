# Google Hashcode 2022 - One Pizza ![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## Problem Statement
<p align="center">
  <img src="https://codejam.googleapis.com/dashboard/get_file/AQj_6U1YZSyNV0Y-_gPyr-2DCkdjytZqr_v1Att7bbxMSvZVYh_qWBQhhLGSENw/pizzeria.gif" width="350" title="pizza">
</p>

<p>
  
  You are opening a small pizzeria. In fact, your pizzeria is so small that you decided to offer only one type of pizza. Now you need to decide what ingredients to include (peppers? tomatoes? both?).

Everyone has their own pizza preferences. Each of your potential clients has some ingredients they like, and maybe some ingredients they dislike. Each client will come to your pizzeria if both conditions are true:

 <ul>
   <li> all the ingredients they like are on the pizza, and</li>
   <li> none of the ingredients they dislike are on the pizza</li>
  </ul>
Each client is OK with additional ingredients they neither like or dislike being present on the pizza. Your task is to choose which ingredients to put on your only pizza type, to maximize the number of clients that will visit your pizzeria.

Input
<ul>
  <li>The first line contains one integer 1≤C≤10^5 - the number of potential clients.</li>
<li>The following 2×C lines describe the clients’ preferences in the following format:</li>
  <ol>
<li>First line contains integer 1≤L≤5, followed by L names of ingredients a client likes, delimited by spaces.</li>
<li>Second line contains integer 0≤D≤5, followed by D names of ingredients a client dislikes, delimited by spaces.</li>
  </ul>
Each ingredient name consists of between 1 and 15 ASCII characters. Each character is one of the lowercase letters (a-z) or a digit (0-9).
  
  </p>
  
  <h2>Submission</h2>
  <p> The submission should consist of one line consisting of a single number 0≤N followed by a list of N ingredients to put on the only pizza available in the pizzeria, separated by spaces. The list of ingredients should contain only the ingredients mentioned by at least one client, without duplicates. </p>
  
  <h2>Scoring</h2>
  <p>A solution scores one point for each client that will come to your pizzeria. A client will come to your pizzeria if **all the ingredients they like** are on the pizza and **none of the ingredients they dislike** are on the pizza.</p>
  
  <h2>Sample</h2>
  
 **Sample Input**
  
  ```
  3
2 cheese peppers
0
1 basil
1 pineapple
2 mushrooms tomatoes
1 basil
  ```
  
  **Sample Output**
  
  ```
  4 cheese mushrooms tomatoes peppers
  ```
  
  <p>
 
  _**In the Sample Input there are 3 potential clients:**_

- The first client likes 2 ingredients, cheese and peppers, and does not dislike anything.
- The second client likes only basil and dislikes only pineapple.
- The third client likes mushrooms and tomatoes and dislikes only basil
  
  _**In this particular Sample Output, we choose to use 4 ingredients in the pizza: cheese, mushrooms, tomatoes, and peppers.**_
  
- The first client likes the pizza because it contains both cheese and peppers, which they like.
- The second client does not like the pizza: it does not contain basil which they like.
- The third client likes the pizza because it contains mushrooms and tomatoes, which they like, and does not contain basil which they do not like.

  This means a submission of this output would score 2 points for this case, because two clients (the first and third ones) would like this pizza.
  </p>
  
  ## Solution
  
  The solution is given in the attached [Jupyter Notebook](https://github.com/pranavarora1895/GoogleHashcode2022/blob/main/PractisePizza.ipynb). The scores on the different test cases were as follows:
  
  - A - An Example => 2
  - B - Basic => 5
  - C - Coarse => 1
  - D - Difficult => 1420
  - E - Elaborate => 412
  - T - Total => 1840

---

* Follow Me On Instagram at [Pranav Arora](https://www.instagram.com/arorapranav187)
* Lets Get Connected on Linkedin at [Pranav Arora](https://www.linkedin.com/in/pranav-arora-354b71bb/)


### ThankYou!
