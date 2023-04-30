Download Link: https://assignmentchef.com/product/solved-dynamical-homework-5
<br>
<strong>1.1      Section 3.2 Problem 10.</strong>

From the textbook, we have that there are infinitely integers <em>n </em>such that 2<em><sup>n </sup></em>starts with a 7. By a similar argument, we have that, for <em>d ∈ {</em>1<em>,…,</em>9<em>}</em>, we have,

log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>3        mod 1 <em>&lt; </em>log<sub>10</sub>(<em>d </em>+ 1)

This is the same as saying,

<em>R</em>

Since <em>α </em>= log<sub>10 </sub>3 is irrational, by Theorem 3.2.3 there are infinitely many integers <em>n </em>such that <em>R</em>, and thus there are infinitely many <em>n </em>such that 3<em><sup>n </sup></em>starts with a 7.

Now we want to show that there are infinitely many <em>n </em>such that 2<em><sup>n </sup></em>and 3<em><sup>n </sup></em>both start with a 7.

Observe that if the decimal representation of 2<em><sup>n </sup></em>starts with <em>d ∈ {</em>1<em>,…,</em>9<em>}</em>, then for some integer <em>k ≥ </em>0, we have that,

<em>d × </em>10<em><sup>k </sup>≤ </em>2<em><sup>n </sup>≤ </em>(<em>d </em>+ 1) <em>× </em>10<em><sup>k</sup></em>

<em>⇐⇒ </em>log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>2 (mod 1) <em>&lt; </em>log<sub>10</sub>(<em>d </em>+ 1)                                      (1)

Similarly, if the decimal representation of 3<em><sup>n </sup></em>starts with <em>d ∈ {</em>1<em>,…,</em>9<em>}</em>, then for some integer <em>j ≥ </em>0, we have that,

<em>d × </em>10<em><sup>j </sup>≤ </em>3<em><sup>n </sup>≤ </em>(<em>d </em>+ 1) <em>× </em>10<em><sup>j</sup></em>

<em>⇐⇒ </em>log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>3 (mod 1) <em>&lt; </em>log<sub>10</sub>(<em>d </em>+ 1)                                      (2)

Then adding these two inequalities yields,

<table width="503">

 <tbody>

  <tr>

   <td width="483">2log<sub>10 </sub><em>d ≤ n</em>(log<sub>10 </sub>3 + log<sub>10</sub>(2) (mod 1)) <em>&lt; </em>2log<sub>10</sub>(<em>d </em>+ 1)</td>

   <td width="20">(3)</td>

  </tr>

  <tr>

   <td width="483"><em>⇐⇒ </em>2log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>6 (mod 1) <em>&lt; </em>2log<sub>10</sub>(<em>d </em>+ 1)</td>

   <td width="20">(4)</td>

  </tr>

 </tbody>

</table>

This is the same as saying that, letting <em>α </em>= log<sub>10</sub>(6),

<em>R</em>

Since <em>α </em>= log<sub>10</sub>(6) is irrational, by Theorem 3.2.3 there are infinitely many integers <em>n </em>such that <em>R</em>. But note that, for any <em>n </em>that satisfies (4), it must also satisfy (1) and (2). Otherwise, the addition that we used to yield (3) does not hold. Hence, this is equivalent to saying that are infinitely many integers <em>n </em>such that

<em>R</em> and <em>R</em>, where <em>β </em>= log<sub>10</sub>(2) and <em>γ </em>= log<sub>10</sub>(3). Thus, we have that there are infinitely many integers <em>n </em>such that both 2<em><sup>n </sup></em>and 3<em><sup>n </sup></em>start with 7.

<h2>1.2            Section 3.12</h2>

<strong>Problem 2.</strong>

Let Ω be the subset Σ<sup>+</sup><sub>3 </sub>consisting of all sequences <em>x </em>that do not have the word 010 at any place. Suppose that <em>z </em>is a limit point of Ω that is not contained within the set Ω. That is, since <em>z </em>not in Ω, it has the sequence 010 starting at position <em>k </em>for some <em>k ∈ </em>Z such that <em>k ≥ </em>0. Moreover, since <em>z </em>is a limit point of Ω, there is a sequence (<em>x<sub>n</sub></em>) <em>∈ </em>Ω such that for every <em> &gt; </em>0, there exists <em>N &gt; </em>0 such that <em>d</em>(<em>x<sub>N</sub>,z</em>) <em>&lt; </em>. However, note that every element <em>x<sub>j </sub></em>in the above sequence does not have the sequence 010. Thus, for any <em>j &gt; </em>0, we have that,

<em>d</em>(<em>x<sub>j</sub>,z</em>) <em>≥ </em>2<em><sup>−k</sup></em>

Hence, for any <em>n ∈ </em>N and any <em> &lt; </em>2<em><sup>−k</sup></em>, we have,

<em>d</em>(<em>x<sub>n</sub>,z</em>) <em>≥ </em>2<em><sup>k </sup>&gt; </em>

Thus, we have a contradiction and so <em>z </em>must be contained in Ω. Since <em>z </em>was an arbitrary limit point of the set, we must have that Ω contains all its limit points and is thus closed.

<h2>1.3            Section 3.13</h2>

<strong>Problem 1.</strong>

Note that alternative definition for density of a set <em>D</em> is that, for every non-empty open set <em>U </em>, we have <em>D ∩ U 6</em>= <em>∅</em>.

For a point <em>x</em> to be periodic, it must be the repetition for some block of symbols in <em>{</em>1<em>,··· ,N −</em>1<em>}</em>. That is, there is some <em>n </em><em><sup>∈ </sup></em>N such that <em>x</em><sub>[0<em>,n−</em>1] </sub>= <em>x</em><sub>[<em>n,</em>2<em>n−</em>1] </sub>= <em>x</em><sub>[2<em>n,</em>3<em>n−</em>1] </sub>= <em>···</em>.

Now fix <em>y</em> and fix <em> &gt; </em>0. Then consider the set,

<em>B   </em><em>&lt; </em>

So for every <em>z </em>, we have <em>d</em>(<em>z,y</em>) = 1<em>/</em>2<sup>min<em>{i≥</em>0:<em>z</em></sup><em><sup>i6</sup></em><sup>=<em>y</em></sup><em><sup>i} </sup>&lt; </em>

Now let <em>k ∈ </em>N be the smallest natural number such that 1<em>/</em>2<sup>min<em>{i≥</em>0:<em>x</em></sup><em><sup>i6</sup></em><sup>=<em>y</em></sup><em><sup>i} </sup>&lt; </em>. Then define the block <em>y</em><sub>[0<em>,k−</em>1] </sub>using elements of <em>y</em>. Next, define <em>x<sub>k </sub></em>= <em>y<sub>k </sub></em>+ 1 mod <em>N</em>. Let <em>x<sub>y </sub></em>=

(<em>y</em>[0<em>,k−</em>1]<em>x</em><em>ky</em>[0<em>,k−</em>1]<em>x</em><em>ky</em>[0<em>,k−</em>1]<em>x</em><em>k ···</em>) = (<em>y</em>0<em>y</em>1 <em>···y</em><em>k−</em>1<em>x</em><em>ky</em>0<em>y</em>1 <em>···y</em><em>k−</em>1<em>x</em><em>k ···</em>). Clearly we have,

<em>d</em>(<em>x<sub>y</sub>,y</em>) = 1<em>/</em>2<em><sup>k </sup>&lt; </em>

Moreover, we have that <em>x</em>[0<em>,k</em>] = <em>x</em>[<em>k</em>+1<em>,</em>2<em>k</em>+1] = <em>x</em>[2<em>k</em>+2<em>,</em>3<em>k</em>+2] = <em>···</em>. So we have that,

<em>σ<sup>k</sup></em><sup>+1</sup>(<em>x</em>) = <em>x</em>

Hence, <em>x </em>is a periodic point with period <em>k </em>+ 1.

Since <em> &gt; </em>0 and <em>y </em> were arbitrary, this holds for any <em>y </em> with any choice of <em> &gt; </em>0. Hence, we have that the set of periodic points of <em>σ </em>intersects every non-empty open subset of Σ<sup>+</sup><em><sub>N</sub></em>, and so the periodic points of <em>σ </em>are dense in Σ<sup>+</sup><em><sub>N</sub></em>.

<strong>Problem 3.</strong>

First, let us show that <em>τ </em>is continuous. That is, we want to show that for each <em>x</em>, we have that for all <em> &gt; </em>0, there exists <em>δ &gt; </em>0 such that <em>d</em>(<em>τ</em>(<em>x</em>)<em>,τ</em>(<em>y</em>)) <em>&lt;  </em>whenever <em>y </em>

and <em>d</em>(<em>x,y</em>) <em>&lt; δ</em>. First let us fix <em>x</em> and <em> &gt; </em>0. Let <em>δ </em>= . Then for any <em>y</em> with <em>d</em>(<em>x,y</em>) <em>&lt; δ</em>, we have that the first position where <em>x 6</em>= <em>y </em>is <em>k </em>such that 1<em>/</em>2<em><sup>k </sup>&lt; δ </em>= . Now let us consider <em>τ</em>(<em>x</em>) and <em>τ</em>(<em>y</em>). Since the first <em>k − </em>1 terms in <em>x </em>and <em>y </em>are the same, the modulo addition and carrying over process must be exactly the same on these <em>k − </em>1 terms. Hence, we have that <em>d</em>(<em>τ</em>(<em>x</em>)<em>,τ</em>(<em>y</em>)) <em>&lt; </em>1<em>/</em>2<em><sup>k </sup>&lt; </em>

Hence, since <em>x </em>and <em> </em>were arbitrary and <em>y </em>was an arbitrary point with distance less than <em>δ </em>from <em>x</em>, we have that <em>τ </em>is continuous.

Recall that <em> → </em> is minimal if the positive orbit <em>{τ<sup>n</sup></em>(<em>x</em>)<em>}<sub>n≥</sub></em><sub>0 </sub>is dense in Σ<sup>+</sup><em><sub>N </sub></em>for all <em>x </em>. Let us fix <em>x</em> and consider some arbitrary <em>y</em> such that <em>y 6</em>= <em>x</em>. Then there exists some <em>k ∈ </em>Z such that <em>k ≥ </em>0 and <em>x<sub>k </sub>6</em>= <em>y<sub>k</sub></em>. Now fix some <em> &gt; </em>0 and consider the set,

<em>B   </em><em>&lt; </em>

So for every <em>z </em>, we have <em>d</em>(<em>z,y</em>) = 1<em>/</em>2<sup>min<em>{i≥</em>0:<em>z</em></sup><em><sup>i6</sup></em><sup>=<em>y</em></sup><em><sup>i} </sup>&lt; </em>. If we fix <em>j </em>to be the smallest integer such that 1<em>/</em>2<em><sup>j </sup>&lt; </em>, then we need to apply <em>τ </em>enough times until the distance between <em>y </em>and the iterated image of <em>x </em>is 1<em>/</em>2<em><sup>j</sup></em>. That is, the first difference between <em>y </em>and the iterated image of <em>x </em>must be at position <em>j</em>.

Observe that, since the addition is modulo <em>N</em>, the first digit <em>x</em><sub>0 </sub>is periodic with period <em>N</em>. The second digit <em>x</em><sub>1 </sub>is periodic with period <em>N</em><sup>2</sup>, and so on. Hence, let us apply <em>τ </em>until <em>x</em><sub>0 </sub>= <em>y</em><sub>0 </sub>and then fix that “cycle” around that point. Next let us, apply <em>τ </em>until <em>x</em><sub>1 </sub>= <em>y</em><sub>1 </sub>and cycle around <em>x</em><sub>0</sub><em>x</em><sub>1</sub>. Let us continue this process until we have that <em>x<sub>j </sub></em>= <em>y<sub>j </sub></em>and cycle until <em>x</em><sub>0</sub><em>x</em><sub>1 </sub><em>···x<sub>j−</sub></em><sub>1 </sub>= <em>y</em><sub>0</sub><em>y</em><sub>1 </sub><em>···y<sub>j−</sub></em><sub>1 </sub>as well. Then we have that,

<em>d</em>(<em>τ<sup>m</sup></em>(<em>x</em>)<em>,y</em>) <em>&lt; </em>1<em>/</em>2<em><sup>j </sup>&lt; </em>

for some <em>m ∈ </em>N. Hence, the forward orbit of <em>x </em>is dense in Σ<sup>+</sup><em><sub>N</sub></em>. Since <em>x </em>was arbitrary, this hold for every <em>x</em> and so <em>τ </em>is minimal.