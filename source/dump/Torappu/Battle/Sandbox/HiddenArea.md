# HiddenArea

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Rect rect`

- `Boolean isHidden`


## Methods

- `Boolean IsInArea(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class HiddenArea : IHotfixable
{
	public Rect rect; // 0x10
	public Boolean isHidden; // 0x20
	private static DelegateBridge __Hotfix0_IsInArea; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1df3fbc VA: 0x759440bfbc
	public Boolean IsInArea(Int32 row, Int32 col) { }
	// RVA: 0x1df40b0 VA: 0x759440c0b0
	public Void .ctor() { }
}
```