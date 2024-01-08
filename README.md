***Author: Julen Ferro 🚗***

# ***_Statistical Learning_*** 🛠️

This repository contains the Homework assignments and experiments carried out for the MATH 569 Statistical Learning subject, at Illinois Institute of Technology for the Master´s degree in Computational Decision Science & Operations Research.

This subject provides its students with a solid understanding on Advanced Mathematical concepts to be used on the Machine Learning/Deep Learning fields:

📁 ***_HOMEWORK 1:_***

asg

📁 ***_HOMEWORK 2:_***

S

📁 ***_HOMEWORK 3:_***

s
📁 ***_HOMEWORK 4:_***

sd
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mtable displaystyle="true" columnalign="right left" columnspacing="0em" rowspacing="3pt">
    <mtr>
      <mtd>
        <msub>
          <mi>b</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </msub>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <msub>
            <mi>x</mi>
            <mrow data-mjx-texclass="ORD">
              <mn>0</mn>
            </mrow>
          </msub>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
      </mtd>
      <mtd>
        <mi></mi>
        <mo>=</mo>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
            <mo>=</mo>
            <mn>1</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>N</mi>
          </mrow>
        </munderover>
        <msup>
          <mrow data-mjx-texclass="INNER">
            <mo data-mjx-texclass="OPEN">(</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mi>i</mi>
              </mrow>
            </msub>
            <mo>&#x2212;</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo data-mjx-texclass="CLOSE">)</mo>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </msup>
        <msub>
          <mi>l</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
          </mrow>
        </msub>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <msub>
            <mi>x</mi>
            <mrow data-mjx-texclass="ORD">
              <mn>0</mn>
            </mrow>
          </msub>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
      </mtd>
    </mtr>
    <mtr>
      <mtd></mtd>
      <mtd>
        <mi></mi>
        <mo>=</mo>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
            <mo>=</mo>
            <mn>1</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>N</mi>
          </mrow>
        </munderover>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
            <mo>=</mo>
            <mn>0</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </munderover>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <mtable columnspacing="1em" rowspacing="4pt">
            <mtr>
              <mtd>
                <mi>j</mi>
              </mtd>
            </mtr>
            <mtr>
              <mtd>
                <mi>k</mi>
              </mtd>
            </mtr>
          </mtable>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
        <msubsup>
          <mi>x</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
          </mrow>
        </msubsup>
        <msup>
          <mrow data-mjx-texclass="INNER">
            <mo data-mjx-texclass="OPEN">(</mo>
            <mo>&#x2212;</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo data-mjx-texclass="CLOSE">)</mo>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
            <mo>&#x2212;</mo>
            <mi>k</mi>
          </mrow>
        </msup>
        <msub>
          <mi>l</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
          </mrow>
        </msub>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <msub>
            <mi>x</mi>
            <mrow data-mjx-texclass="ORD">
              <mn>0</mn>
            </mrow>
          </msub>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
      </mtd>
    </mtr>
    <mtr>
      <mtd></mtd>
      <mtd>
        <mi></mi>
        <mo>=</mo>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
            <mo>=</mo>
            <mn>0</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </munderover>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <mtable columnspacing="1em" rowspacing="4pt">
            <mtr>
              <mtd>
                <mi>j</mi>
              </mtd>
            </mtr>
            <mtr>
              <mtd>
                <mi>k</mi>
              </mtd>
            </mtr>
          </mtable>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
        <msup>
          <mrow data-mjx-texclass="INNER">
            <mo data-mjx-texclass="OPEN">(</mo>
            <mo>&#x2212;</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo data-mjx-texclass="CLOSE">)</mo>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
            <mo>&#x2212;</mo>
            <mi>k</mi>
          </mrow>
        </msup>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
            <mo>=</mo>
            <mn>1</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>N</mi>
          </mrow>
        </munderover>
        <msubsup>
          <mi>x</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
          </mrow>
        </msubsup>
        <msub>
          <mi>l</mi>
          <mrow data-mjx-texclass="ORD">
            <mi>i</mi>
          </mrow>
        </msub>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <msub>
            <mi>x</mi>
            <mrow data-mjx-texclass="ORD">
              <mn>0</mn>
            </mrow>
          </msub>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
      </mtd>
    </mtr>
    <mtr>
      <mtd></mtd>
      <mtd>
        <mi></mi>
        <mo>=</mo>
        <munderover>
          <mo data-mjx-texclass="OP">&#x2211;</mo>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
            <mo>=</mo>
            <mn>0</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </munderover>
        <mrow data-mjx-texclass="INNER">
          <mo data-mjx-texclass="OPEN">(</mo>
          <mtable columnspacing="1em" rowspacing="4pt">
            <mtr>
              <mtd>
                <mi>j</mi>
              </mtd>
            </mtr>
            <mtr>
              <mtd>
                <mi>k</mi>
              </mtd>
            </mtr>
          </mtable>
          <mo data-mjx-texclass="CLOSE">)</mo>
        </mrow>
        <msup>
          <mrow data-mjx-texclass="INNER">
            <mo data-mjx-texclass="OPEN">(</mo>
            <mo>&#x2212;</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo data-mjx-texclass="CLOSE">)</mo>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
            <mo>&#x2212;</mo>
            <mi>k</mi>
          </mrow>
        </msup>
        <msubsup>
          <mi>x</mi>
          <mrow data-mjx-texclass="ORD">
            <mn>0</mn>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>k</mi>
          </mrow>
        </msubsup>
        <mo>=</mo>
        <msup>
          <mrow data-mjx-texclass="INNER">
            <mo data-mjx-texclass="OPEN">(</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo>&#x2212;</mo>
            <msub>
              <mi>x</mi>
              <mrow data-mjx-texclass="ORD">
                <mn>0</mn>
              </mrow>
            </msub>
            <mo data-mjx-texclass="CLOSE">)</mo>
          </mrow>
          <mrow data-mjx-texclass="ORD">
            <mi>j</mi>
          </mrow>
        </msup>
        <mo>=</mo>
        <mn>0</mn>
        <mo>.</mo>
      </mtd>
    </mtr>
  </mtable>
</math>

📁
***_HOMEWORK 5:_***

asdg
