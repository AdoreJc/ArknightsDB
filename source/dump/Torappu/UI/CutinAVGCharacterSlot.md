# CutinAVGCharacterSlot

**Namespace:** `Torappu.UI`


## Fields

- `AVGCharacterSlot _charslot`

- `UIStencilComponent _foreImgStencilComponent`

- `UIStencilComponent _backImgStencilComponent`

- `String m_cachedChar`


## Methods

- `Void _SetStencilComp(CutinElementParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinAVGCharacterSlot : CutinElement
{
	private AVGCharacterSlot _charslot; // 0x18
	private UIStencilComponent _foreImgStencilComponent; // 0x20
	private UIStencilComponent _backImgStencilComponent; // 0x28
	private String m_cachedChar; // 0x30
	private static DelegateBridge __Hotfix0_DoMove; // 0x0
	private static DelegateBridge __Hotfix0_DoScale; // 0x8
	private static DelegateBridge __Hotfix0_SetCutinElement; // 0x10
	private static DelegateBridge __Hotfix0__SetStencilComp; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x216a1f8 VA: 0x75947821f8
	public override Tween DoMove(Vector3 fromPos, Vector3 toPos, Single duration) { }
	// RVA: 0x216a2e8 VA: 0x75947822e8
	public override Tween DoScale(Vector3 scaleFrom, Vector3 scaleTo, Single duration) { }
	// RVA: 0x216a404 VA: 0x7594782404
	public override Tween SetCutinElement(CutinElementParam param, ILoadAsset assetLoader) { }
	// RVA: 0x216a558 VA: 0x7594782558
	private Void _SetStencilComp(CutinElementParam param) { }
	// RVA: 0x216a5fc VA: 0x75947825fc
	public Void .ctor() { }
}
```