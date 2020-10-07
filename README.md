### Hi there 👋

<!--
**Afrizal1998/afrizal1998** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:
from sklearn import tree

#jeruk = 0
#apel = 1
#halus = 0
#kasar = 1

ciri = [[120, 1],[150, 1],[200, 0],[250, 0]]
label = [0, 0, 1, 1]
mesin = tree.DecisionTreeClassifier()
mesin = mesin.fit(ciri, label)

a = input('Berapa gram beratnya ?'\n'>>> ')
b = input('Teksturnya'\n'Halus atau kasar')

data = int(a)
if b.lower() == 'halus':
    tekstur = 0
elif b.lower() == 'kasar':
    tekstur = 1
else:
    print('Unknown')

c = mesin.predict([[data, tekstur]])
if c == 0:
    d = 'Jeruk'
else:
    d = 'Apel'

print('Nama buahnya diprediksi {}'.format(d))

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
