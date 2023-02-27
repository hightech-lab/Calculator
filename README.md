# Calculator Project By C#



<h1 align="center">Semi Advance "Calculator App"<br></h1>
<p align="center">
<img src="https://i.ibb.co/6wj7kbN/Untitled.png" alt="img" width="280" height="300" />
</p>

<p align="center">
This is my first C# project for your knowledge. Created by : <a href="https://github.com/hightech-lab" target="_blank">High Tech Lab</a> using <a href="https://visualstudio.microsoft.com/" target="_blank">Visual Studio 2012 Ultimate</a> and Dont forget to give a star bro.
</p>

<p align="center">
Big thanks❤️ to Esoft Metro Campus Panadura
</p>

---

<p align="center">
<a href="Coming Soon"><img title="Size" src="https://img.shields.io/badge/Tutorial-Video-green"></a>
</p>

------

# ```Project Info```
<p align="center">
<a href="https://github.com/hightech-lab/followers"><img title="Followers" src="https://img.shields.io/github/followers/hightech-lab?color=red&style=flat-square"></a>
<a href="https://github.com/hightech-lab/Calculator/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/hightech-lab/Calculator?color=blue&style=flat-square"></a>
<a href="https://github.com/hightech-lab/Calculator/network/members"><img title="Forks" src="https://img.shields.io/github/forks/hightech-lab/Calculator?color=red&style=flat-square"></a>
<a href="https://github.com/hightech-lab/Calculator/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/hightech-lab/Calculator?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/hightech-lab/Calculator"><img title="Open Source" src="https://img.shields.io/badge/Author-High%20Tech%20Lab.-red?v=103"></a>
<a href="https://github.com/hightech-lab/Calculator/"><img title="Size" src="https://img.shields.io/github/repo-size/hightech-lab/Calculator?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhightech-lab%2FCalculator6&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/hightech-lab/Calculator/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>
<p align='center'>
    </p>

-------

## ```Connect With Me```
<p align="center">
<a href="https://wa.me/94753420144"><img src="https://img.shields.io/badge/Contact High Tech Lab-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="https://chat.whatsapp.com/Ebm27fhLdubKvI0OnNentO"><img src="https://img.shields.io/badge/Join Official Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="https://youtube.com/@hightechlab2022"><img src="https://img.shields.io/badge/Subscribe High Tech Lab-ff0000?style=for-the-badge&logo=youtube&logoColor=ff000000&link=https://youtube.com/@DGXeon" /><br>
</p>

## `How To Set Up Zero Button`
``` {
            if (TxtBox.Text == "0")
            {
                TxtBox.Text = "0";
            }
            else
            {
                TxtBox.Text += "0";
            }
        }
```
## `How To Set Up Equal Mark`
``` {
            switch (operators)
            {
                case "-":
                    valueSecond = decimal.Parse(TxtBox.Text);
                    Result = valueFirst - valueSecond;
                    TxtBox.Text = Result.ToString();
                    break;
                case "+":
                    valueSecond = decimal.Parse(TxtBox.Text);
                    Result = valueFirst + valueSecond;
                    TxtBox.Text = Result.ToString();
                    break;
                case "*":
                    valueSecond = decimal.Parse(TxtBox.Text);
                    Result = valueFirst * valueSecond;
                    TxtBox.Text = Result.ToString();
                    break;
                case "/":
                    valueSecond = decimal.Parse(TxtBox.Text);
                    Result = valueFirst / valueSecond;
                    TxtBox.Text = Result.ToString();
                    break;
                case "%":
                    valueSecond = decimal.Parse(TxtBox.Text);
                    Result = valueFirst % valueSecond;
                    TxtBox.Text = Result.ToString();
                    break;
            }
        
        }
```
## `How To Set Up Dot`
``` {
            if (!TxtBox.Text.Contains("."))
            {
                TxtBox.Text += ".";
            }
        }
```
## `How To Set Up Numbers`
```  private void OneBtn_Click(object sender, EventArgs e)
        {
            if (TxtBox.Text == "0")
            {
                TxtBox.Text = "1";
            }
            else
            {
                TxtBox.Text += "1";
            }
        }

        private void TwoBtn_Click(object sender, EventArgs e)
        {
            if (TxtBox.Text == "0")
            {
                TxtBox.Text = "2";
            }
            else
            {
                TxtBox.Text += "2";
            }
        }
```
## `How To Set Up Clear Button`
```  {
            valueFirst = 0.0m;
            valueSecond = 0.0m;
            TxtBox.Text = "0";
        }
```
## `How To Set Up Minus Button`
```{
            valueFirst = decimal.Parse(TxtBox.Text);
            TxtBox.Clear();
            operators = "-";
        }
```
## `How To Set Up Plus Button`
``` {
            valueFirst = decimal.Parse(TxtBox.Text);
            TxtBox.Clear();
            operators = "+";
        }
```
## `How To Set Up Devide Button`
``` {
            valueFirst = decimal.Parse(TxtBox.Text);
            TxtBox.Clear();
            operators = "/";
        }
```
## `How To Set Up Multiply Button`
```  {
            valueFirst = decimal.Parse(TxtBox.Text);
            TxtBox.Clear();
            operators = "*";
        }
```
## `How To Set Up MinusPlus Button`
``` {
            if (TxtBox.Text.Contains("-"))
            {
                TxtBox.Text = TxtBox.Text.Trim('-');
            }
            else
            {
                TxtBox.Text = "-" + TxtBox.Text;
            }
        }
```
## `How To Set Up Module Button`
```{
            valueFirst = decimal.Parse(TxtBox.Text);
            TxtBox.Clear();
            operators = "%";
        }
```
-----
## Thank You...! Dont forget to give a star bro ⭐.

💻 Tutorial Video Coming Soon. Expect the YouTube video soon.
We are not responsible for errors that occur when you try the programs here. Be patient until the tutorial video is released.
If necessary, try alone and make your project successful with this. Thank you.
Let us know if there are any errors in the programming here.
Thank you...!

💻 Tutorial Video Coming Soon. YouTube වීඩියෝව ලගදීම බලාපොරොත්තු වන්න.
මෙහි ක්‍රමලේඛන ඔබ අත් හදා බැලීමේදි සිදු වන Errors වලට වගකියනු නොලැබේ. මන්ද Tutorial Video එක නිකුත් කරන තුරු ඉවසන්න.
අවශ්‍ය නම් තනිව උත්සහ කොට ඔබගේ Project එක මෙයින් සාර්ථක කර ගන්න ස්තූති.
මෙහි ක්‍රමලේඛණ වල යම් දෝෂ ඇතොත් අපව දැනුවත් කරන්න.
ස්තූති...!
-----
