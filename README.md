# Consistency chekcing for ontology learning from Relational Database

This is a graph-based intermediate model that represent the semantics of RDB and the spcifications of learned ontologies.
- The graph-based intermediate model is encoded by SMV program.
- The specification of learned ontologies is formalzied by CTL formula.

This model could be run [nuXmv](https://nusmv.fbk.eu/) model chcker to verify whether the learned ontolgies satisfy the RDB model by excuting the folloing commands:
1. read_model -i Mini_University.smv
2. flatten_hierarchy
3. encode_variables
4. build_model
5. check_fsm
6. check_ctlspec


