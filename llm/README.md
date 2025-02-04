#### LLM (Section 8)

The code for running the LLM experiments (Section 7) is in the ``llm`` directory:

```shell
cd llm
```

The ``main_bppy.py`` file runs the evaluation for the BP model, and the ``main_regular.py`` runs the evaluation for the python model.
Both accept a single parameter, an example identifier, one of `r1,...,r10` or `rs1,...,rs10`


For example, running the evaluation of the BP model for the specification example `rs1`:
```shell
python3 main_bppy.py rs1
```

and running the evaluation of the Python model for the specification example `rs1`:
```shell
python3 main_regular.py rs1
```

The scripts output the alignment of the 100 sampled traces with requirements.

The full evaluation results mentioned in the end of Section 8 can be obtained by running the script `run_all.sh` using the `bash` command.

