---
UID: NF:comsvcs.IComCRMEvents.OnCRMRecoveryDone
title: IComCRMEvents::OnCRMRecoveryDone (comsvcs.h)
description: Generated when CRM recovery is done.
old-location: cos\icomcrmevents_oncrmrecoverydone.htm
tech.root: cossdk
ms.assetid: 533148f3-ecb4-495c-81c4-c75db7284ded
ms.date: 12/05/2018
ms.keywords: IComCRMEvents interface [COM+],OnCRMRecoveryDone method, IComCRMEvents.OnCRMRecoveryDone, IComCRMEvents::OnCRMRecoveryDone, OnCRMRecoveryDone, OnCRMRecoveryDone method [COM+], OnCRMRecoveryDone method [COM+],IComCRMEvents interface, _dtc_IComCRMEvents_OnCRMRecoveryDone, comsvcs/IComCRMEvents::OnCRMRecoveryDone, cos.icomcrmevents_oncrmrecoverydone
f1_keywords:
- comsvcs/IComCRMEvents.OnCRMRecoveryDone
dev_langs:
- c++
req.header: comsvcs.h
req.include-header: 
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- ComSvcs.h
api_name:
- IComCRMEvents.OnCRMRecoveryDone
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IComCRMEvents::OnCRMRecoveryDone


## -description


Generated when CRM recovery is done.


## -parameters




### -param pInfo [in]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/comsvcs/ns-comsvcs-comsvcseventinfo">COMSVCSEVENTINFO</a> structure.


### -param guidApp [in]

The globally unique identifier (GUID) of the application.


## -returns



The user verifies the return values from this method.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/comsvcs/nn-comsvcs-icomcrmevents">IComCRMEvents</a>
 

 

