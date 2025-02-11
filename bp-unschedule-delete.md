---

copyright:
  years: 2022, 2024
lastupdated: "2024-10-30"

keywords: bandwidth metering, bandwidth pools

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# Unscheduling deletion of bandwidth pools
{: #how-to-unschedule-deletion-bw-pools}
{: ui}

You can unschedule the deletion a bandwidth pool from your {{site.data.keyword.cloud}} account by using the following instructions. 
{: shortdesc}

Unscheduling the deletion of the pool does not unschedule the ejection of its members. You must readd devices to the bandwidth pool that are ejected on your billing anniversary. 
{: important}

To unschedule the deletion of a bandwidth pool by using the UI, follow these steps:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select the Navigation menu ![Navigation menu](../icons/icon_hamburger.svg), then click **Infrastructure > Classic Infrastructure**.
1. Select **Network > Bandwidth > Pools**.
1. Locate the bandwidth pool where you want to unschedule the deletion. Use the **Region** and **Overage Status** filters as necessary. The status "Pool deletion scheduled" appears next to the pool name.
1. Click this status, then click the **Unschedule** button in the tooltip that appears. Alternatively, you can click the **Actions** menu ![Actions menu](../icons/action-menu-icon.svg) at the end of the row, then select the **Unschedule deletion** option.
1. Acknowledge the unschedule deletion details, then click **Unschedule**.

You can also access the bandwidth pool's details page to unschedule the deletion of a bandwidth pool. Click the **Pool deletion scheduled** status, then click **Unschedule**.
{: note}
