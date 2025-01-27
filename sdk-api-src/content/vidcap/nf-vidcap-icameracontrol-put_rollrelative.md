---
UID: NF:vidcap.ICameraControl.put_RollRelative
title: ICameraControl::put_RollRelative (vidcap.h)
description: The put_RollRelative method sets the camera's relative roll. The relative roll is expressed as a number of steps, where the size of each step depends on the camera model.
helpviewer_keywords: ["ICameraControl interface [DirectShow]","put_RollRelative method","ICameraControl.put_RollRelative","ICameraControl::put_RollRelative","ICameraControlput_RollRelative","dshow.icameracontrol_put_rollrelative","put_RollRelative","put_RollRelative method [DirectShow]","put_RollRelative method [DirectShow]","ICameraControl interface","vidcap/ICameraControl::put_RollRelative"]
old-location: dshow\icameracontrol_put_rollrelative.htm
tech.root: dshow
ms.assetid: b0dbfd1c-493f-4f35-88ab-cd3868a56370
ms.date: 4/26/2023
ms.keywords: ICameraControl interface [DirectShow],put_RollRelative method, ICameraControl.put_RollRelative, ICameraControl::put_RollRelative, ICameraControlput_RollRelative, dshow.icameracontrol_put_rollrelative, put_RollRelative, put_RollRelative method [DirectShow], put_RollRelative method [DirectShow],ICameraControl interface, vidcap/ICameraControl::put_RollRelative
req.header: vidcap.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - ICameraControl::put_RollRelative
 - vidcap/ICameraControl::put_RollRelative
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - ICameraControl.put_RollRelative
---

# ICameraControl::put_RollRelative


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>put_RollRelative</code> method sets the camera's relative roll. The relative roll is expressed as a number of steps, where the size of each step depends on the camera model.

## -parameters

### -param Value [in]

Specifies the relative roll. The size of the value represents the desired rotation speed; a higher value represents a higher speed. To get the range of possible values, call <a href="/windows/desktop/api/vidcap/nf-vidcap-icameracontrol-getrange_rollrelative">ICameraControl::getRange_RollRelative</a>.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>0</td>
<td>Stop the roll.</td>
</tr>
<tr>
<td>Positive value</td>
<td>Start rotating clockwise around the viewing axis.</td>
</tr>
<tr>
<td>Negative value</td>
<td>Start rotating counterclockwise around the viewing axis.</td>
</tr>
</table>

### -param Flags [in]

Zero or more flags. See <a href="/windows/win32/api/strmif/ne-strmif-cameracontrolflags">CameraControlFlags</a>. If the CameraControl_Flags_Auto flag is used, the <i>Value</i> parameter is ignored and the camera sets the default value.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/vidcap/nn-vidcap-icameracontrol">ICameraControl Interface</a>