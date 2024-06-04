# Objectifs journaliers

## Mardi 28/05/2024

### DOM :

-[x] Comprendre les propriétés des nœuds (https://javascript.info/b[]asic-dom-node-properties) :
 [x] - nodeType
 [x] - innerHTML
 [x] - outerHTML
 [x] - textContent
 [x] - ...
-[x] Connaitre les attributs et propriétés du DOM (https://javascript.info/dom-attributes-and-properties)

const wrapper = document.querySelector('#lastPosts');
const loader = document.createElement('p');
loader.innerText = 'Chargement...';
wrapper.append(loader);