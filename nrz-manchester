#autor: Pedro Inacio

import matplotlib.pyplot as plt

bits = input()

left = []
left = range(1,len(bits)+1)
tick_label = []
nrz = []
for i in bits:
    if i=="0":
        nrz.append(0)
        tick_label.append(i)
    else:
        nrz.append(1)
        tick_label.append(i)

plt.bar(left, nrz, tick_label = tick_label,
        width = 1.0, color = ['red', 'green'])
 
plt.xlabel('bits')
plt.ylabel('nrz')
plt.title('codificacao-nrz')
plt.gca().axes.get_yaxis().set_visible(False)
plt.show()

local = []
manc = []
binarios = []
for i in bits:
    if i=="0":
        manc.append(1)
        manc.append(0.9)
        binarios.append("0")
        binarios.append("-")
    else:
        manc.append(0.9)
        manc.append(1)
        binarios.append("1")
        binarios.append("-")
local = range(1,len(manc)+1)
plt.bar(local, manc, tick_label = binarios,
        width = 1.0, color = ['red', 'green'])
 
plt.xlabel('bits')
plt.ylabel('manchester')
plt.title('codificacao-manchester')
plt.gca().axes.get_yaxis().set_visible(False)
plt.show()

"""
nrz = ""
for i in bits:
    if i=="0":
        nrz = nrz + "_"
    elif i=="1":
        nrz = nrz + "–"
print("nrz: \n", nrz)
manchester = ""
for i in bits:
    if i=="0":
        manchester = manchester + "–|_"
    elif i=="1":
        manchester = manchester + "_|–"
print("manchester: \n", manchester)
"""
