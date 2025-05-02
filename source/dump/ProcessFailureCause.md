# ProcessFailureCause

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NoFailure |

| 1 | FailureCauseImageHasNullMainTexture |

| 2 | FailureCauseImageHasNullSprite |

| 3 | FailureCauseSpriteHasNonQuadMesh |

| 4 | FailureCauseSpriteHasAssociatedAlphaSplitTexture |

| 5 | FailureCauseSpriteRectHasNoPadding |

| 6 | FailureCauseTextureWidthExceedLimit |

| 7 | FailureCauseTextureHeightExceedLimit |

| 8 | FailureCauseTextureFormatNotCompatible |

| 9 | FailureCauseTextureSizeNotAlignedForCopyTexture |

| 10 | FailureCauseAtlasTextureHasNoSpaceLeft |

## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : 
public enum ProcessFailureCause
{
	public Int32 value__; // 0x10
	public const ProcessFailureCause NoFailure = 0; // 0x0
	public const ProcessFailureCause FailureCauseImageHasNullMainTexture = 1; // 0x0
	public const ProcessFailureCause FailureCauseImageHasNullSprite = 2; // 0x0
	public const ProcessFailureCause FailureCauseSpriteHasNonQuadMesh = 3; // 0x0
	public const ProcessFailureCause FailureCauseSpriteHasAssociatedAlphaSplitTexture = 4; // 0x0
	public const ProcessFailureCause FailureCauseSpriteRectHasNoPadding = 5; // 0x0
	public const ProcessFailureCause FailureCauseTextureWidthExceedLimit = 6; // 0x0
	public const ProcessFailureCause FailureCauseTextureHeightExceedLimit = 7; // 0x0
	public const ProcessFailureCause FailureCauseTextureFormatNotCompatible = 8; // 0x0
	public const ProcessFailureCause FailureCauseTextureSizeNotAlignedForCopyTexture = 9; // 0x0
	public const ProcessFailureCause FailureCauseAtlasTextureHasNoSpaceLeft = 10; // 0x0


}
```