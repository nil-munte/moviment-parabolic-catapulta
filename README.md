# Catapulta parabòlica

Demo interactiva del moviment parabòlic per a **1r de Batxillerat**. Una catapulta llança un projectil i es veu com el moviment es descompon en dos moviments independents:

- **Eix X: MRU**. La velocitat horitzontal és constant: `x(t) = x₀ + v₀ₓ·t`
- **Eix Y: MRUA**. L'acceleració és `a_y = −g`: `y(t) = y₀ + v₀ᵧ·t − ½·g·t²` i `v_y(t) = v₀ᵧ − g·t`

amb `v₀ₓ = v₀·cos α` i `v₀ᵧ = v₀·sin α`.

**Demo en línia:** https://nil-munte.github.io/moviment-parabolic-catapulta/

## Què es pot fer

- Canviar la velocitat inicial `v₀`, l'angle `α`, l'altura inicial `y₀` i la gravetat (Terra, Lluna, Mart, Júpiter o un valor lliure).
- Veure les equacions generals i les mateixes equacions amb els valors substituïts, i el càlcul a l'instant actual.
- Mostrar els vectors `v`, `vₓ` i `vᵧ` damunt del projectil.
- Mostrar les projeccions sobre els eixos i la posició cada Δt: sobre l'eix X les marques queden igual de separades (MRU) i sobre l'eix Y no (MRUA).
- Consultar les gràfiques x–t, y–t i v–t en directe.
- Aturar el llançament i moure's a qualsevol instant amb la barra de temps, o reproduir-lo a 1×, ½× o ⅕×.
- Comparar llançaments amb les traces dels anteriors.

## Ús a classe

- **Resultats amagats**: desmarqueu «Resultats numèrics» i «Trajectòria prevista». L'alumnat calcula el temps de vol, l'abast i l'altura màxima, i després ho comprova.
- **Repte del castell**: activeu «Repte: encerta el castell», fixeu-ne la distància i l'altura, i demaneu quina velocitat o quin angle cal per encertar-lo.
- **Altres planetes**: amb la mateixa `v₀` i el mateix `α`, compareu l'abast a la Terra i a la Lluna.

Criteri de signes: l'eix Y és positiu cap amunt i l'origen és al peu de la torre. Es menysprea la fricció amb l'aire.

## Ús local

És un sol fitxer, `index.html`, sense dependències ni cap pas de compilació. S'obre amb doble clic en qualsevol navegador. Les fonts es carreguen de Google Fonts; sense connexió, la pàgina funciona igual amb la lletra del sistema.

## Publicació a GitHub Pages

1. Pugeu els fitxers a la branca `main` del repositori.
2. A GitHub, aneu a **Settings → Pages**.
3. A **Build and deployment**, trieu **Source: Deploy from a branch**, branca `main` i carpeta `/ (root)`, i deseu.
4. Al cap d'un o dos minuts, la demo estarà disponible a l'adreça de dalt.

El fitxer `.nojekyll` indica a GitHub Pages que serveixi els fitxers tal com són, sense processar-los amb Jekyll.

## Llicència

[MIT](LICENSE) © 2026 Nil Munté
