---
ns: PED
---
## _GET_PED_HEAD_BLEND_DATA

```c
// 0x2746BD9D88C5C5D0
BOOL _GET_PED_HEAD_BLEND_DATA(Ped ped, Any* headBlendData);
```

```
The pointer is to a padded struct that matches the arguments to SET_PED_HEAD_BLEND_DATA(...). There are 4 bytes of padding after each field.  
(Edit) Console Hash: 0x44E1680C  
pass this struct in the second parameter   
typedef struct  
{  
        int shapeFirst, shapeSecond, shapeThird;   
        int skinFirst, skinSecond, skinThird;   
	float shapeMix, skinMix, thirdMix;  
} headBlendData;  
```

## Parameters
* **ped**: 
* **headBlendData**: 

## Return value
