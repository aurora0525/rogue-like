# rogue-like

vide =0
mur=1
escalierM=
escalierD=


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

def escalierD():
  i=randint(1,31)
  j=randint(1,31)   #faire des conditions pour que les escaliers ne tombent pas sur un mur !!!
  D=[i,j]
    
