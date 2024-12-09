Latest Logs From Latest Build
==============================

Generated On: 2024-12-09 15:16:51 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-09_15:14:20] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-09_15:14:26] STEP 2: Create topics started

  [INFO 2024-12-09_15:14:42] STEP 2: Completed

  [INFO 2024-12-09_15:14:55] STEP 3: producing data started

  [INFO 2024-12-09_15:14:58] MQTT connection established...

  [INFO 2024-12-09_15:14:59] STEP 4: Preprocessing started

  [INFO 2024-12-09_15:15:03] STEP 4: Preprocessing started

  [INFO 2024-12-09_15:15:06] STEP 7: Visualization started

  [INFO 2024-12-09_15:15:12] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2024-12-09_15:15:26] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-09_15:15:30] STEP 8: Starting docker push for: maadsdocker/cybersecuritywithprivategpt-3f10-amd64

  [INFO 2024-12-09_15:15:39] STEP 9: Starting privateGPT

  [INFO 2024-12-09_15:15:59] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit ec8984af0da7 maadsdocker/cybersecuritywithprivategpt-3f10-amd64 - message=0

  [INFO 2024-12-09_15:16:04] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-12-09_15:16:39] STEP 8: Successfully ran Docker push: docker push maadsdocker/cybersecuritywithprivategpt-3f10-amd64 - message=0

  [INFO 2024-12-09_15:16:51] STEP 10: Started to build the documentation

  [INFO 2024-12-09_15:16:52] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


