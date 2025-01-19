.. _topiclink:

vSphere+ Requirements
=====================

vSphere+ supports all existing vSphere capabilities including Enhanced Linked Mode and vSphere High Availability (HA). The ESXi host and vCenter must meet certain software and hardware requirements.


.. _sectionlink:

ESXi Host and vCenter Requirements
-----------------------------------

* vCenter:

	* 7.0 Update 3g and later
	* 8.0.x and later

* ESXi hosts: 

	All versions of 6.7, 7.0, and 8.0.

Hardware Requirements
---------------------

The cluster where the vCenter and VMware Cloud Gateway are deployed must meet certain hardware requirements.

**Hardware Requirements for VMware Cloud Gateway**

You can connect up to eight vCenter instances on each VMware Cloud Gateway instance. The number of instances you must install depends on the number of vCenter instances you want to subscribe to vSphere+. See VMware Cloud Gateway Requirements.

**Hardware Requirements for vCenter Updates**

The CPU, memory, and storage on the cluster must be at least twice the size of the deployed vCenter so that the hardware is sufficient for the vCenter updates. See System Requirements for vCenter.

Procedure Sample
----------------

#. Go to the VMware Cloud Console at https://vmc.vmware.com.
#. Under Infrastructure, select vSphere+ > Learn More.
#. Click Start Trial.
   The VMware Cloud Services login page opens.
#. Follow the on-screen prompts to create your VMware Cloud account.

Figure Sample
---------------------

.. figure:: /images/vsphereplus.png
  :alt: Alt text sample
  :align: center

  *vSphere+ Architecture*
