# Tekton

1. Create git secret with GIT SSH key
2. Link secret to pipeline service account
3. oc create pvc-m2-cache.yaml
4. oc create pvc-workspace.yaml
5. oc create task-dev-quarkus.yaml
6. oc create pipeline.yaml
7. Run the Pipeline by using the PipelineRuns