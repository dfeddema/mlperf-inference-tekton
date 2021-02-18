# mlperf inference benchmarks in tekton pipelines
#
# Work in Progress 

This is a tekton pipeline to run the mkperf inrerence benchmark with benchmarks='resnet' scenarios='Server' 
and benchmarks='resnet'  scenarios='Offline' 

To run: 

$ oc apply -f task.yaml

$ oc apply -f pipeline.yaml

$ tkn pipeline start mlperf-inference --showlog


