# m8ball
def pl():
  f='/Users/mhovan/Desktop/m8ball.jpg'
  p=makePicture(f)
  s=makeStyle(sansSerif,bold,18)
  addTextWithStyle(p,115,100,"It is",s,white)
  addTextWithStyle(p,90,115,"decidedly",s,white)
  addTextWithStyle(p,115,130,"so",s,white)
  repaint(p)
