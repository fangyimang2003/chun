//这是很sb的东西，纯手工打，兔杂出，错误在所难免，至于什么zlp适用请自己编译尝试，，，不想看可以滚蛋
{＃cleo.cs}
thread'BSSJGB'
0247: load_model #FAM3
0247: load_model #FAM2
0247: load_model #FAM1
0247: load_model -1
0247: load_model #M4
0247: load_model #AK47
0247: load_model #MINIGUN
0247: load_model #HEATSEEK
:BSSJGB_1
wait 500
if
Player.Defined($PLAYER_CHAR)
jf @BSSJGB_1
if and
0248: model #HEATSEEK available
0248: model #MINIGUN available
0248: model #AK47 available
0248: model #M4 available
0248: model -1 available
0248: model #FAM1 available
0248: model #FAM2 available
0248: model #FAM3 available
//未完待续，老子不想写了
