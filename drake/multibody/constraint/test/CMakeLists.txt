drake_add_cc_test(NAME rigid_body_constraint_test)
target_link_libraries(rigid_body_constraint_test
    drakeRBM drakeRigidBodyConstraint)
