# UIOperationTarget

**Namespace:** ` `


## Fields

- `String name`

- `AnimationWrapper wrapper`

- `String clipName`

- `Ease fadeOutEase`

- `Single fadeOutTime`

- `CanvasGroup mainCanvas`

- `Boolean isEnabled`


## Methods

- `Void OnEnable(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UIOperationTarget
{
	public String name; // 0x10
	public CanvasGroup[] targetCanvas; // 0x18
	public Graphic[] targetGraphic; // 0x20
	public AnimationWrapper wrapper; // 0x28
	public String clipName; // 0x30
	public Ease fadeOutEase; // 0x38
	public Single fadeOutTime; // 0x3c
	public CanvasGroup mainCanvas; // 0x40
	public Boolean isEnabled; // 0x48


	// RVA: 0x1d23eb4 VA: 0x759433beb4
	public Void OnEnable(Boolean enable, Boolean force) { }
	// RVA: 0x1d256b8 VA: 0x759433d6b8
	public virtual Void OnComplete() { }
	// RVA: 0x1d257a4 VA: 0x759433d7a4
	public Void .ctor() { }
}
```