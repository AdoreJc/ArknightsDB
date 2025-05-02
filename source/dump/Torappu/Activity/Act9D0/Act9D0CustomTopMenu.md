# Act9D0CustomTopMenu

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `RectTransform _btnBack`


## Methods

- `Void OnClickBack()`

- `Void OnClickHome()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0CustomTopMenu : Act9D0CustomTopMenuBase, IHotfixable
{
	private RectTransform _btnBack; // 0x28
	private static DelegateBridge __Hotfix0_InitTopMenu; // 0x0
	private static DelegateBridge __Hotfix0_OnClickBack; // 0x8
	private static DelegateBridge __Hotfix0_OnClickHome; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31aefd0 VA: 0x75957c6fd0
	protected override Void InitTopMenu() { }
	// RVA: 0x31af0c8 VA: 0x75957c70c8
	public Void OnClickBack() { }
	// RVA: 0x31af164 VA: 0x75957c7164
	public Void OnClickHome() { }
	// RVA: 0x31af1f8 VA: 0x75957c71f8
	public Void .ctor() { }
}
```