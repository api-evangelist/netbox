---
title: "NetBox Labs CMDB Integration for ServiceNow Hits the Store with v2.0"
url: "https://netboxlabs.com/blog/netbox-labs-cmdb-integration-servicenow-v2/"
date: "Wed, 29 Apr 2026 20:59:35 +0000"
author: "Richard Boucher"
feed_url: "https://netboxlabs.com/feed/"
---
<p>Your infrastructure data lives in the NetBox Labs platform. Your ITSM workflows live in ServiceNow. When those two systems drift apart, everything downstream suffers: incidents route to the wrong team, change requests lack context, and audits turn into fire drills. The root cause is almost always the same: data that&#8217;s stale, incomplete, or manually maintained.</p>
<p>The <a href="https://store.servicenow.com/store/app/b5c1950197a8875076b932471153afc7">NetBox Labs CMDB Integration for ServiceNow</a> fixes that. It connects NetBox, the world&#8217;s most popular system of record for complex networks and infrastructure, directly to your ServiceNow CMDB with automated, bidirectional sync. The NetBox Labs platform stays authoritative for the intended state of your infrastructure. ServiceNow enrichment data is preserved. Both teams keep working the way they already do.</p>
<p>Today we&#8217;re announcing that the integration is now certified on the ServiceNow Store, and v2.0 brings a full architectural redesign built for enterprise-grade deployments.</p>
<h2>Store-Certified: What That Means for Your Team</h2>
<p>The NetBox Labs ServiceNow CMDB integration is now available directly on the <a href="https://store.servicenow.com/store/app/b5c1950197a8875076b932471153afc7">ServiceNow Store</a>, meaning it&#8217;s been reviewed, validated, and certified by ServiceNow, and is fully maintained and supported by NetBox Labs.</p>
<p>For IT leaders, that means simplified procurement: no separate vendor approvals, no professional services engagements, and a supported upgrade path. The integration installs as a scoped application that doesn&#8217;t touch your out-of-the-box ServiceNow tables. Your CMDB schema stays exactly as it is.</p>
<p>For ServiceNow admins, it means no scope creep, no global-scope modifications, and no upgrade conflicts. NetBox data stays in its own dedicated table, completely separate from your core CMDB. If you ever need to remove the integration, your ServiceNow instance is exactly where it started.</p>
<p>This is the only supported way to keep your ServiceNow CMDB in sync with your network and infrastructure data automatically, without manual maintenance, custom scripts, or vendor lock-in.</p>
<h2>What&#8217;s New in v2.0</h2>
<p>Version 2.0 is an architectural redesign built for enterprise-grade ServiceNow deployments.</p>
<p><strong>Isolated from your core tables.</strong> The data in the NetBox Labs platform is stored in a dedicated attributes table within the app&#8217;s own scope, not as fields added to ServiceNow&#8217;s base tables. Your core CMDB stays clean, upgrade risk drops drastically, and conflicts with other apps or customizations are eliminated.</p>
<p><strong>Store-native delivery.</strong> You install and update through ServiceNow&#8217;s Application Manager. No more XML update sets or manual upgrade processes.</p>
<p><strong>Built-in migration.</strong> If you&#8217;re already running an earlier version, v2.0 supports migration from v1.x and includes conversion between data models with a guided migration process. Your existing mappings are preserved.</p>
<h2>Building on Proven Capabilities</h2>
<p>v2.0 includes the full set of capabilities introduced in v1.4, now battle-tested across production deployments:</p>
<p><strong>Flexible CI class mapping.</strong> Map NetBox devices to any ServiceNow CI class, including custom classes, through the self-service Class Manager. Your CMDB taxonomy doesn&#8217;t change. The integration adapts to your structure, not the other way around.</p>
<p><strong>Full location hierarchy.</strong> NetBox regions, sites, and locations sync into ServiceNow so every CI carries the physical context needed for incident routing, change management, and compliance scoping.</p>
<p><strong>Tenant configuration wizard.</strong> Map NetBox tenants to ServiceNow departments, customers, or both, configured through the UI. It supports multi-BU, MSP, and subsidiary structures without modifying the integration code.</p>
<h2>How the Integration Works</h2>
<p>The integration syncs devices, device types, sites, regions, locations, manufacturers, and tenants between the NetBox Labs platform and ServiceNow.</p>
<p>Three sync patterns are available: NetBox as the system of record, ServiceNow as the system of record, or a mixed/hybrid approach, configurable per object type. That flexibility matters in real-world deployments where different teams own different data.</p>
<p>The integration uses an event-driven sync to keep data flowing in both directions, with batch imports available for larger updates. A setup wizard walks you through the core configuration.</p>
<p><strong>What to expect:</strong> Initial setup is complete in less than 10 minutes. You&#8217;ll be synchronizing data soon after. Post-deployment, syncs are event-driven and continuous, with no daily maintenance required.</p>
<p><strong>Deployment:</strong> The integration is compatible with NetBox Cloud (via direct connection) and NetBox Enterprise (on-prem via ServiceNow MID Server), and supports ServiceNow Yokohama and Zurich.</p>
<h2>Get Started</h2>
<p>The NetBox CMDB Integration for ServiceNow v2.0 is available now on the ServiceNow Store. It requires a CMDB Integration license for NetBox Cloud or NetBox Enterprise.</p>
<p><a href="https://store.servicenow.com/store/app/b5c1950197a8875076b932471153afc7">Find it on the ServiceNow Store</a>. <a href="https://netboxlabs.com/docs/integrations/tool-integrations/servicenow/">Read the documentation</a> for setup details. Or <a href="https://netboxlabs.com/contact-us/">book a demo</a> to see it in action.</p>
<p>The post <a href="https://netboxlabs.com/blog/netbox-labs-cmdb-integration-servicenow-v2/">NetBox Labs CMDB Integration for ServiceNow Hits the Store with v2.0</a> appeared first on <a href="https://netboxlabs.com">NetBox Labs</a>.</p>
