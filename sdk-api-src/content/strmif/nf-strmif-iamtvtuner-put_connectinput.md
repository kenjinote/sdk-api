---
UID: NF:strmif.IAMTVTuner.put_ConnectInput
title: IAMTVTuner::put_ConnectInput (strmif.h)
description: The put_ConnectInput method sets the hardware tuner input connection.
helpviewer_keywords: ["IAMTVTuner interface [DirectShow]","put_ConnectInput method","IAMTVTuner.put_ConnectInput","IAMTVTuner::put_ConnectInput","IAMTVTunerput_ConnectInput","dshow.iamtvtuner_put_connectinput","put_ConnectInput","put_ConnectInput method [DirectShow]","put_ConnectInput method [DirectShow]","IAMTVTuner interface","strmif/IAMTVTuner::put_ConnectInput"]
old-location: dshow\iamtvtuner_put_connectinput.htm
tech.root: dshow
ms.assetid: d0ea5d82-acb6-401a-942a-99d34058c648
ms.date: 4/26/2023
ms.keywords: IAMTVTuner interface [DirectShow],put_ConnectInput method, IAMTVTuner.put_ConnectInput, IAMTVTuner::put_ConnectInput, IAMTVTunerput_ConnectInput, dshow.iamtvtuner_put_connectinput, put_ConnectInput, put_ConnectInput method [DirectShow], put_ConnectInput method [DirectShow],IAMTVTuner interface, strmif/IAMTVTuner::put_ConnectInput
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
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
 - IAMTVTuner::put_ConnectInput
 - strmif/IAMTVTuner::put_ConnectInput
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
 - IAMTVTuner.put_ConnectInput
---

# IAMTVTuner::put_ConnectInput


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>put_ConnectInput</code> method sets the hardware tuner input connection.

## -parameters

### -param lIndex [in]

Index value of the input pin to set connection for.

## -returns

Returns an <b>HRESULT</b> value that depends on the implementation of the interface.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-iamtvtuner">IAMTVTuner Interface</a>



<a href="/windows/desktop/api/strmif/nn-strmif-iamtuner">IAMTuner Interface</a>