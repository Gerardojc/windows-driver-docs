---
title: IPrinterScriptUsbJobContext interface
description: The IPrinterScriptUsbJobContext interface is passed as a parameter to the startPrintJob JavaScript function.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
keywords: ["IPrinterScriptUsbJobContext interface Print Devices", "IPrinterScriptUsbJobContext interface Print Devices , described"]
topic_type:
- apiref
api_name:
- IPrinterScriptUsbJobContext
api_type:
- COM
ms.date: 04/20/2017
---

# IPrinterScriptUsbJobContext interface

The IPrinterScriptUsbJobContext interface is passed as a parameter to the **startPrintJob** JavaScript function.

## Members

The **IPrinterScriptUsbJobContext** interface inherits from the [**IUnknown**](/windows/win32/api/unknwn/nn-unknwn-iunknown) interface. **IPrinterScriptUsbJobContext** also has these types of members:

-   [Methods](#methods)

### Methods

The **IPrinterScriptUsbJobContext** interface has these methods.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Method</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="iprinterscriptusbjobcontext-jobpropertybag.md" data-raw-source="[&lt;strong&gt;JobPropertyBag&lt;/strong&gt;](iprinterscriptusbjobcontext-jobpropertybag.md)"><strong>JobPropertyBag</strong></a></td>
<td><p>Returns the property bag associated with the current print job.</p></td>
</tr>
<tr class="even">
<td><a href="iprinterscriptusbjobcontext-printedpagecount.md" data-raw-source="[&lt;strong&gt;PrintedPageCount&lt;/strong&gt;](iprinterscriptusbjobcontext-printedpagecount.md)"><strong>PrintedPageCount</strong></a></td>
<td><p>Returns the number of pages that have been printed by the print device in the current job.</p></td>
</tr>
<tr class="odd">
<td><a href="iprinterscriptusbjobcontext-printedpagecount-in.md" data-raw-source="[&lt;strong&gt;PrintedPageCount&lt;/strong&gt;](iprinterscriptusbjobcontext-printedpagecount-in.md)"><strong>PrintedPageCount</strong></a></td>
<td><p>Sets the number of pages that have been printed by the print device in the current job.</p></td>
</tr>
<tr class="even">
<td><a href="iprinterscriptusbjobcontext-returncodes.md" data-raw-source="[&lt;strong&gt;ReturnCodes&lt;/strong&gt;](iprinterscriptusbjobcontext-returncodes.md)"><strong>ReturnCodes</strong></a></td>
<td><p>Returns an object that can supply return code values that an IHV has defined for their JavaScript functions.</p></td>
</tr>
<tr class="odd">
<td><a href="iprinterscriptusbjobcontext-temporarystreams.md" data-raw-source="[&lt;strong&gt;TemporaryStreams&lt;/strong&gt;](iprinterscriptusbjobcontext-temporarystreams.md)"><strong>TemporaryStreams</strong></a></td>
<td><p>Returns an array of <a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterscriptablesequentialstream" data-raw-source="[IPrinterScriptableSequentialStream](/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterscriptablesequentialstream)">IPrinterScriptableSequentialStream</a> interfaces for the persistent data streams that can be used by the IHV JavaScript functions for the current job.</p></td>
</tr>
</tbody>
</table>

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 8.1</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2012 R2</p></td>
</tr>
</tbody>
</table>
