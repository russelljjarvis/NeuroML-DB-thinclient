# NeuroML-DB_thinclient
Client side NeuroML-DB
https://github.com/scrook/neuroml-db/

neuroml-db contains some great pipelines for handling: realistic mutli-compartment NEURON, HBP and Allen protocals. The problem is that the implementation of these algorithms is designed to be intrinsically server side and data-base intensive. The database/webservice is also dependency heavy. This repository serves as a light weight client side implementation of those pipelines and algorithms, found in NeuroML-DB.

The build environment needs python to be able to import the NEURON simulator. The attached Dockerfile, describes the appropriate build env, and makes cloning the exact environment possible. 
