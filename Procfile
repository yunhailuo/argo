controller: ALWAYS_OFFLOAD_NODE_STATUS=${ALWAYS_OFFLOAD_NODE_STATUS} OFFLOAD_NODE_STATUS_TTL=30s WORKFLOW_GC_PERIOD=30s UPPERIO_DB_DEBUG=1 ARCHIVED_WORKFLOW_GC_PERIOD=30s ./dist/workflow-controller --executor-image argoproj/argoexec:${VERSION} --namespaced --loglevel ${LOG_LEVEL}
argo-server: UPPERIO_DB_DEBUG=1 ./dist/argo --loglevel ${LOG_LEVEL} server --namespaced --auth-mode client --secure
