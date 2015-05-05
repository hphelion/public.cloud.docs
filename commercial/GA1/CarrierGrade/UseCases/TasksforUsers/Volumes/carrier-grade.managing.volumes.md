---
layout: default
title: "HP Helion OpenStack&#174; Carrier Grade (Alpha): Managing Block Storage Volumes"
permalink: /helion/commercial/carrier/dashboard/managing/volumes/
product: carrier-grade

---
<!--UNDER REVISION-->

<script>

function PageRefresh {
onLoad="window.refresh"
}

PageRefresh();

</script>

<!-- <p style="font-size: small;"> <a href="/helion/commercial/carrier/ga1/install/">&#9664; PREV</a> | <a href="/helion/commercial/carrier/ga1/install-overview/">&#9650; UP</a> | <a href="/helion/commercial/carrier/ga1/">NEXT &#9654;</a></p> -->

# HP Helion OpenStack&#174; Carrier Grade (Alpha): Managing Block Storage Volumes

Volumes are block storage devices that allow you to expand the storage capacity of an instance. Volumes may only be attached to one server at a time, and will retain data, even when not attached to an instance.

You can create and configure volumes; create snapshots of volumes; update the metadata associated with a volume, extend volumes, and transfer a volume between users, and attach and detach volumes from instances.

How you interact with these images depends upon your user type, either an administrative user (admin) or a non-administrative user (user). 


To work with volumes [launch the HP Helion OpenStack Helion Dashboard](/helion/openstack/carrier/dashboard/login/).

* For non-admin users, click **Project** > **Compute** > **Volumes**. The volumes in the current project are listed.
* For admin users, click **Admin** > **Volumes**. The volumes in the current domain are listed.

The **Volumes** panel looks similar to the following. Click the image to view in a new window: 

<img src="media/CGH-Helion-Volumes.png"/>

<a href="javascript:window.open('/content/documentation/media/media/CGH-Helion-Volumes.png','_blank','toolbar=no,menubar=no,resizable=yes,scrollbars=yes')">Click here to view a larger image in a new window.</a>

For details on a volume, click the volume name. 

## Managing volumes as a user ##

As a user, you can work with any volume associated with the active project. 

* [Create, edit and delete a volume](/helion/commercial/carrier/dashboard/managing/volume/create/)
* [Create a snapshot from a volume](/helion/commercial/carrier/dashboard/managing/volume/snapshot/create/)
* [Extend the size of a volume](/helion/commercial/carrier/dashboard/managing/volume/extend/)
* [Attach a volume to a VM instance and detach a volume from VM instance](/helion/commercial/carrier/dashboard/managing/volume/attach/)

## Managing volumes as an admin ##

**Note:** The administrative user can perform all of the user tasks in addition to the admin tasks.

* [Creating and deleting a volume type](/helion/commercial/carrier/dashboard/managing/volume/admin/)

<p><a href="#top" style="padding:14px 0px 14px 0px; text-decoration: none;"> Return to Top &#8593; </a></p>


----