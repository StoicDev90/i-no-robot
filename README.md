# i-no-robot

Skill de Claude Code para escribir o editar prosa en español que no suene a texto generado por IA.

## Qué hace

Detecta y corrige los patrones típicos del español escrito por modelos de lenguaje: inflación de importancia ("marcó un antes y un después"), vocabulario inflado (profundizar, fomentar, holístico, ecosistema), contrastes innecesarios ("no solo X, sino Y"), tríos automáticos ("rápido, fácil y eficaz"), gerundios de consecuencia ("..., logrando así..."), muletillas ("cabe destacar", "en el mundo actual") y tipografía calcada del inglés (comillas rectas, raya sobreusada, title case).

No se limita a borrar. También evalúa el ritmo de las oraciones, la variedad de los párrafos y la voz del texto, que es la parte que más se suele descuidar al limpiar un texto.

## Cuándo se activa

Se usa al escribir prosa desde cero o al editar un texto existente: emails, mensajes, posts, artículos, informes, resúmenes, descripciones de producto.

No aplica a código, citas textuales ni textos legales o normativos con fórmulas obligatorias.

## Cómo usarla

```
/i-no-robot
```

Para escribir desde cero, pedí el texto directamente y la skill aplica los principios de redacción desde el primer borrador. Para editar algo que ya existe, pegá el texto junto con el comando: la skill conserva el sentido, los datos y el registro del original, y entrega solo la versión revisada.

## Contenido

Todas las reglas están en [SKILL.md](SKILL.md): los principios de redacción, las estructuras a evitar con ejemplos de antes y después, el vocabulario de alarma en español e inglés, las normas de formato y una lista de revisión final.

## Qué no hace

No introduce errores, coloquialismos ni muletillas orales para simular que un humano escribió el texto. No cambia el registro del original: un informe formal sigue formal, un mensaje a un amigo sigue informal. Si una palabra de las listas de alarma es el término exacto para el caso, la deja.
