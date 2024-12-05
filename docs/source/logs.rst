Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 17:08:04 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/anupampDL/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_17:02:39] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_17:02:44] STEP 2: Create topics started

  [INFO 2024-12-05_17:03:06] STEP 2: Completed

  [INFO 2024-12-05_17:03:16] STEP 3: producing data started

  [INFO 2024-12-05_17:03:20] MQTT connection established...

  [INFO 2024-12-05_17:03:21] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:03:25] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:03:26] STEP 7: Visualization started

  [INFO 2024-12-05_17:03:33] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:03:49] STEP 8: Starting docker push for: anupampdl/finalproject160withprivategpt-5567-amd64

  [INFO 2024-12-05_17:04:04] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_17:04:09] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:04:19] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit fb7ccd20847c anupampdl/finalproject160withprivategpt-5567-amd64 - message=0

  [INFO 2024-12-05_17:04:19] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-12-05_17:07:53] STEP 8: Successfully ran Docker push: docker push anupampdl/finalproject160withprivategpt-5567-amd64 - message=0

  [INFO 2024-12-05_17:08:04] STEP 10: Started to build the documentation

  [INFO 2024-12-05_17:08:04] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


