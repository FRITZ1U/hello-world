# hello-world
#my first repository

#if else语句exercise
status=int(input('dying'))
if status>50:
  print('你不用惊慌，\n死亡是生命的一部分，是我们注定要面对的。\n我不知道为什么，但我注定要做你的妈妈，我就尽力做好。\n\n我相信你能实现自己的命运。\n你要凭着上帝所给予的做到最好。\n\n你要弄明白你的命运是什么。\n人生就像一盒巧克力，\n你永远不知道拿到的下一颗是什么。')
else:
  print('只要你需要，我就在这里。')
  
#测试BMI
weight=float(input('体重：'))
height=float(input('身高：'))
BMI=(weight/height**2)

if 18.5<BMI<23.9:
  print('正常')
elif BMI<18.5:
  print('偏瘦')
else:
  print('偏胖')
