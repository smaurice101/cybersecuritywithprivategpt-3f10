Latest Logs From Latest Build
==============================

Generated On: 2025-02-06 17:58:42 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-02-06_17:57:11] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-02-06_17:57:14] STEP 2: Create topics started

  [INFO 2025-02-06_17:57:18] STEP 2: Completed

  [INFO 2025-02-06_17:57:24] STEP 3: producing data started

  [INFO 2025-02-06_17:57:26] MQTT connection established...

  [INFO 2025-02-06_17:57:26] STEP 4: Preprocessing started

  [INFO 2025-02-06_17:57:28] STEP 4: Preprocessing started

  [INFO 2025-02-06_17:57:29] STEP 7: Visualization started

  [INFO 2025-02-06_17:57:35] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2025-02-06_17:57:44] STEP 9: Qdrant container.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant, v=0

  [INFO 2025-02-06_17:57:44] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2025-02-06_17:57:44] STEP 8: Starting docker push for: maadsdocker/cybersecuritywithprivategpt-3f10-amd64

  [INFO 2025-02-06_17:57:49] STEP 9: Starting privateGPT Kube=0

  [INFO 2025-02-06_17:57:56] STEP 9: PrivateGPT container.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env vectorsearchtype="Manhattan" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2, v=0

  [INFO 2025-02-06_17:57:56] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env vectorsearchtype="Manhattan" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2

  [INFO 2025-02-06_17:58:31] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit 086b8f54398f maadsdocker/cybersecuritywithprivategpt-3f10-amd64 - message=0

  [INFO 2025-02-06_17:58:42] STEP 10: Started to build the documentation

  [INFO 2025-02-06_17:58:42] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


