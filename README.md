# rogue-like

vide =0
mur=1
escalier=


def etage(e):
  etage=np.zeros((32,32)):
  for k in range(0,32):
    if k==0 or k==32:
      etage[:,k]=mur
  for i in range (0,32):
    if k==0 or k==32:
      etage[i,:]=mur
  return etage
  
def donjon():
  d=[]
  for k in range(0,10):
    d.append(etage(k))
  return d
