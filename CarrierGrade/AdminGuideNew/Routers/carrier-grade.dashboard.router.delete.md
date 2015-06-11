---
layout: default
title: "HP Helion OpenStack&#174; Carrier Grade (Beta): Deleting a Router"
permalink: /helion/commercial/carrier/dashboard/managing/router/delete/
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

# HP Helion OpenStack&#174; Carrier Grade (Beta): Deleting a Router

A network connects to the router through an interface.

You must remove all router interfaces before deleting the router, by removing all internal interfaces.

### Delete a router ###

1. [Launch the HP Helion OpenStack Horizon Dashboard](/helion/openstack/carrier/dashboard/login/).

2. Click the **Project** dashboard, then the **System** panel, then the **Network Topology** link.

	Determine if the router is connected to a network using the [Network Topology screen](/helion/commercial/carrier/dashboard/managing/network/viewing/):

	<br /><img src="media/NetworkConnections.png"  alt="" />

3. Click the **Routers** link on the **Project** dashboard **Network** panel.

	The routers for the selected project appear. 

	If the router is connected to a network:

		a. Click the name of the router you want to delete.</li>
		b. On the **Router Details** screen, select the interface(s) for the router and click **Delete Interface**.</li>
		c. Return to the **Routers** screen.</li>

4. For the router you want to delete, click **More &gt; Delete Router**.

5. In the confirmation window, click **Delete Router**.


You can use the CLI to delete a router:

To delete a router:

	neutron router-delete router_id

<a href="#top" style="padding:14px 0px 14px 0px; text-decoration: none;"> Return to Top &#8593; </a>


----