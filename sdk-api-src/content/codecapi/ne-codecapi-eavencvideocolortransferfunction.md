---
UID: NE:codecapi.eAVEncVideoColorTransferFunction
title: eAVEncVideoColorTransferFunction (codecapi.h)
description: Specifies the conversion function from R'G'B' to RGB. This enumeration is used with the AVEncVideoInputColorTransferFunction and AVEncVideoOutputColorTransferFunction properties.
helpviewer_keywords: ["codecapi/eAVEncVideoColorTransferFunction","codecapi/eAVEncVideoColorTransferFunction_10","codecapi/eAVEncVideoColorTransferFunction_18","codecapi/eAVEncVideoColorTransferFunction_20","codecapi/eAVEncVideoColorTransferFunction_22","codecapi/eAVEncVideoColorTransferFunction_22_240M","codecapi/eAVEncVideoColorTransferFunction_22_709","codecapi/eAVEncVideoColorTransferFunction_22_8bit_sRGB","codecapi/eAVEncVideoColorTransferFunction_28","codecapi/eAVEncVideoColorTransferFunction_SameAsSource","dshow.eavencvideocolortransferfunction","eAVEncVideoColorTransferFunction","eAVEncVideoColorTransferFunction enumeration [DirectShow]","eAVEncVideoColorTransferFunctionEnumeration","eAVEncVideoColorTransferFunction_10","eAVEncVideoColorTransferFunction_18","eAVEncVideoColorTransferFunction_20","eAVEncVideoColorTransferFunction_22","eAVEncVideoColorTransferFunction_22_240M","eAVEncVideoColorTransferFunction_22_709","eAVEncVideoColorTransferFunction_22_8bit_sRGB","eAVEncVideoColorTransferFunction_28","eAVEncVideoColorTransferFunction_SameAsSource"]
old-location: dshow\eavencvideocolortransferfunction.htm
tech.root: dshow
ms.assetid: 447e6df7-6e6b-4dff-87e5-0308eb0a3dae
ms.date: 4/26/2023
ms.keywords: codecapi/eAVEncVideoColorTransferFunction, codecapi/eAVEncVideoColorTransferFunction_10, codecapi/eAVEncVideoColorTransferFunction_18, codecapi/eAVEncVideoColorTransferFunction_20, codecapi/eAVEncVideoColorTransferFunction_22, codecapi/eAVEncVideoColorTransferFunction_22_240M, codecapi/eAVEncVideoColorTransferFunction_22_709, codecapi/eAVEncVideoColorTransferFunction_22_8bit_sRGB, codecapi/eAVEncVideoColorTransferFunction_28, codecapi/eAVEncVideoColorTransferFunction_SameAsSource, dshow.eavencvideocolortransferfunction, eAVEncVideoColorTransferFunction, eAVEncVideoColorTransferFunction enumeration [DirectShow], eAVEncVideoColorTransferFunctionEnumeration, eAVEncVideoColorTransferFunction_10, eAVEncVideoColorTransferFunction_18, eAVEncVideoColorTransferFunction_20, eAVEncVideoColorTransferFunction_22, eAVEncVideoColorTransferFunction_22_240M, eAVEncVideoColorTransferFunction_22_709, eAVEncVideoColorTransferFunction_22_8bit_sRGB, eAVEncVideoColorTransferFunction_28, eAVEncVideoColorTransferFunction_SameAsSource
req.header: codecapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - eAVEncVideoColorTransferFunction
 - codecapi/eAVEncVideoColorTransferFunction
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - codecapi.h
api_name:
 - eAVEncVideoColorTransferFunction
---

# eAVEncVideoColorTransferFunction enumeration


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Specifies the conversion function from R'G'B' to RGB. This enumeration is used with the <a href="/windows/desktop/DirectShow/avencvideoinputcolortransferfunction-property">AVEncVideoInputColorTransferFunction</a> and <a href="/windows/desktop/DirectShow/avencvideooutputcolortransferfunction-property">AVEncVideoOutputColorTransferFunction</a> properties.

## -enum-fields

### -field eAVEncVideoColorTransferFunction_SameAsSource:0

Use the same function as the input video. This flag applies to the <b>AVEncVideoOutputColorTransferFunction</b> property only.

### -field eAVEncVideoColorTransferFunction_10:1

Linear RGB (gamma = 1.0).

### -field eAVEncVideoColorTransferFunction_18:2

True 1.8 gamma. L' = L^1/1.8.

### -field eAVEncVideoColorTransferFunction_20:3

True 2.0 gamma. L' = L^1/2.0..

### -field eAVEncVideoColorTransferFunction_22:4

True 2.2 gamma. L' = L^1/2.2..

### -field eAVEncVideoColorTransferFunction_22_709:5

Gamma 2.2 curve with a linear segment in the lower range. L' = 4.5L, for L &lt; 0.018; L' = 1.099L^0.45.- 0.099, for L &gt;= 0.018. This transfer function is used in BT-709, SMPTE 296M, SMPTE 170M, BT-470, and SPMTE 274M.

### -field eAVEncVideoColorTransferFunction_22_240M:6

Gamma 2.2 curve with a linear segment in the lower range. L' = 4.0L, for L &lt; 0.0228; L' = 1.1115^L0.45.- 0.01115, for L &gt;= 0.0228. This transfer function is used in SPMTE 240M.

### -field eAVEncVideoColorTransferFunction_22_8bit_sRGB:7

Gamma 2.4 curve with a linear segment in the lower range. L' = L/12.92, for L &lt; 0.03928; L' = ((L + 0.055) / 1.055)^2.4., for L &gt;= 0.03928.

### -field eAVEncVideoColorTransferFunction_28:8

True 2.8 gamma. L' = L^1/2.8..

## -see-also

<a href="/windows/desktop/DirectShow/codec-api-enumerations">Codec API Enumerations</a>



<a href="/windows/desktop/api/strmif/nn-strmif-icodecapi">ICodecAPI Interface</a>
