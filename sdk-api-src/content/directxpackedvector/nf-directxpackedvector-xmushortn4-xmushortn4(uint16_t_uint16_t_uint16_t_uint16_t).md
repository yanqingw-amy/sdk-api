---
UID: NF:directxpackedvector.XMUSHORTN4.XMUSHORTN4(uint16_t,uint16_t,uint16_t,uint16_t)
title: XMUSHORTN4::XMUSHORTN4(uint16_t,uint16_t,uint16_t,uint16_t) (directxpackedvector.h)
description: Initializes a new instance of XMUSHORTN4 from four uint16_t arguments.helpviewer_keywords: ["XMUSHORTN4","XMUSHORTN4 constructor [DirectX Math Support APIs]","XMUSHORTN4 constructor [DirectX Math Support APIs]","XMUSHORTN4 structure","XMUSHORTN4 structure [DirectX Math Support APIs]","XMUSHORTN4 constructor","XMUSHORTN4.XMUSHORTN4","XMUSHORTN4.XMUSHORTN4(uint16_t","uint16_t","uint16_t","uint16_t)","XMUSHORTN4::XMUSHORTN4","XMUSHORTN4::XMUSHORTN4(uint16_t","uint16_t","uint16_t","uint16_t)","dxmath.xmushortn4_ctor_2"]
old-location: dxmath\xmushortn4_ctor_2.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.reference.XMUSHORTN4.#ctor(uint16_t,uint16_t,uint16_t,uint16_t)
ms.date: 12/05/2018
ms.keywords: XMUSHORTN4, XMUSHORTN4 constructor [DirectX Math Support APIs], XMUSHORTN4 constructor [DirectX Math Support APIs],XMUSHORTN4 structure, XMUSHORTN4 structure [DirectX Math Support APIs],XMUSHORTN4 constructor, XMUSHORTN4.XMUSHORTN4, XMUSHORTN4.XMUSHORTN4(uint16_t,uint16_t,uint16_t,uint16_t), XMUSHORTN4::XMUSHORTN4, XMUSHORTN4::XMUSHORTN4(uint16_t,uint16_t,uint16_t,uint16_t), dxmath.xmushortn4_ctor_2
f1_keywords:
- directxpackedvector/XMUSHORTN4.XMUSHORTN4
dev_langs:
- c++
req.header: directxpackedvector.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: DirectX::PackedVector
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
- DirectXPackedVector.h
api_name:
- XMUSHORTN4.XMUSHORTN4
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMUSHORTN4::XMUSHORTN4(uint16_t,uint16_t,uint16_t,uint16_t)


## -description


Initializes a new instance of <code>XMUSHORTN4</code> from four <code>uint16_t</code> arguments.
    

This constructor initializes a new instance of <a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/ns-directxpackedvector-xmushortn4">XMUSHORTN4</a> from four
	<code>uint16_t</code> arguments.
<div class="alert"><b>Note</b>  This constructor is only available under C++.
    </div><div> </div>

## -parameters




### -param _x

Value of the x-coordinate of the vector, the <b>x</b> member of the new
		    <code>XMUSHORTN4</code> instance.
		


### -param _y

Value of the y-coordinate of the vector, the <b>y</b> member of the new
		    <code>XMUSHORTN4</code> instance.
		


### -param _z

Value of the z-coordinate of the vector, the <b>z</b> member of the new
		    <code>XMUSHORTN4</code> instance.
		


### -param _w

Value of the w-coordinate of the vector, the <b>w</b> member of the new
		    <code>XMUSHORTN4</code> instance.
		


## -remarks



Input values are not normalized. The following pseudocode demonstrates the operation of
	    this constructor:
	


```

	XMUSHORTN4 instance;

	instance.x = _x;
	instance.y = _y;
	instance.z = _z;
	instance.w = _w;

    
```





## -see-also




<b>Reference</b>



<a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/ns-directxpackedvector-xmushortn4">XMUSHORTN4</a>



<a href="https://docs.microsoft.com/windows/desktop/dxmath/xmushortn4-ctor">XMUSHORTN4 Constructors</a>
 

 

