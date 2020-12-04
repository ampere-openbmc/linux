.. SPDX-License-Identifier: GPL-2.0

.. _linux_doc:

==============================
The Linux Kernel documentation
==============================

This is the top level of the kernel's documentation tree.  Kernel
documentation, like the kernel itself, is very much a work in progress;
that is especially true as we work to integrate our many scattered
documents into a coherent whole.  Please note that improvements to the
documentation are welcome; join the linux-doc list at vger.kernel.org if
you want to help out.

Working with the development community
======================================

The essential guides for interacting with the kernel's development
community and getting your work upstream.

.. toctree::
   :maxdepth: 1

   process/development-process
   process/submitting-patches
   Code of conduct <process/code-of-conduct>
   maintainer/index
   All development-process docs <process/index>


Internal API manuals
====================

Manuals for use by developers working to interface with the rest of the
kernel.

.. toctree::
   :maxdepth: 1

   core-api/index
   driver-api/index
   subsystem-apis
   Locking in the kernel <locking/index>

Development tools and processes
===============================

Various other manuals with useful information for all kernel developers.

.. toctree::
   :maxdepth: 1

   process/license-rules
   doc-guide/index
   dev-tools/index
   dev-tools/testing-overview
   kernel-hacking/index
   trace/index
   fault-injection/index
   livepatch/index
   rust/index


User-oriented documentation
===========================

The following manuals are written for *users* of the kernel — those who are
trying to get it to work optimally on a given system and application
developers seeking information on the kernel's user-space APIs.

.. toctree::
   :maxdepth: 1

   admin-guide/index
   The kernel build system <kbuild/index>
   admin-guide/reporting-issues.rst
   User-space tools <tools/index>
   userspace-api/index

See also: the `Linux man pages <https://www.kernel.org/doc/man-pages/>`_,
which are kept separately from the kernel's own documentation.

Firmware-related documentation
==============================
The following holds information on the kernel's expectations regarding the
platform firmwares.

.. toctree::
   :maxdepth: 1

   firmware-guide/index
   devicetree/index

Application-developer documentation
-----------------------------------

The user-space API manual gathers together documents describing aspects of
the kernel interface as seen by application developers.

.. toctree::
   :maxdepth: 2

   userspace-api/index


Introduction to kernel development
----------------------------------

These manuals contain overall information about how to develop the kernel.
The kernel community is quite large, with thousands of developers
contributing over the course of a year.  As with any large community,
knowing how things are done will make the process of getting your changes
merged much easier.

.. toctree::
   :maxdepth: 2

   process/index
   dev-tools/index
   doc-guide/index
   kernel-hacking/index
   trace/index
   maintainer/index
   fault-injection/index
   livepatch/index


Kernel API documentation
------------------------

These books get into the details of how specific kernel subsystems work
from the point of view of a kernel developer.  Much of the information here
is taken directly from the kernel source, with supplemental material added
as needed (or at least as we managed to add it — probably *not* all that is
needed).

.. toctree::
   :maxdepth: 2

   driver-api/index
   core-api/index
   locking/index
   accounting/index
   block/index
   cdrom/index
   cpu-freq/index
   fb/index
   fpga/index
   hid/index
   i2c/index
   iio/index
   isdn/index
   infiniband/index
   jtag/index
   leds/index
   netlabel/index
   networking/index
   pcmcia/index
   power/index
   target/index
   timers/index
   spi/index
   w1/index
   watchdog/index
   virt/index
   input/index
   hwmon/index
   gpu/index
   security/index
   sound/index
   crypto/index
   filesystems/index
   mm/index
   bpf/index
   usb/index
   PCI/index
   scsi/index
   misc-devices/index
   scheduler/index
   mhi/index
   peci/index

Architecture-agnostic documentation
-----------------------------------

.. toctree::
   :maxdepth: 2

   asm-annotations

Architecture-specific documentation
===================================

.. toctree::
   :maxdepth: 2

   arch/index


Other documentation
===================

There are several unsorted documents that don't seem to fit on other parts
of the documentation body, or may require some adjustments and/or conversion
to ReStructured Text format, or are simply too old.

.. toctree::
   :maxdepth: 1

   staging/index


Translations
============

.. toctree::
   :maxdepth: 2

   translations/index

Indices and tables
==================

* :ref:`genindex`
