---
Description: IPv6LinkMTU
MS-HAID: CarrierControlSchema\_v2.element\_IPv6LinkMTU
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: IPv6LinkMTU
ms.assetid: 9d7ca5ab-9be7-466f-bef9-48a84b0e7e7b
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# IPv6LinkMTU


Defines the maximum transmission unit (MTU) for an IPv6 link. It must be a positive integer between 1280 and 1500.

## Element hierarchy

<dl>
<dt><a href="element-extensions-v2.md">&lt;Extensions_v2&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-carriernetworkmetadata.md">&lt;CarrierNetworkMetadata&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-networksettings.md">&lt;NetworkSettings&gt;</a></dt>
<dd><b>&lt;IPv6LinkMTU&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<IPv6LinkMTU>

  Defines a simple type for the maximum transmission unit (MTU).

</IPv6LinkMTU>
```

## Attributes and Elements


### Attributes

None.

### Child Elements

None.

### Parent Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parent Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[NetworkSettings](element-networksettings.md)</td>
<td><p>Defines the network settings in a subscriber's carrier provisioning file.</p></td>
</tr>
</tbody>
</table>

 

## Remarks

This setting is applied to all the profiles defined in a subscriber's carrier provisioning file.

## See also


[CarrierControlSchema schema](https://msdn.microsoft.com/library/windows/apps/hh868312)

[CarrierControlSchema\_v2 schema](schema-root.md)

[**NetworkSettings**](element-networksettings.md)

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/v2</p></td>
</tr>
</tbody>
</table>

 

 


