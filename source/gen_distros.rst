=============
Distributions
=============

HELM charts
-----------

- Release and pre-release :term:`Helm charts <Odahu HELM Chart>` are in `github <https://github.com/odahu/odahu-helm>`_.

.. csv-table::
   :header: "Helm chart name", "Repository", "Description"
   :widths: 20, 30, 40

   "odahu-flow-fluentd", "odahu/odahu-infra", "Fluentd with gcp, s3 and abs plugins"
   "odahu-flow-k8s-gke-saa", "odahu/odahu-infra", "GKE role assigner"
   "odahu-flow-knative", "odahu/odahu-infra", "Custom knative chart"
   "odahu-flow-monitoring", "odahu/odahu-infra", "Prometheus, grafana and alertmanager"
   "odahu-flow-opa", "odahu/odahu-infra", "Open Policy Agent"
   "odahu-flow-tekton", "odahu/odahu-infra", "Custom tekton chart"
   "odahu-flow-core", "odahu/odahu-flow", "Core Odahu-flow services"
   "odahu-flow-mlflow", "odahu/odahu-trainer", "Odahu-flow mlflow toolchain"
   "odahu-flow-packagers", "odahu/odahu-packager", "Odahu-flow REST packager"

Docker Images
-------------

 Release versions of images are on Docker Hub in the `odahu <https://hub.docker.com/u/odahu>`_ team.

.. csv-table::
   :header: "Image name", "Repository", "Description"
   :widths: 20, 30, 40

   "odahu-flow-fluentd", "odahu/odahu-infra", "Fluentd with gcp, s3 and abs plugins"
   "odahu-flow-api", "odahu/odahu-flow", "Odahu-flow API service"
   "odahu-flow-model-cli", "odahu/odahu-flow", "Odahu-flow CLI"
   "odahu-flow-model-trainer", "odahu/odahu-flow", "Trainer helper"
   "odahu-flow-model-packager", "odahu/odahu-flow", "Packager helper"
   "odahu-flow-service-catalog", "odahu/odahu-flow", "Swagger for model deployments"
   "odahu-flow-operator", "odahu/odahu-flow", "Odahu-flow kubernetes orchestrator"
   "odahu-flow-feedback-collector", "odahu/odahu-flow", "REST API for user feedback service"
   "odahu-flow-feedback-rq-catcher", "odahu/odahu-flow", "Model deployment request-response catcher"
   "odahu-flow-mlflow-toolchain", "odahu/odahu-trainer", "Odahu-flow mlflow toolchain"
   "odahu-flow-mlflow-toolchain-gpu", "odahu/odahu-trainer", "Odahu-flow mlflow toolchain with NVIDIA GPU"
   "odahu-flow-mlflow-tracking-server", "odahu/odahu-trainer", "MLflow tracking service"
   "odahu-flow-packagers", "odahu/odahu-packager", "Odahu-flow packagers"
   "base-notebook", "odahu/odahu-flow-jupyterlab-plugin", "Image with :ref:`int_jupyterlab_extension:JupyterLab extension` based on `jupyter/base-notebook <https://hub.docker.com/r/jupyter/base-notebook>`_"
   "datascience-notebook", "odahu/odahu-flow-jupyterlab-plugin", "Image with :ref:`int_jupyterlab_extension:JupyterLab extension` based on `jupyter/datascience-notebook <https://hub.docker.com/r/jupyter/datascience-notebook>`_"
   "tensorflow-notebook", "odahu/odahu-flow-jupyterlab-plugin", "Image with :ref:`int_jupyterlab_extension:JupyterLab extension` based on `jupyter/tensorflow-notebook <https://hub.docker.com/r/jupyter/tensorflow-notebook>`_"

Python packages
---------------

- Release versions of Python packages are on PyPi: `odahu <https://pypi.org/search/?q=odahu>`_.

.. csv-table::
   :header: "Package name", "Repository", "Description"
   :widths: 20, 30, 40

   "odahu-flow-cli", "odahu/odahu-flow", "Odahu-flow CLI"
   "odahu-flow-sdk", "odahu/odahu-flow", "Odahu-flow SDK"
   "odahu-flow-jupyterlab-plugin", "odahu/odahu-flow-jupyterlab-plugin", "Jupyterlab with the Odahu-flow plugin"
   "odahu-flow-airflow-plugin", "odahu/odahu-airflow-plugin", "Odahu-flow Airflow plugin(operators, hooks and so on)"

NPM packages
------------

- Release versions of Python packages are on npm in project odahu.

.. csv-table::
   :header: "Package name", "Repository", "Description"
   :widths: 20, 30, 40

   "odahu-flow-jupyterlab-plugin", "odahu/odahu-flow-jupyterlab-plugin", "Jupyterlab with the Odahu-flow plugin"
