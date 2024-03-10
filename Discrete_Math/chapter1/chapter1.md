# 1-1,1-2
## (1)
**指出下列语句哪些是命题,哪些不是命题,如果是命题,请指出它的真值**
### (a)
**离散数学是计算机科学系的一门必修课**

是命题。$T$
### (b)
**计算机有空吗？**

不是命题。
### (c)
**明天我去看电影**

不是命题。
### (d)
**请勿随地吐痰！**

不是命题
### (e)
**不存在最大质数**

是命题。$T$
### (f)
**如果我掌握了英语、法语，那么学习其他欧洲语言就容易得多**

是命题。$T$
### (g)
$9+5\leq12$

是命题。$F$
### (h)
$x=3$

不是命题。
### (i)
**我们要努力学习**

不是命题
## (3)
$$\bf 假设P表示命题“天下雪”$$
$$\bf Q表示命题“我将去镇上”$$
$$\bf R表示命题“我有时间”$$
**以符号形式写出下列命题**
### (a)
**如果天不下雪和我有时间,那么我将去镇上**
$$\neg{P}\wedge{R}\rightarrow{Q}$$
### (b)
**我将去镇上，仅当我有时间时**
$$Q\rightarrow{R}$$
### (c)
**天不下雪**
$$\neg{P}$$
### (d)
**天下雪,那么我不去镇上**
$$P\rightarrow\neg{Q}$$
## (5)
**将下列命题符号化**
### (a)
**王强身体很好,成绩也很好**

**设**:命题$B$表示王强身体很好,命题$G$表示王强成绩很好
$$B\wedge{G}$$
### (c)
**气候很好或很热**

**设**:命题$G$表示气候很好,命题$H$表示气候很热
$$(G\wedge\neg{H})\vee(\neg{G}\wedge{H})$$
### (e)
**四边形$ABCD$是平行四边形,当且仅当它的对边平行**

**设**:命题$S$表示四边形$ABCD$是平行四边形,命题$P$表示四边形$ABCD$的对边平行
$$S\leftrightarrow{P}$$
## (6)
**将下列复合命题分成若干原子命题**
### (b)
**天气炎热但湿度较小**

命题$T$表示天气炎热\
命题$W$表示湿度较小
### (d)
**刘英与李进上山**

命题$Y$表示刘英上山\
命题$J$表示李进上山
### (f)
**如果你不看电影,那么我也不看电影**

命题$Y$表示你看电影\
命题$M$表示我看电影
### (h)
**控制台打字机既可作为输入设备,又可作为输出设备**

命题$I$表示控制台打字机可作为输入设备\
命题$O$表示控制台打字机可作为输出设备
# 1-3
## (5)
**试把原子命题表示为$P,Q,R$等,然后用符号译出下列句子**
### (a)
**或者你没有给我写信,或者它在中途丢失了**

**设**:命题$P$表示你给我写信\
命题$Q$表示信在途中丢失了
$$(\neg{P}\wedge\neg{Q})\vee(P\wedge{Q})$$
### (b)
**如果张三李四都不去,他就去**

**设**:命题$P$表示张三去\
命题$Q$表示李四去\
命题$R$表示他去
$$(\neg{P}\wedge\neg{Q})\rightarrow{R}$$
### (c)
**我们不能既划船又跑步**

**设**:命题$P$表示我们划船\
命题$Q$表示我们跑步
$$(\neg{P}\wedge{Q})\vee(P\wedge\neg{Q})\vee(\neg{P}\wedge\neg{Q})$$
### (d)
**如果你来了,那么他唱不唱歌将由你是否伴奏而定**

**设**:命题$P$表示你来了\
命题$Q$表示他唱歌\
命题$R$表示你伴奏
$$P\rightarrow(R\leftrightarrow{Q})$$
## (6)
**一个人起初说，“占据空间的、有质量的而且不断变化的叫做物质”；后来他改说，“占据空间的有质量的叫做物质，而物质是不断变化的。”问他前后主张的差异在什么地方。试以命题形式进行分析**

**设**：命题$S$表示占据空间\
命题$Q$表示有质量\
命题$C$表示不断变化\
命题$M$表示是物质

**则这个人前面的主张用符号化表达是**
$$(S\wedge{Q}\wedge{C})\rightarrow{M}$$
**他后面的主张可以表示为**
$$((S\wedge{Q})\rightarrow{M})\wedge(M\rightarrow{C})$$
**两者的逻辑关系并不相同**
## (7)
**用符号形式写出下列命题**
### (a)
**假如上午不下雨,我去看电影,否则就在家里读书或看报**

**设**:命题$R$表示上午下雨\
命题$M$表示我去看电影
命题$B$表示在家里读书\
命题$P$表示在家里看报
$$(\neg{R}\rightarrow{M})\wedge(R\rightarrow(B\wedge\neg{P})\vee(\neg{B}\wedge{P}))$$
### (b)
**我今天进城,除非下雨**

**设**:命题$C$表示我今天进城\
命题$R$表示今天下雨
$$R\rightarrow\neg{C}$$
### (c)
**仅当你走我将留下**

**设**:命题$Y$表示你走\
命题$M$表示我留下
$$M\rightarrow{Y}$$
# 1-4
## (1)
**求下列各复合命题的真值表**
### (c)
$$(P\vee{Q})\leftrightarrow(Q\vee{P})$$
|P|Q|$(P\vee{Q})\leftrightarrow(Q\vee{P})$|
|:-:|:-:|:-:|
|1|1|1|
|1|0|1|
|0|1|1|
|0|0|1|
### (d)
$$(P\vee\neg{Q})\wedge{R}$$
|P|Q|R|$(P\vee\neg{Q})\wedge{R}$|
|:-:|:-:|:-:|:-:|
|1|1|1|1|
|1|1|0|0|
|1|0|1|1|
|1|0|0|0|
|0|1|1|0|
|0|1|0|0|
|0|0|1|1|
|0|0|0|0|
### (e)
$$(P\rightarrow(Q\rightarrow{R}))\rightarrow((P\rightarrow{Q})\rightarrow(P\rightarrow{R}))$$
|P|Q|R|$(P\rightarrow(Q\rightarrow{R}))\rightarrow((P\rightarrow{Q})\rightarrow(P\rightarrow{R}))$|
|:-:|:-:|:-:|:-:|
|1|1|1|1|
|1|1|0|1|
|1|0|1|1|
|1|0|0|1|
|0|1|1|1|
|0|1|0|1|
|0|0|1|1|
|0|0|0|1|
## (7)
**证明下列等价式**
### (b)
$$\neg(A\leftrightarrow{B})\Leftrightarrow(A\vee{B})\wedge\neg(A\wedge{B})$$
**证明**:
$$\neg(A\leftrightarrow{B})\Leftrightarrow\neg(A\rightarrow{B})\vee\neg(B\rightarrow{A})$$
$$\Leftrightarrow(A\wedge\neg{B})\vee(B\wedge\neg{A})$$
$$\Leftrightarrow((A\wedge\neg{B})\vee{B})\wedge((A\wedge\neg{B})\vee\neg{A})$$
$$\Leftrightarrow((A\vee{B})\wedge(\neg{B}\vee{B}))\wedge((A\vee\neg{A})\wedge(\neg{B}\vee\neg{A}))$$
$$\Leftrightarrow(A\vee{B})\wedge\neg(A\wedge{B})$$
### (d)
$$\neg(A\leftrightarrow{B})\Leftrightarrow(A\wedge\neg{B})\vee(\neg{A}\wedge{B})$$
**证明**:\
**在上题的第二步等价换算中已经给出**
### (f)
$$A\rightarrow(B\vee{C})\Leftrightarrow(A\wedge\neg{B})\rightarrow{C}$$
**证明**:
$$A\rightarrow(B\vee{C})\Leftrightarrow\neg{A}\vee{B}\vee{C}$$
$$\Leftrightarrow\neg(A\wedge\neg{B})\vee{C}$$
$$\Leftrightarrow(A\wedge\neg{B})\rightarrow{C}$$
### (h)
$$((A\wedge{B})\rightarrow{C})\wedge(B\rightarrow(D\vee{C}))\Leftrightarrow(B\wedge(D\rightarrow{A}))\rightarrow{C}$$
**证明**:.
$$((A\wedge{B})\rightarrow{C})\wedge(B\rightarrow(D\vee{C}))\Leftrightarrow(\neg{A}\vee\neg{B}\vee{C})\wedge(\neg{B}\vee{D}\vee{C})$$
$$\Leftrightarrow((\neg{A}\vee\neg{B})\wedge(\neg{B}\vee{D}))\vee{C}$$
$$\Leftrightarrow((\neg{A}\wedge{D})\vee\neg{B})\vee{C}$$
$$\Leftrightarrow(\neg(A\vee\neg{D})\vee\neg{B})\vee{C}$$
$$\Leftrightarrow\neg(B\wedge(D\rightarrow{A}))\vee{C}$$
$$\Leftrightarrow(B\wedge(D\rightarrow{A}))\rightarrow{C}$$
## (8)
**化简下列各式**
### (a)
$$((A\rightarrow{B})\leftrightarrow(\neg{B}\rightarrow\neg{A}))\wedge{C}$$
**解**:
$$((A\rightarrow{B})\leftrightarrow(\neg{B}\rightarrow\neg{A}))\wedge{C}\Leftrightarrow((\neg{A}\vee{B})\leftrightarrow(B\vee\neg{A}))\wedge{C}$$
$$\Leftrightarrow{T}\wedge{C}$$
$$\Leftrightarrow{C}$$
### (b)
$$A\vee(\neg{A}\vee(B\wedge\neg{B}))$$
**解**:
$$A\vee(\neg{A}\vee(B\wedge\neg{B}))\Leftrightarrow{A}\vee(\neg{A\vee{F}})$$
$$\Leftrightarrow{A}\vee\neg{A}$$
$$\Leftrightarrow{T}$$
### (C)
$$(A\wedge{B}\wedge{C})\vee(\neg{A}\wedge{B}\wedge{C})$$
**解**:
$$(A\wedge{B}\wedge{C})\vee(\neg{A}\wedge{B}\wedge{C})\Leftrightarrow(A\vee\neg{A})\wedge(B\wedge{C})$$
$$\Leftrightarrow{B}\wedge{C}$$
# 1-5
## (1)
**试论证下列各式为重言式**:
### (a)
$$(P\wedge(P\rightarrow{Q}))\rightarrow{Q}$$
**证明**:
$$(P\wedge(P\rightarrow{Q}))\rightarrow{Q}\Leftrightarrow((P\wedge\neg{P})\vee(P\wedge{Q}))\rightarrow{Q}$$
$$\Leftrightarrow\neg{P}\vee\neg{Q}\vee{Q}$$
$$\Leftrightarrow{T}$$
### (c)
$$((P\rightarrow{Q})\wedge(Q\rightarrow{R}))\rightarrow(P\rightarrow{R})$$
**证明**:
$$((P\rightarrow{Q})\wedge(Q\rightarrow{R}))\rightarrow(P\rightarrow{R})\Leftrightarrow((\neg{P}\vee{Q})\wedge(\neg{Q}\vee{R}))\rightarrow(P\rightarrow{R})$$
$$\Leftrightarrow(((\neg{P}\vee{Q})\wedge\neg{Q})\vee((\neg{P}\vee{Q})\wedge{R}))\rightarrow(P\rightarrow{R})$$
$$\Leftrightarrow\neg(\neg{P}\vee((\neg{P}\vee{Q})\wedge{R}))\vee(\neg{P}\vee{R})$$
$$\Leftrightarrow\neg((\neg{P}\vee{Q})\wedge(\neg{P}\vee{R}))\vee(\neg{P}\vee{R})$$
$$\Leftrightarrow\neg(\neg{P}\vee{Q})\vee\neg(\neg{P}\vee{R})\vee(\neg{P}\vee{R})$$
$$\Leftrightarrow{T}$$
## (2)
**不构造真值表证明下列蕴含式**
### (b)
$$(P\rightarrow{Q})\rightarrow{Q}\Rightarrow{P}\vee{Q}$$
**证明**:
要证蕴含式成立，即证
$$((P\rightarrow{Q})\rightarrow{Q})\rightarrow({P}\vee{Q})$$
为永真式

所以有
$$((P\rightarrow{Q})\rightarrow{Q})\rightarrow({P}\vee{Q})\Leftrightarrow\neg((P\wedge\neg{Q})\vee{Q})\vee{P}\vee{Q}$$
$$\Leftrightarrow((\neg{P}\vee{Q})\wedge\neg{Q})\vee{P}\vee{Q}$$
$$\Leftrightarrow(\neg{P}\wedge\neg{Q})\vee{P}\vee{Q}$$
$$\Leftrightarrow\neg(P\vee{Q})\vee(P\vee{Q})$$
$$\Leftrightarrow{T}$$
**得证**
## (6)
**检验下列论证的有效性**

**如果我学习,那么我数学不会不及格**\
**如果我不热衷于玩扑克,那么我将学习**\
**但我数学不及格**\
**因此我热衷于玩扑克**

**证明**:\
假设:命题$S$表示我学习\
命题$M$表示我数学及格\
命题$P$表示我热衷于玩扑克\
**所以可以得出一个蕴含式**:
$$(S\rightarrow{M})\wedge(\neg{P}\rightarrow{S})\wedge\neg{M}\Rightarrow{P}$$
现要证明该蕴含式的正确性，则有\
**证明**:
$$(S\rightarrow{M})\wedge(\neg{P}\rightarrow{S})\wedge\neg{M}\Leftrightarrow((S\rightarrow{M})\wedge\neg{M})\wedge(\neg{P}\rightarrow{S})$$
$$\Rightarrow\neg{S}\wedge(\neg{P}\rightarrow{S})$$
$$\Rightarrow\neg(\neg{P})$$
$$\Leftrightarrow{P}$$
即该蕴含式正确，论证有效
## (8)
**逻辑推证以下各式**
### (a)
$$P\Rightarrow(\neg{P}\rightarrow{Q})$$
**证明**:\
假设$P$为真,则有
$$\neg{P}\rightarrow{Q}\Leftrightarrow{P}\vee\neg{Q}$$
因为$P$为真，所以该式也为真，得证
### (c)
$$C\Rightarrow{A}\vee{B}\vee\neg{B}$$
**证明**:
易得
$$A\vee{B}\vee\neg{B}\Leftrightarrow{T}$$
即该式永真\
所以若$C$为真，该式也为真，得证
# 1-6
## (1)
**把下列各式用只含$\vee$和$\neg$的等价式表达 ,并要尽可能的简单**
### (a)
$$(P\wedge{Q})\wedge\neg{P}$$
**解**:
$$(P\wedge{Q})\wedge\neg{P}\Leftrightarrow{F}$$
### (b)
$$(P\rightarrow(Q\vee\neg{R}))\wedge\neg{P}\wedge{Q}$$
**解**:
$$(P\rightarrow(Q\vee\neg{R}))\wedge\neg{P}\wedge{Q}\Leftrightarrow(\neg{P}\vee({Q}\vee\neg{R}))\wedge\neg{P}\wedge{Q}$$
$$\Leftrightarrow\neg{P}\wedge{Q}$$
$$\Leftrightarrow\neg(P\vee\neg{Q})$$
### (c)
$$\neg{P}\wedge\neg{Q}\wedge(\neg{R}\rightarrow{P})$$
**解**:
$$\neg{P}\wedge\neg{Q}\wedge(\neg{R}\rightarrow{P})\Leftrightarrow\neg{P}\wedge(R\vee\neg{P})\wedge\neg{Q}$$
$$\Leftrightarrow\neg{P}\wedge\neg{Q}$$
$$\Leftrightarrow\neg(P\vee{Q})$$
## (2)
**对下列各式仅用"或非"($\downarrow$)表达**
### (a)
$$\neg{P}$$
**解**:
$$P\downarrow{P}$$
### (b)
$$P\vee{Q}$$
**解**:
$$P\vee{Q}\Leftrightarrow\neg(P\downarrow{Q})$$
$$\Leftrightarrow(P\downarrow{Q})\downarrow(P\downarrow{Q})$$
### (c)
$$P\wedge{Q}$$
**解**:
$$P\wedge{Q}\Leftrightarrow\neg(\neg{P}\vee\neg{Q})$$
$$\Leftrightarrow\neg{P}\downarrow\neg{Q}$$
$$\Leftrightarrow(P\downarrow{P})\downarrow(Q\downarrow{Q})$$
## (9)
**证明{$\neg,\rightarrow$}和{$\neg,\overset{c}{\rightarrow}$}是最小联结词**

**证明**:\
假设任意命题$P,Q$
$$P\vee{Q}\Leftrightarrow\neg{P}\rightarrow{Q}$$
且
$$\neg{P}\Leftrightarrow\neg{P}$$
**所以{$\neg,\rightarrow$}是最小联结词**

又
$$P\wedge{Q}\Leftrightarrow\neg(\neg{P}\vee\neg{Q})$$
$$\Leftrightarrow\neg(P\rightarrow\neg{Q})$$
$$\Leftrightarrow{P}\overset{c}{\rightarrow}\neg{Q}$$
**所以{$\neg,\overset{c}{\rightarrow}$}是最小联结词**

**得证**
# 1-7