.. only:: not (epub or latex or html)

    WARNING: You are looking at unreleased Cilium documentation.
    Please use the official rendered version released here:
    https://docs.cilium.io

Welcome to Cilium's documentation!
==================================

The documentation is divided into the following sections:

* :ref:`k8s_install_quick`: Provides a simple tutorial for running a small Cilium
  setup on your laptop.  Intended as an easy way to get your hands dirty
  applying Cilium security policies between containers.

* :ref:`concepts`: Describes the components of Cilium,
  and the different models for deploying Cilium.  Provides the high-level
  understanding required to run a full Cilium deployment and understand its
  behavior.

* :ref:`getting_started` :  Details instructions for installing, configuring, and
  troubleshooting Cilium in different deployment modes.

* :ref:`network_policy` : Detailed walkthrough of the policy language structure
  and the supported formats.

* :ref:`metrics` : Instructions for configuring metrics collection from Cilium.

* :ref:`admin_guide` : Describes how to troubleshoot Cilium in different
  deployment modes.

* :ref:`bpf_guide` : Provides a technical deep dive of eBPF and XDP technology,
  primarily focused at developers.

* :ref:`api_ref` : Details the Cilium agent API for interacting with a local
  Cilium instance.

* :ref:`dev_guide` : Gives background to those looking to develop and contribute
  modifications to the Cilium code or documentation.

A `hands-on tutorial <https://play.instruqt.com/isovalent/invite/j4maqox5r1h5>`_ 
in a live environment is also available for users looking for a way to quickly
get started and experiment with Cilium.

.. toctree::
   :maxdepth: 2
   :caption: Overview

   overview/intro
   overview/component-overview

.. _getting_started:

.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   gettingstarted/k8s-install-default
   gettingstarted/hubble_intro
   gettingstarted/hubble_setup
   gettingstarted/hubble-configuration
   gettingstarted/hubble
   gettingstarted/hubble_cli.rst
   gettingstarted/terminology
   gettingstarted/gettinghelp

.. toctree::
   :maxdepth: 2
   :caption: Advanced Installation

   installation/index


.. toctree::
   :maxdepth: 2
   :caption: Operations

   operations/system_requirements
   operations/upgrade
   configuration/index
   policy/index
   operations/metrics
   operations/performance/index
   operations/troubleshooting
   concepts/index
   installation/microk8s


.. toctree::
   :maxdepth: 2
   :caption: Community

   community/community
   community/governance/index
   community/roadmap

.. toctree::
   :maxdepth: 3
   :caption: For Developers

   contributing/development/index
   contributing/release/index
   contributing/testing/index
   bpf
   api
   grpcapi
   internals/index

.. toctree::
   :maxdepth: 2
   :caption: Reference

   cheatsheet
   cmdref/index
   kvstore
   further_reading
   glossary
   helm-reference
