<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [getAugmentationPrereq](./bitburner.singularity.getaugmentationprereq.md)

## Singularity.getAugmentationPrereq() method

If you are not in BitNode-4, then you must have Level 3 of Source-File 4 in order to use this function and the RAM cost is doubled.

This function returns an array with the names of the prerequisite Augmentation(s) for the specified Augmentation. If there are no prerequisites, a blank array is returned.

<b>Signature:</b>

```typescript
getAugmentationPrereq(augName: AugmentName): AugmentName[];
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  augName | [AugmentName](./bitburner.augmentname.md) | Name of Augmentation. |

<b>Returns:</b>

[AugmentName](./bitburner.augmentname.md)<!-- -->\[\]

Array with the names of the prerequisite Augmentation(s) for the specified Augmentation.

## Remarks

5 GB  Level 3
