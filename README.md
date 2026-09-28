# Dog posture labelling

A small browser tool for labelling two-second dog video clips as **walk**, **sit**, **lie** or **stand**
(plus *other / mixed* and *unclear*). One keypress per clip; the clip loops until you label it.

Open the hosted page, or serve the folder locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Labels are held in the page for the session only. Nothing is uploaded and nothing is stored between
visits, so closing the tab clears them.

## Clips

The 20 clips are excerpts from the **TigDog** dog subset (Del Pero, Ricco, Sukthankar and Ferrari;
University of Edinburgh / Google Research), <http://calvin-vision.net/bigstuff/tigdog/>, used here for
non-commercial research. The TigDog authors note that they do not own the copyright to the underlying
internet videos. If you are a rights holder and want a clip removed, open an issue.

```bibtex
@inproceedings{delpero2015articulated,
  title     = {Articulated motion discovery using pairs of trajectories},
  author    = {Del Pero, Luca and Ricco, Susanna and Sukthankar, Rahul and Ferrari, Vittorio},
  booktitle = {CVPR},
  year      = {2015}
}
```
