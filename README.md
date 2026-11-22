# What's that muscle?

Point at a muscle, see what it is, and walk the anatomy around it: the bones it starts and ends on, its nerve and spinal roots, its blood supply, what it moves, and the exercises and stretches for it. Every body system is in it, and a 3D body you can turn, zoom and peel layer by layer, each of its parts tied to the graph. Physios and trainers can gather a client handout, print it, or send it as a link.

**Open it:** https://evanmcdowell31.github.io/whats-that-muscle/

A prototype. For learning, not diagnosis.

## Handout links, with no server

A handout link carries the handout itself, after the `#`, the part of a link a browser never sends to a server. This site is plain static files: it stores nothing about anyone. The client's name is never put in a link.

## What is in it, and its licences

- The page's own code: Apache-2.0.
- Anatomy facts: English Wikipedia's articles, CC BY-SA 4.0. Each card links the article revision it came from.
- The 3D body: [BodyParts3D](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/), © The Database Center for Life Science, CC BY 4.0, with the nerves of the trunk and limbs and the lymph nodes from [Z-Anatomy](https://github.com/Z-Anatomy/Unity-app_Z-Anatomy), CC BY-SA 4.0.
- Exercises and their steps: [free-exercise-db](https://github.com/yuhonas/free-exercise-db), public domain (the Unlicense).
- Body drawing: [react-native-body-highlighter](https://github.com/HichamELBSI/react-native-body-highlighter), MIT.

[docs/LICENSES.txt](docs/LICENSES.txt) has the full notices. The page in `docs/` is built from its source with `tools/publish.sh` there; edit the source, not this copy.
