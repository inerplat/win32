---
Description: Contains a pointer to the IMFNetResourceFilter callback interface for the Microsoft Media Foundation HTTP byte stream.
ms.assetid: C035B4AD-CF99-4A4F-9384-F80A3620BD27
title: MFNETSOURCE\_RESOURCE\_FILTER property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MFNETSOURCE\_RESOURCE\_FILTER property

Contains a pointer to the [**IMFNetResourceFilter**](/windows/desktop/api/mfidl/nn-mfidl-imfnetresourcefilter) callback interface for the Microsoft Media Foundation HTTP byte stream.



Data type

PROPVARIANT type (vt)

PROPVARIANT member

**IUnknown\***

VT\_UNKNOWN

**punkVal**



## Remarks

Use this property to configure the Media Foundation HTTP byte stream. To set the property, pass an [**IPropertyStore**](https://msdn.microsoft.com/e995aaa1-d4c9-475f-b1fa-b9123cd5b653) pointer to the source resolver. For more information, see [Configuring a Media Source](configuring-a-media-source.md).

## Requirements



|                                     |                                                                                    |
|-------------------------------------|------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8 \[desktop apps only\]<br/>                                         |
| Minimum supported server<br/> | Windows Server 2012 \[desktop apps only\]<br/>                               |
| Header<br/>                   | <dl> <dt>Mfidl.h</dt> </dl> |



## See also

<dl> <dt>

[Media Foundation Properties](media-foundation-properties.md)
</dt> </dl>

 

 



