# Proof-of-intersection

## Check Private Set Intersection (PSI) example

This mini-project illustrates how to import and use `check_private_set_intersection(commitment_a, commitment_b, private_set_a, private_set_b, intersection_is_empty)` from `proof_of_intersection` public Noir library.

## Run the proof generation & verification

```bash
cd example/
nargo prove it_s_a_match
nargo verify it_s_a_match
```

## Notes

If you use the function in your project, make sure the commitments and the emptyness to check are public inputs (`commitment_a`, `commitment_b` and `intersection_is_empty`).