# HotUpdateProgressModel

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Progress progress`

- `String hint`


## Methods

- `String GetHintText()`

- `IconType GetIconType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateProgressModel : IHotfixable
{
	public Progress progress; // 0x10
	public String hint; // 0x18
	private static DelegateBridge __Hotfix0_GetHintText; // 0x0
	private static DelegateBridge __Hotfix0_GetIconType; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27bbb08 VA: 0x7594dd3b08
	public String GetHintText() { }
	// RVA: 0x27bbb8c VA: 0x7594dd3b8c
	public IconType GetIconType() { }
	// RVA: 0x27bbc04 VA: 0x7594dd3c04
	public Void .ctor() { }
}
```