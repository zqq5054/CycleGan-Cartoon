- split photo2cartoon_weights.pt:
  split -b 80MB photo2cartoon_weights.pt photo2cartoon_weights.pt. -d

- restore
  cat photo2cartoon_weights.pt.0* > photo2cartoon_weights.pt
